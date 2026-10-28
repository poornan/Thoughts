# Technical Limitations Should Not Drive Architectural Decisions

### Technical Limitations Should Not Drive Architectural Decisions: When the Easy Path Becomes the Architecture

[Anan](https://substack.com/@anan12)Apr 02, 2026

> A bricklayer builds walls. An architect decides where walls go. Both are necessary. But if you ask the bricklayer to design the building, you get a building that is all walls. Not because the bricklayer is bad, but because the question they are trained to answer is “how do I lay this brick?” not “should there be a wall here?”

There is a moment in every engineering team’s life when someone proposes changing the architecture because a technical problem resists solution. The proposal sounds reasonable. The language is professional. The diagrams are clean. But the reason behind it is not architectural. It is a response to a problem that the team’s structure was not designed to solve at the right layer.

## **The Scenario**

Consider a message-processing system built on an enterprise integration framework. System A generates events. System B enriches them. System C, a new addition, consumes the enriched events. The design is straightforward: A emits events to B, B processes and emits to C. This follows event-driven principles: producers emit, consumers decide what to process based on event semantics.

Now suppose a technical problem arises. The integration framework needs to connect to two different message broker contexts simultaneously, one for the A-to-B channel and one for the B-to-C channel. After two weeks of investigation, the effort surfaces log entries showing “connection failed,” but the root cause remains unresolved. The problem is escalated.

The root cause is a configuration-level problem: two broker contexts competing for the same connection parameters. It is solvable at the technical layer, but it requires a depth of framework knowledge that the team was never resourced to develop. No one on the team was hired for this specific expertise. No one was given time to acquire it. The team was structured to deliver features, not to resolve framework-level integration conflicts.

In the absence of that expertise, a different proposal emerges: change the architecture so that System A decides at the point of emission whether to route to B or C, eliminating the need for B to maintain two broker connections.

## **What Just Happened**

The architectural proposal is technically valid. It would work. But it violates a design principle the team had already adopted: in an event-driven system, producers emit events by type. They do not decide where events go. Routing intelligence belongs to the consumer or the broker, not the producer. This separation exists for a reason: it allows new consumers to be added without modifying the producer, it keeps the system loosely coupled, and it makes rollback and phased deployment possible.

The team had a rollback plan. They had a release strategy. They had chosen A-to-B-to-C precisely because messages were already flowing on the A-to-B channel, and C was new. B and C could be correlated and rolled out incrementally.

The alternative proposal, A deciding B-or-C, would have collapsed this separation. It would have introduced producer-side routing logic that would need to be maintained, tested, and eventually removed when the connection problem was eventually solved anyway. It would have created technical debt to avoid a technical problem.

This is the structural moment. The question “how do I connect these two brokers?” was answered with “let’s move the wall.” Not because anyone was wrong, but because the team’s structure made the wall-moving answer more available than the connection-fixing answer.

> **The bricklayer’s incentive**
>
> Charlie Munger tells the story of FedEx’s night shift. Workers had to rapidly sort and transfer packages between planes at a central hub. The system’s integrity depended on speed. But the crew was paid by the hour. Management tried moral suasion, pep talks, everything. Nothing worked. Then they switched to a fixed shift rate: you can go home when the job is done. Workers immediately moved as fast as possible. Transfer times improved dramatically.
>
> Munger’s lesson: “Never, ever, think about something else when you should be thinking about the power of incentives.”
>
> The bricklayer version is older. Frederick Taylor’s differential piece-rate system in the early 1900s showed that bricklayers paid per brick laid 1,000 bricks a day. Paid per wall completed, they laid 3,500. Frank Gilbreth, who started as a bricklayer’s apprentice, reduced the motions per brick from 18 to 4.5 by asking a different question: not “how do I lay this brick?” but “how do I finish this wall?”
>
> The opening metaphor of this essay is the same structure. When the question is “how do I lay this brick?” (solve this connection problem), the bricklayer optimises for bricks. When the question is “should there be a wall here?” (is this the right architecture), the answer requires a different incentive, a different scope of vision, and often a different person. The organisation that pays for bricks and expects walls gets neither efficiently.

## **The Pattern**

This is not an isolated incident. It is a pattern that recurs wherever the organisation has not invested in the implementation-layer capability that the problem’s complexity demands, and the structure provides no mechanism to bridge the gap.

The pattern works like this:

1. A technical problem arises that requires deep framework knowledge
2. The team does not have that knowledge, and has no path to acquire it within the delivery timeline
3. The problem is escalated, and in the process, reframed: “maybe we should redesign this part”
4. A manager or architect, under time pressure, considers the redesign
5. If accepted, a capability gap at one layer becomes a permanent design compromise at another

The redesign is not proposed because the architecture is wrong. It is proposed because the implementation problem exceeds the capability the team’s structure was designed to produce. These are different problems with different solutions. Conflating them is how systems accumulate accidental complexity.

## **Why It Matters**

In a well-functioning team, someone with architectural insight is not doing production coding. They are reviewing designs, setting constraints, evaluating trade-offs, and intervening when implementation decisions threaten architectural integrity. They have the bandwidth to see these moments.

But in teams where the architect also carries a full implementation load, something different happens. The architect is occupied. Others on the team, who are skilled implementers focused on their delivery scope, have more available time to shape direction. Not because they seized it, but because the structure allocated the architect’s attention elsewhere.

> **The misplaced architect**
>
> “When architecture is not clearly understood, architects get pulled into delivery work, not because they belong there, but because the organization doesn’t know what else to do with them.” — Gregor Hohpe, 2021
>
> This is especially damaging at the enterprise and systems architecture levels, where the role is meant to operate across time horizons, domains, and initiatives. When reduced to a delivery contributor, the architect is cut off from their real value: building coherence, shaping direction, and enabling lasting change.

It is a structural problem. The team members proposing the architectural change are acting rationally within what the organisation made visible to them. They see a connection that does not work. They see a design change that would eliminate the connection problem. From within the implementation layer, the proposal makes sense.

What is not visible from that layer is the design principle being violated, the coupling being introduced, the rollback strategy being compromised, the precedent being set. It is not visible because nothing in the team’s structure, training, or incentives required anyone to see it. The organisation’s hiring and evaluation criteria tested configuration skills, not architectural reasoning. The gap is in what the structure selected for, not in what individuals could have learned.

## **The Discipline**

The discipline is simple to state and difficult to maintain:

**Never change the architecture to avoid solving a technical problem.**

Solve the technical problem. If the architecture genuinely needs to change, that decision should be driven by a change in requirements, a change in scale, or a change in the domain model, never by a gap in implementation capability.

This requires someone in the room who can distinguish between the two. Someone who asks: “Are we changing the design because the design is wrong, or because we have not yet solved the implementation?” If no one asks this question, every unsolved technical problem becomes an architectural decision. Over time, the system’s architecture is not the product of intentional design. It is the accumulated residue of problems that were never solved at the right layer.

And here is the ego test: the architect who insists on the original design must also ask themselves whether they are defending the architecture from judgment or from identity. Kent Beck’s question applies: “Is my resistance to this proposal principle or ego? Does my practiced judgment still apply here, or am I defending a workflow that no longer fits?” The discipline cuts both ways. The person who says “never change the architecture” and the person who says “let’s just redesign it” may both be avoiding the harder question, which is: what capability does this team need that it does not have, and whose responsibility is it to provide it?

## **The Connection to Purpose**

There is a broader principle here. Purpose exists at the layer above the one you operate in. A developer’s purpose is not just to write code that works. It is to ensure that the code serves the architecture, which serves the system, which serves the users, which serves the institution. But this purpose is only visible if the organisation makes it visible. If the incentive is “close the ticket,” the developer closes the ticket. That is not a character flaw. That is the system working as designed.

When a technical limitation drives an architectural decision, the layers collapse. The implementation layer dictates to the design layer. The design layer, which should be governed by strategic intent, domain modelling, and long-term maintainability, instead becomes a function of what the team could and could not solve on a particular week.

This is how systems decay. Not through catastrophic failure, but through a thousand small surrenders where the path of least resistance was taken because the organisation did not invest in the capability to take the harder path. Each surrender is rational. The accumulated effect is an architecture that no one designed and no one can explain.

The fix is not better developers. The fix is structural: ensure that someone with architectural authority has the bandwidth to exercise it, ensure that technical problems are solved at the technical layer before they are escalated to the design layer, and ensure that the organisation asks the question before the team has to: “Is this a design problem or a capability problem?”

The answer determines whether the system gets better or just gets different.

#### Discussion about this post

CommentsRestacks

No posts

### Ready for more?
