# Pair programming and mob programming are antidotes for many issues and factors that influence programming.

### Pair programming, Mob programming, TDD

[Anan](https://substack.com/@anan12)Feb 23, 2025

Let's say you get a requirement to write a program that prints all English alphabet letters on a new line.

One programmer writes 26 println statements. Another writes an array and iterates through it with one println statement.

People might debate whether the first approach serves the purpose, "task done." Some won't stop; they will also blame the second approach for being over-engineered. Interestingly, most managers and leaders will agree with them.

If you find the second solution better, that's good, but persuading others to work to this level requires extra knowledge, effort, and grit, especially the motivation to do the right thing. Both codes do the work. The second is more production-ready. There is a difference between throwaway trials, PoCs, and production-ready code.

Second solution: more importantly, implement a non-functional requirement. That is, separate context that will change from how we implement it (essential vs. accidental complexity).

Here are possible changes that could come next.

1. Print all on the same line.
2. Change the letters' case.
3. Add other alphabets like alpha and beta, too.

Now, see which is easier to change and how many changes you need to make?

This post to discuss about antidotes. How to avoid this arising at in fist place rather argue later which is better. (Problem solving vs problem dissolving)

As Extreme Programming(XP) puts it each practice is complimentary to each other's pros and cons.

Pair Programming, allows early discussion even before you write something. So higher chance getting additional perspective on non functionalities. Forces to a ‘better than task done’. It also tied to experience of programmers involved, usually we pair to different expertise level and often change to mix them. So that average improves. Additionally there will be an expert programmer, who practice TDD. Which solves even important step, it takes through the evolution, in multiple iterations.

TDD strats like this, instead of writing all 26 at once. You go write test that expect ‘A’ printed. Then implement it to print it. Look at the design at this stage itself we will start to think about how to separate handling IO, that makes it easy to test. Then you'll continue to do for ‘B’, like this, when gradually evolve you see a pattern, so that you won't write another print statement. You'll take time to refactor code to get a better design, that can easily accept next change with the confidence of have tests for already written functions.

Now people will argue this what happens usually, no one writes 26 print statements. For simplicity sake I shared this printing Alphabet example. In practice things won't be this clear, and often happens.

Let me share a real example. In a data exchange system, XML data was received and stored in a database. There's an XSD; from that, JAXB entities were generated. These entities were used to unmarshal XML to object graphs. Let's call this function "xmlhandler". Like a print alphabet function, it could be written once and used multiple times. What happened in practice is that we ended up with hundreds of "xmlhandlers" instead of one. When I joined the team, I was shocked to see that. There were many other design issues. We refactored them. That's another story—refactoring a system that doesn't have automated testing. But these arguments are the barriers.

Arguments like these come because you have to act with those who are consuming them.

1. This is how we have been doing.
2. This is a massive change; we can't do it (postpone indefinitely).
3. Doesn't want to write tests because they are not used to it; thus, it's a "psychological inertia". A simple unit test usually provides much better coverage than manual testing at unmatched speed.
4. "Passing the buck" or "deferring responsibility"; We have other tasks. (That's fine, but in what capacity are you going to do the task? Why do people have a lot of operational tasks? It's because we have the aforementioned code quality and never want to improve it; then the effort for operational tasks will never decrease, or we will never find time to improve.)
5. We don't know. We never touched that code for years. (Why that's a problem? Do you do programming? Are you a software developer? )

💡

Psychological inertia is the tendency to keep doing things the same way, even when it might be better to change.

💡

This behavior is often called "passing the buck" or "deferring responsibility"; it describes the act of avoiding completing a task by claiming another one is more urgent or needs immediate attention, essentially shifting the blame or responsibility to something else.

Why this situation exists? Because knowledge, responsibility and authority divided. (Another antidot - autonomy)

There would be an accountable person, but that person should know how to delegate tasks. This often happens when technical people become managers and are isolated from hands-on technical work, but they do not realize they are not technical managers. So, a manager might think that to get multiple XML files processed quickly, it should be parallelized, thus assigning multiple developers to handle multiple XML files. Second, it's easier and more natural to lock in the current instance's problem context than to think long-term and about the full software life cycle.

That's why mob programming or pair programming are antidotes. Even if management divides and assigns tasks, they can still be merged.

💡

Conway's Law is a theory that describes the relationship between an organization's communication structure and the systems it designs. It's often used in software architecture, but it can be applied to many technical fields.

> **How it works**
>
> * The way an organization's members communicate and collaborate will shape the design of its systems and projects.
> * If a company has a fragmented communication style, its products and systems are likely to reflect that fragmentation.
> * The architecture of these products will reflect the communication structure of the teams that are part of that process.
>
> **History**
>
> Computer scientist and programmer Melvin Conway introduced the idea in 1967. The theory gained popularity when it was cited by Fred Brooks in the book **The Mythical Man Month**

Let's now see the economic implications. Results are counterintuitive to our traditional wisdom on decision-making when developing software in a rapidly changing, complex world.

The decision to write hundreds of handlers ten years ago resulted in significant development and maintenance costs. This design created technical debt, leading to lost opportunities and other unintended consequences. For example, the generated JAXB entities were treated as source code instead of generated code. Three to five years ago, a decision was made to slim down the XSD structure, but the entities and DTOs were not updated. Now, nobody wants to touch the code due to risk aversion. Any XSD changes are rejected because of the need for manual entity editing or synchronization. This results in further lost opportunities. The software is being treated like hardware; it is no longer easy to change. For simple calculations, we need a four- to five-member team to maintain this software instead of one or fewer (using modern integration methods). That's roughly $500,000 to $600,000 annually instead of approximately $100,000. This is about 5–30% of the whole business function, equivalent to $1.6–10 million in annual operational losses from similar decisions across the overall business.

What we are trying to address is the negative consequence of the division of labor.

> 💡
>
> The division of labor, while offering numerous benefits, also presents several concerns, particularly regarding responsibility and authority. Here's a breakdown of those concerns:
>
> * Concerns Related to Division of Labor:
>   * Fragmentation of Responsibility:
>     * When tasks are highly specialized, it can be difficult to pinpoint who is responsible when something goes wrong. This can lead to a diffusion of accountability.
>     * "That's not my job" syndrome: Workers may feel disconnected from the overall outcome and focus solely on their narrow task, leading to a lack of ownership.
>   * Coordination Challenges:
>     * As tasks become more specialized, coordinating the efforts of different individuals or departments becomes more complex.
>     * This can lead to communication breakdowns, delays, and inefficiencies.
>   * Loss of Holistic View:
>     * Workers may lose sight of the big picture, focusing only on their specific task. This can hinder innovation and problem-solving.
>     * Reduced feeling of contribution to the overall goal of a company.
>   * Authority Division Issues:
>     * Clarity of authority: It is essential that with the division of labor, there is a very clear division of authority. When this is not present, it can cause conflict between workers, and managers.
>     * Overlapping authority: When more than one person has authority over the same task, this can cause confusion, and conflict.
>     * Lack of authority: When a person has responsibility for a task, but does not have the authority to complete the task, this causes frustration, and inefficiency.
> *   Key Considerations:
>
>     * Clear Communication: Effective communication is crucial for mitigating the challenges of the division of labor.
>     * Defined Roles and Responsibilities: Clearly defining roles and responsibilities can help prevent confusion and ensure accountability.
>     * Effective Coordination Mechanisms: Implementing mechanisms for coordinating the efforts of different individuals and departments is essential.
>     * Empowerment: Giving workers a sense of ownership and empowerment can help to address the issue of fragmented responsibility.
>
>     In essence, while the division of labor can increase efficiency and productivity, it requires careful planning and management to avoid potential pitfalls related to responsibility and authority.

> 💡
>
> Pair programming and mob programming offer interesting approaches to mitigating some of the challenges associated with the division of labor, particularly in software development.
>
> Here's how:
>
> * Pair Programming:
>   * Shared Responsibility:
>     * In pair programming, two developers work together at a single workstation. This inherent collaboration fosters a sense of shared responsibility for the code being produced.
>     * The "driver" and "navigator" roles ensure that both developers are actively engaged, contributing to and understanding the work. This reduces the "that's not my job" mentality.
>   * Enhanced Communication and Coordination:
>     * Constant communication between the pair facilitates real-time coordination and knowledge sharing.
>     * This helps to prevent communication breakdowns and ensures that both developers are aligned on the goals and implementation details.
>   * Knowledge Sharing and Holistic View:
>     * Pair programming promotes knowledge sharing, as developers learn from each other's expertise.
>     * This collaborative environment encourages a broader understanding of the codebase and the overall project, reducing the risk of a fragmented view.
> * Mob Programming:
>   * Collective Ownership:
>     * Mob programming extends the concept of pair programming to an entire team. Everyone works together at a single workstation, fostering a strong sense of collective ownership.
>     * This eliminates the fragmentation of responsibility, as the entire team is accountable for the work.
>   * Seamless Coordination:
>     * With the entire team working together, coordination becomes seamless. Real-time communication and collaboration ensure that everyone is on the same page.
>   * Shared Understanding:
>     * Mob programming maximizes knowledge sharing, as everyone participates in every aspect of the work.
>     * This creates a shared understanding of the project, reducing the risk of silos and promoting a holistic view.
>   * Authority and responsibility:
>     * Because the entire team is working on the same task, authority and responsibility are shared by the whole team. This removes the problem of overlapping authority, and lack of authority.
> * In summary:
>   * Both pair programming and mob programming emphasize collaboration, communication, and shared responsibility, which directly address the concerns related to the division of labor.
>   * They promote a holistic view of the work, enhance coordination, and foster a sense of collective ownership.These practices are particularly valuable in complex software development projects where effective communication and collaboration are essential.

#### Discussion about this post

CommentsRestacks

No posts

### Ready for more?
