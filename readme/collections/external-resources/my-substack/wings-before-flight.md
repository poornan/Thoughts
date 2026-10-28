# Wings Before Flight

### Structure precedes behaviour. Always.

[Anan](https://substack.com/@anan12)Apr 02, 2026

_This is part 1 of a four-part series decomposing_ [_It’s a Theory: Complains_](https://anan12.substack.com/p/its-a-theory-complains)_._

***

A bird did not develop wings in order to fly. Yet, that is the story we tell because we see the finished product and reverse-engineer the purpose. But evolution does not work with purpose. It works with what is available.

> **The blind watchmaker**
>
> As Dawkins argues in _The Selfish Gene_ (1976) and _The Blind Watchmaker_ (1986), evolution has no foresight. It does not design for a purpose. It builds from whatever structures already exist, and the structures that happen to be useful survive. The “design” is visible only in hindsight.

Feathers evolved for insulation. Forelimbs evolved for balance while running. Over millions of years, the structures that served one function were repurposed for another. Biologists call this exaptation: a trait that evolved for one purpose being co-opted for a different one. Flight was not the goal. Flight was what became possible once the structures were in place.

This distinction matters far beyond biology.

## **The “Theory” and “Academic” Complaint**

In every workplace, in every institution, there is a moment when someone says: “That’s just theory. It’s not practical.”

What they mean is: “I cannot see how to turn this into something I can use right now.” And they are often right. They cannot see it. Not because the theory is impractical, but because the structure required to make it practical does not yet exist, or they are not positioned to see it.

Set theory did not arrive as a finished product ready for computing. It evolved across decades, through contributions from Cantor, Zermelo, Fraenkel, and others, none of whom could have imagined a semiconductor. But without set theory, there is no Boolean algebra. Without Boolean algebra, there is no logic gate. Without logic gates, there is no processor. The “impractical theory” became the platform for every practical device in modern life.

The person who said “set theory is impractical” in 1880 was not wrong about their own context. They were wrong about the arc. The structure was being built. The behaviour it would enable was not yet visible. That is not a failure of theory. It is the nature of how capability emerges.

## **Exaptation in Organisations**

The same pattern operates in organisations, but we rarely recognise it because we are inside the system.

A developer builds a test automation framework because the team needs regression testing. That is the immediate purpose, the “insulation” function. Years later, that same framework becomes the foundation for a continuous integration pipeline that the organisation could not have planned for. The structure was exapted for a purpose the original builder could not have foreseen.

And then it happens again. The same test suite, now part of CI, becomes the safety net for something even further from the original intent: AI agents spinning up parallel implementations in different languages and frameworks, running the tests against each, and surfacing which approach performs best. Exaptation upon exaptation. But this second leap only works if the tests were written to describe behaviour, not implementation. A test that asserts “button X triggers function Y” breaks the moment the implementation changes. A test that asserts “when a user submits an order, the system confirms it” holds regardless of which language, framework, or agent built it. The structure that enables exaptation is not the test framework. It is the domain language encoded in the tests. The framework was exapted for a purpose that did not exist when it was written, but only because the original builder wrote tests that spoke the domain, not the implementation.

A governance framework bridging two project methodologies is created to solve a compliance problem. That is the immediate function. Later, it becomes the template for how the entire organisation adopts a new delivery model. The structure was built for one reason and used for another.

The person who says “that governance framework is just theory” is looking at feathers and cannot see flight. They are not wrong that the feathers are not currently flying. They are wrong that the feathers have no purpose.

## **The Layer Problem**

The “it’s just theory” complaint is a layer problem. The person making the complaint is operating within a layer where “practical” means “solves my current task.” They are not wrong within that layer. They are missing the layer above, where the structure being built will enable capabilities that do not yet exist.

Consider the Turing machine. For Alan Turing in 1936, building a theoretical model of computation was a practical application of mathematical logic that had evolved over sixty years. For everyone else at the time, it was impractical: a thought experiment with no obvious use. Today, every device in your pocket runs on the architecture that Turing’s “impractical theory” made possible.

Was it a theory? Yes. Was it impractical? Only to the observer standing in the wrong layer.

> **Rational beings, irrational outcomes**
>
> “There is nothing wrong with people’s brainpower; there is something very wrong with people’s perception of reality.” — Eliyahu Goldratt, _The Choice_ (2008)
>
> “Even when people do things that seem stupid, they have a reason for that behavior.” — Third axiom of the Theory of Constraints
>
> People who dismiss theory as impractical are not being irrational. They are being perfectly rational within a perception of reality that does not include the layer above. The irrationality is not in the person. It is in the gap between the layer they can see and the layer where the structure’s purpose lives.

## **The Incentive Structure**

This is where the structural diagnosis becomes uncomfortable. The reason most people dismiss theory as impractical is structural, not personal. It is an incentive problem.

If you are paid to lay bricks, the question “should there be a wall here?” is not your question. It is above your pay grade, literally. The system incentivises brick-laying, not wall-questioning. The person who stops laying bricks to ask about the wall is penalised, not rewarded. Their output drops. Their metrics suffer. Their performance review reflects “did not meet delivery targets.”

The system selects for execution and penalises structural questioning. Then it asks why no one questions the structure.

> **Goldratt’s warning**
>
> “Tell me how you measure me, and I will tell you how I will behave. If you measure me in an illogical way, do not complain about illogical behaviour.” — Eliyahu Goldratt, _The Haystack Syndrome_ (1990)
>
> People are not irrational. If their behaviour seems irrational, examine the metrics and policies they operate under. You will find they are behaving perfectly rationally given those constraints. The fault lies with the measurement system, not with the people.

If your incentive is to close tickets, learning set theory is impractical. If your incentive is to build the platform that makes the next generation of tickets unnecessary, set theory is the most practical thing you could study. The difference is not in the theory. It is in what the system rewards.

## **Who Builds Wings?**

The people who build structures that later get exapted for purposes no one foresaw are rarely rewarded at the time. They are building feathers in a world that does not yet know about flight. Their contribution is invisible until the behaviour it enables becomes visible, and by then, the credit often goes to whoever was standing nearby when the bird took off.

This is the invisible contribution problem. The crises they eliminated never happened. The platforms they built were attributed to whoever deployed them. The theory they developed was called impractical until it became indispensable, at which point it was called obvious.

The examination system does not select for these people. The incentive structure does not reward them. The organisational hierarchy does not promote them. And yet, without them, there are no wings. There is no flight. There is only a world of people building walls with increasing efficiency, in a building that no one designed.

## **Not All Feathers Fly**

This essay argues that theory builds structure, and structure enables behaviour that was not foreseeable. But honesty requires the counter-case: not all structures get exapted. Not all feathers enable flight. Some theories remain impractical because the context never arrives where they become useful. Some structures are built for a purpose that never materialises, and the cost of building them was real.

I have built structures I was certain would be exapted. Some were. Some were not. The difference is not always visible from the inside. The person building the structure and the person dismissing it as impractical are both operating with incomplete information. The builder cannot prove future use. The dismisser cannot prove future uselessness. The honest position is not “theory always wins” but “we cannot know in advance which structures will be exapted, so the question is how much structural investment a society can afford, not whether it should invest at all.”

The system that invests nothing in structure gets no wings. The system that invests everything in structure gets no food. The question is the ratio, and that is a decision that should be argued through, not assumed.

## **The Question**

The next time someone says “it’s just theory,” ask yourself: are they diagnosing the theory, or revealing the layer they operate in?

And then ask the harder question: what structures are you building right now that will be exapted for purposes you cannot yet see? Because that is what the arc of progress looks like from the inside. Not a straight line from theory to practice, but a long accumulation of structures that were built for one reason and used for another.

Wings before flight. Always.

#### Discussion about this post

CommentsRestacks

No posts

### Ready for more?
