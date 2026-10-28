# Critique: "Trying to be better at agile will not make any difference to system quality"

[Anan](https://substack.com/@anan12)Jul 14, 2026

**Source:** LinkedIn post, eventmodeling account (viewed via browser this session) **Author / Speaker:** Adam Dymitruk, author of Event Modeling, event-sourcing practitioner **Context:** Public thought-leadership post, with an attached Oren Harari candle image and a comment exchange with Gunnar Wielert. Assessed as a confidently-asserted public claim.

***

## Clarity assessment

The claim is not clear, and its persuasive force depends on that lack of clarity. Three terms carry the argument and none is defined: “agile”, “quality”, and “continuous”. The word “agile” is used to mean both the degraded ceremonial practice found in industry and the defined body of values, principles, and practice, and the argument moves between the two senses without notice. “Continuous” is imported from the attached Harari quotation, where it denotes the vice of polishing a doomed artifact, and is allowed to sit beside the agile sense of “continuous”, where it denotes the virtue of a fast feedback loop. The two senses are opposite in valence. The main risk is that a reader accepts a global verdict on a defined discipline that has in fact been drawn from an undefined aggregate. The single most important correction is to fix the referent of “agile” before any conclusion is drawn from it.

***

## The claim

Paraphrased, with load-bearing phrases quoted. The author states that improving at agile “will not make any significant difference in the quality of your systems”, that effort should move instead to system design, and that raising agile knowledge is analogous to refining how a shovel is held whilst digging on the wrong side of the street. The record of system quality after roughly twenty-five years of agile is described as “abysmal”, the root cause being that the field “ignored design” and attended only to execution. In reply to a comment, the author adds that the ability to find a wrong idea through design without executing is “proof of agile ignoring design”, and that requiring execution first indicates one is “not competent at design”. The Harari line, “the electric light did not come from the continuous improvement of candles”, is used as the argument’s prop.

***

## 1. Devil’s Advocate Flip

The inverse position is defensible and, on the evidence, stronger. Improving agile capability is frequently the fastest route to higher system quality, because the engineering practices bundled with disciplined agile, namely continuous integration, test-driven development, trunk-based development, and small releases, are the levers the DORA research identifies as raising delivery speed and stability together. Where quality is poor under an agile banner, the common cause is that the label was adopted as ceremony without these practices, not that the practices were tried and failed. On this reading the remedy is more engineering discipline, not less agility.

The claim holds only in the narrow case it does not name: organisations running agile as ceremony, that is, stand-ups, boards, and ticketing with no engineering or design discipline. For those organisations the instruction to attend to design is correct. The correct name for their failure is the absence of disciplined agile, not agile.

## 2. Steelman vs Teardown

**Steelman (as written).** Two decades of agile adoption have, in aggregate, over-invested in process ceremony and delivery cadence and under-invested in system design. Marginal effort spent becoming “more agile” in that ceremonial sense returns little quality improvement compared with effort spent on design. As a corrective to cargo-cult agile, the point has force.

**Teardown.** The argument breaks on equivocation. “Agile” denotes the ceremonial degradation where that is convenient and the whole discipline where that is convenient, and a defect belonging only to the degradation is then attributed to the defined discipline. The defined discipline names design in its ninth principle and, in its Extreme Programming form, is built on design practice. The global quality verdict is asserted with no metric and no counterfactual. The further claim, that execution yields no design knowledge, contradicts the empirical basis of the delivery research that measures quality in the first place.

**Steelman reconstruction (what the author should have written).** Quote-ready:

> Much of what passes for agile in industry is ceremony without engineering discipline: stand-ups, boards, and sprints, but little continuous integration, test-driven development, or deliberate design. Getting better at that ceremony will not improve system quality. What improves quality is the engineering and design practice that disciplined agile already prescribes, applied before and during execution. Invest there. Design enough up front to avoid building the wrong thing, and keep the feedback loop fast so that execution corrects the design that could not be settled on paper.

That version is defensible. It is not the version posted.

## 3. Skeptical Mentor

Questions to settle before acting on the claim.

1. Which practices would be dropped and which kept? If agile investment is to be cut, name whether continuous integration, test-driven development, code review, and small releases are among the casualties.
2. What is the quality baseline and target measure? Absent a metric, neither “abysmal” nor “design will fix it” can be substantiated.
3. Does the team currently design at all? If little, the fault may be the absence of agile engineering practice, not its presence.
4. What is the cost and risk of moving design wholly up front for this problem class? Where requirements are volatile, how is designing to the wrong assumption to be avoided?
5. How will a design be validated before build, and what is the plan when execution shows the design was wrong?
6. Does the author offer a competing method? Note the incentive and test the claim on its merits.
7. What does the team’s own delivery data show? Check change-failure rate and lead time before accepting a narrative of decline.

## 4. Cross-Examine

Each question is paired with what a vague answer would reveal.

1. **Which “agile” is meant: the Manifesto, a named framework such as Scrum or SAFe, Extreme Programming, or one organisation’s adoption?** A vague answer reveals the claim targets an undefined aggregate and therefore cannot be tested.
2. **By what measure is quality “abysmal”, and against what baseline?** A vague answer reveals no metric and no counterfactual, that is, an unfalsifiable assertion.
3. **Does “agile” include Extreme Programming; if so, how does a practice built on test-driven development, refactoring, and evolutionary design “ignore design”?** A vague answer reveals the claim depends on excluding the design-centric strand it nominally covers.
4. **How is Manifesto principle 9 consistent with “agile ignoring design”?** A vague answer reveals the claim contradicts the defining text.
5. **Which class of design error is detectable only before execution, and which only after?** A vague answer reveals the false premise that all relevant knowledge is available up front.
6. **What primary source establishes the Harari quotation used as the prop?** A vague answer reveals reliance on an unverifiable attribution.
7. **For two teams differing only in agile-engineering maturity, what do change-failure rate, lead time, and recovery time show?** A vague answer reveals the claim ignores the available empirical record.

## 5. Prediction Test



## 6. Assumption Audit

**Reasonable.**

* Many organisations adopted agile as execution cadence without engineering or design discipline, and shipped poor systems.
* Up-front design can catch structural errors cheaply.

**Questionable.**

* That system design and agile are opposed rather than complementary activities.
* That a single global quality verdict on “agile” is meaningful given the term’s breadth.

**Wrong.**

* That agile, as defined, ignores design. Contradicted by Manifesto principle 9 and Extreme Programming practice.
* That execution yields no design-relevant knowledge. Contradicted by the feedback basis of continuous delivery, test-driven development, and the DORA findings.
* That improving agile capability makes no significant difference to quality. Contradicted by the DORA finding that practice maturity correlates with quality outcomes.

***

## Rubric



***

## Bottom line

* **What the post tells the reader to do:** stop investing in agile capability, redirect effort to up-front system design, and treat any need to execute before knowing as design incompetence.
* **What the steelman actually supports:** reinstate the engineering and design practice that disciplined agile already prescribes; design enough up front to avoid building the wrong thing, whilst keeping the feedback loop fast so that execution corrects what could not be settled on paper; and measure quality with delivery data rather than asserting a decline.
* **Verdict:** partially-right-with-wrong-call-to-action. The kernel, that design-free execution is a real and common industry failure, is correct. The prescription, framed as agile versus design, is wrong, because in the version of agile with definite content the design is already inside the loop.

**One point conceded to the author:** the diagnosis of cargo-cult agile, process ceremony substituting for engineering and design, is accurate and worth stating plainly.

***

**Sources used for empirical grounding:**

* [Principles behind the Agile Manifesto](https://agilemanifesto.org/principles.html)
* [Accelerate / DORA State of DevOps, throughput and stability do not trade off](https://redmonk.com/rstephens/2024/11/26/dora2024/)
* [Kent Beck, “Design in TDD”, Tidy First? Substack](https://newsletter.kentbeck.com/p/design-in-tdd)
* [Dave Farley, weblog on agile principles and anti-patterns](https://www.davefarley.net/?tag=agile)

#### Discussion about this post

CommentsRestacks

No posts

### Ready for more?
