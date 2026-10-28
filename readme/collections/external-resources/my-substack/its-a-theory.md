# “It’s a Theory”

### What the complaint reveals about the structure behind it

[Anan](https://substack.com/@anan12)Apr 02, 2026

_This is part 2 of a four-part series decomposing_ [_It’s a Theory: Complains_](/broken/pages/384f06432fa10178a5d469053ccbda0df6701e8f)_._

***

“It’s a theory. It’s not practical.” Or its sibling: “That’s too academic.”

These are said with the confidence of someone who believes they have ended an argument. They have not. They have revealed something about the structure they operate within.

> **“I am paid to think, not to play product lottery”**
>
> “Ironically, conducting the worthwhile exercise of plotting your own IT world map can be challenged by traditional IT managers as ‘academic.’ This can be especially amusing in Germany where IT management is littered with PhDs (not necessarily in any technical major) who carry the title ‘Dr.’ as part of their legal name. If pragmatic means ‘haphazard,’ I am happy to be in the ‘academic’ camp: I am paid to think and plan, not to play product lottery.”
>
> — Gregor Hohpe, _The Software Architect Elevator_

## **What They Mean**

The complaint has several possible meanings, and the speaker rarely distinguishes between them:

1. “This theory is incomplete and cannot be applied yet.” Sometimes true. Many theories are in development. But incomplete does not mean useless. Every theory that eventually became indispensable was incomplete when someone first dismissed it.
2. “I cannot see how to apply this theory to my current problem.” Almost always true, and almost always irrelevant. The inability to see an application is a statement about the observer’s position, not about the theory’s value.
3. “This theory does not help me do what I am currently paid to do.” Always true, and the most honest version. It is also the version that reveals the incentive structure driving the complaint.

## **The Incentive Behind the Complaint**

Gregor Hohpe, who has spent a career riding the elevator between strategy and implementation, puts it directly: “Looking at things from a higher level doesn’t at all mean there’s less depth.” The assumption that abstraction equals impracticality is itself a failure of abstraction. The person looking up from the engine room and seeing the penthouse assumes the penthouse is empty. It is not. It is where the decisions are made that determine which engines get built.

Consider what “practical” means to different people.

For someone whose system rewards closing tickets, “practical” means: can I use this to close my next ticket? If not, it is impractical.

For someone whose purpose is to build a system that makes the next generation of tickets unnecessary, “practical” means: does this help me understand the domain at a deeper level? If so, it is the most practical thing available.

For someone whose purpose is to design an institution that produces different outcomes than the current one, “practical” means: does this help me see the structural assumptions that the current system rests on? If so, it is indispensable.

The word “practical” is not objective. It is a function of the speaker’s purpose, which is a function of their incentives, which is a function of the structure they operate within. The complaint “it’s not practical” is never about the theory. It is always about the layer the system has placed the speaker in.

> **Wide does not mean vague**
>
> Hohpe maps architecture along two independent axes: scope (narrow to wide) and level of abstraction (concrete to conceptual). The assumption that “bigger picture = more abstract = less real” is wrong. Cloud infrastructure scripts are wide-scope AND deeply concrete. Design patterns are narrow-scope AND highly conceptual. You can think about the entire system in precise, testable terms. You can think about a single function in purely theoretical terms. The complaint “that’s too academic” conflates scope with abstraction. The assumption is that because the work addresses the whole system, it must be vague. It is not. It is wide AND concrete. But nothing in the speaker’s position requires seeing both axes.
>
> — Gregor Hohpe, “The Architect’s Path”, architectelevator.com

## **The Ready-Made Meal Test**

Anyone who wants a ready-made meal does not think cooking is practical. They are not wrong. Within their constraints (time, skill, interest), cooking is impractical. The meal is what they need, not the capability to produce meals.

But the person who can cook is not dependent on the meal provider. They can adapt when ingredients change, when supply chains break, when the restaurant closes. Their capability is structural. The system that delivers ready-made meals produces a transactional dependency.

The same applies to theory and practice. The system that delivers ready-made solutions does not require engaging with the structure that produced them. It does not require contributing to the capability behind the solution. When the context changes and the old solution no longer works, the system offers no fallback. It produces dependency on the next ready-made meal.

The person who engaged with the theory, even when it was “impractical,” has structural capability. They can adapt. They can see when the model no longer matches reality. They can design a new solution because they understand the principles that generated the old one.

## **The Copying Problem**

There is a revealing analogy in software development. A developer can reuse someone else’s code. The code works. The task is done. The ticket is closed. But the developer has not gained the capability to produce that code. The system counted the output, not the understanding.

The person who wrote the original code contributed creation: understanding the problem, designing the solution, encoding it in a way that works. The person who reused it contributed execution: recognising that it solved the problem and applying it. Both contributions are necessary, but the system that values them identically has stopped distinguishing between creation and application.

The system that rewards both equally, because both closed a ticket, is incentivising replication over origination. Over time, the original contributors either leave (because they are undervalued), stop contributing (because there is no incentive), or are simply outnumbered by those the system selected for: efficient metric completion.

This is how organisations lose the capability to innovate while becoming more efficient at execution. Those who build theory leave. Those the system selected for ticket-closing remain. The system continues to measure tickets.

## **What Practice Actually Means**

Practice, in its deepest sense, is not “applying a recipe.” It is testing a theory against reality and updating both.

A doctor practices medicine. This does not mean they follow a manual. It means they hold a theoretical model of how the body works, observe a patient, update the model, and act. When the model is wrong, they do not discard medicine. They update the model. The practice is the ongoing dialogue between theory and reality.

A software architect practices architecture. This does not mean they apply patterns from a book. It means they hold a model of how the system should behave, observe how it actually behaves, update the model, and redesign. The practice is the structural reasoning, not the implementation.

The complaint “it’s just theory” conflates practice with execution. In this framing, practice means doing the thing. In a complex domain, practice means understanding why the thing works, and knowing when to do a different thing.

> **Framework vs model**
>
> “Cynefin is a sense-making framework; it’s not a model, and that’s actually quite an important distinction. A model seeks to represent reality; a framework is a way of looking at reality.” — Dave Snowden
>
> Practice in a complex domain is not applying a model (a fixed representation of how things work). It is using a framework (a way of looking) to sense what is happening, and responding accordingly. The person who demands a model is asking for a map of territory that has not been surveyed. The practitioner who uses a framework is navigating without a map, which is the only honest way to navigate territory that keeps changing.

## **The Civilisation Test**

Every structure we call civilised, law, education, healthcare, governance, was once a theory someone called impractical. Every institution that protects the weak from the strong was once an abstract principle that a pragmatist dismissed.

Most people benefit from these structures without engaging with the mechanisms that produce them. That is the system’s design, not a personal choice. Specialisation is itself a structural achievement: the surgeon should not grow their own food; the farmer should not perform their own surgery. The problem is not that most people operate within structures others built. The problem is when the system produces only operators and no one is left to build.

The system also depends on a small number of people who create the structures that everyone else operates within. And those people, almost without exception, started with a theory that someone called impractical.

I have consumed more structures than I have built. Everyone has. The question is not whether you are a builder or an operator. It is whether the system notices the difference and invests accordingly.

The question is not whether theory is practical. The question is: practical for whom, and at what layer?

#### Discussion about this post

CommentsRestacks

No posts

### Ready for more?
