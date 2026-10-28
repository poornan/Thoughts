# Observation: AI Adoption and the Limits of Courses and Targets

### Vendors selling AI courses are increasingly present in shopping malls and at MRT stations. The premise of such courses, that a person must be formally taught to use AI, warrants scrutiny.

[Anan](https://substack.com/@anan12)Jun 30, 2026

AI is not a specialised instrument, such as a chef’s knife, whose correct use must be imparted by a trained practitioner. It is closer to electricity: you plug in whatever device you need, and no one is taught how to use the electricity itself. It operates on top of the general literacy and reasoning that primary education has already installed, and is reached through ordinary language and existing judgement. The proposition that a person must be formally taught to use it is therefore questionable.

The history of open source software supports this. Projects such as Linux set no central adoption target and provided no formal instruction on use or contribution for many years. Programmers who found them interesting modified them to solve their own problems, then contributed their changes back. Capability and adoption emerged through self-directed, problem-driven engagement, not through taught courses.

Self-directed engagement does not mean the bar is low. The capability that makes serious contribution possible is mechanical sympathy: an understanding of how the machine works, paired with an understanding of the domain in which the programming is applied. The strongest contributors operate close to that level. A programmer who cannot read source and understand the system cannot contribute value at that level; knowing syntax alone is not programming \[10]. That incapacity is itself a constraint. It forces dependence on an intermediary, a document or another person, whose account may not match the running system and may already be obsolete.

AI changes what the binding constraint is. Where the intermediary was previously a fixed and possibly stale translation, AI reads the actual system and explains it at the level of the user’s own knowledge and experience. It does not reinstate the obsolete-proxy problem, because it translates the live system rather than a frozen account of it. The translation layer therefore stops being the bottleneck. What remains binding is scientific curiosity and judgement, the capacities that cannot be outsourced to any translator.

## Diffuse value, capture, and sustainability

The structure that makes AI capability emerge from use rather than instruction also governs how its value should be measured and sustained. Both AI capability and open source are diffuse, demand-side goods: their worth is spread across all who use them rather than concentrated in any individual, which is why neither is well served by individual-level instruction or individual-level metrics.

Singapore engaged a version of this tension early. At the 2015 FOSSASIA Summit in Singapore \[1], the Minister-in-charge of the Smart Nation Initiative, himself a maker, backed open source but voiced one reservation: looking around the room, he said he needed at least some contributors to become millionaires from their open source work, because if they did the hard work while others took the profit, the movement would not be sustainable \[2]. The worry is sound. The framing, that the answer is individual wealth, is not.

The value of open source is overwhelmingly diffuse, and it does not sit where individual wealth would. A Harvard Business School study placed the cost of writing widely-used open source once at about 4.15 billion US dollars, but its demand-side value, what every firm that uses it would together pay to rebuild it for itself if it vanished, at about 8.8 trillion US dollars \[3]. The gap of roughly two thousand to one is not a markup but the effect of reuse: code written once is relied on by millions of firms. Measured another way, firms already spend about 3.4 trillion US dollars a year on software, and replacing open source would lift that to roughly 12.2 trillion, about 3.5 times current spending \[3]. That whole gap is value no contributor captures. It flows outward as lower costs to every firm and, in turn, every household: strip out Linux and the base cost reappears in the price of phones, routers, and cloud services. The same study found 96 per cent of that demand-side value created by 5 per cent of developers \[3], which locates both the leverage and the fragility in a small number of maintainers, consistent with the Paretian distribution of contribution \[11].

The same principle runs through payment systems. Singapore’s instant-payment rail, PayNow, is free to use for individuals, and digital-payment adoption now stands at about 92 per cent, the highest in the region \[7]. Sri Lanka, by contrast, has long charged fees on interbank transfers, and adoption has lagged, though its central bank is now capping and removing those fees precisely to lift it \[8]. Charging at the base layer suppresses the very adoption that creates the value; keeping the base free pushes capture to higher orders, where the whole economy rather than the single transaction is where value accrues. Note too that this is not free to provide: Singapore’s banks and regulator carry the rail as public infrastructure and recoup it above the base, which is the open source pattern exactly. The lesson transfers. If open source captured value at the point of creation or use, it would put a toll on every reuse, and the reusability, common protocols, and shared security models that generate its value would begin to fail, fragmenting the world into isolated, incompatible islands. That is the direction much of the technology industry is already taking. A free base layer is what lets software connect rather than divide.

This is why the burden cannot rest on individuals. Capturing and redistributing value is properly a collective function, of the state and the community, not a duty placed on contributors. But the mechanism has to be deliberate, because the value is consumer surplus, a cost that never appears, and a cost that never appears cannot be taxed. Singapore’s model lets private enterprise capture value and then redistributes what it taxes; the commons needs the stronger move of appropriating public funds for value that was never privately captured at all. Germany’s Sovereign Tech Fund, which pays to maintain critical open source infrastructure from public money, is that move made concrete \[4], as are the foundations and corporate consortia that pool funds for the same end.

The level of support required is also lower than the millionaire framing implies, because the problem is a floor and not a ceiling. Open source contribution is largely intrinsically motivated. Linus Torvalds is not a billionaire, yet is, by all accounts, satisfied, and most contributors are the same. Burnout among critical maintainers does not come from failing to get rich; it comes from doing essential, unpaid work while basic needs go unmet. The research on income and well-being points the same way: the returns to income diminish steeply, so the largest gains come from relieving financial strain at the low end, not from wealth at the top \[5]\[6], and extrinsic reward can even crowd out the intrinsic motivation that sustains the work. The Zig Software Foundation institutionalises exactly this. It pays the language’s creator, Andrew Kelley, a salary of 154,000 US dollars, set by the board at the median for a senior software engineer in New York City where the foundation was formed, not the fortune a comparable commercial founder would extract. It runs on one employee and about five paid contractors, routes the vast majority of its roughly 670,000 dollar annual income straight to that work, and draws on a spread of individual and corporate donors so that no single sponsor can dictate the language’s direction \[9]. The anti-capture rule is stated plainly: the foundation could refuse any one sponsor’s demand and still survive. Securing a living for the critical few is therefore both sufficient and far cheaper than manufacturing millionaires, and it does not risk privatising the commons.

The dilemma then dissolves. Capture must happen, as the minister said, but it need not fall on individuals, need not take the form of millionaires, and need only secure a floor rather than a fortune. It can be the deliberate public and communal funding of the critical few who carry the commons. The same logic disciplines the metrics now proposed for AI. A headcount of practitioners, or a tally of completed courses, counts what is legible and individual \[11], while the value, like the value of open source, is diffuse, demand-side, and located in use across the whole economy.

## Conclusion

It follows that the requirement for mass AI adoption is not a course but an environment in which to operate. Embedded workplace tools, of which Microsoft 365 Copilot is one example, provide that environment: the user applies AI to real work, the tool explains the system as the work demands, and curiosity and judgement do the rest. This is the same self-directed, problem-driven path by which open source capability formed, now open to the non-programmer because the translation constraint has been lifted, with AI augmenting rather than replacing the discoverer \[10].

The corresponding measure of success is diffuse capability in use. Where public money is spent, it belongs on the operating environment and on sustained access to it, not on counting credentials, in the same way that sustaining open source means funding the commons rather than rewarding individuals.

## References

\[1] [FOSSASIA Summit 2015](https://2015.fossasia.org/), “The Smart City”, Singapore, 13 to 15 March 2015. Event and keynote details, including the speaker profile of Dr Vivian Balakrishnan, Minister-in-charge of the Smart Nation Initiative, described as a maker. See also the [event wrap-up](https://blog.fossasia.org/fossasia-2015-singapore-wrap/).

\[2] Wallace Tan (uploader), “[FOSSASIA - Dr. Vivian Balakrishnan](https://youtu.be/_bDjsYgZMFo)“, candid questions and answers session, FOSSASIA Summit 2015, 13 March 2015. YouTube. The reservation about millionaires and sustainability is at approximately 6:18 to 8:03.

\[3] Hoffmann, M., Nagle, F., and Zhou, Y. (2024), “[The Value of Open Source Software](https://www.hbs.edu/ris/Publication%20Files/24-038_51f8444f-502c-4139-8bf2-56eb4b65c58a.pdf)“, Harvard Business School Working Paper 24-038. Supply-side value about 4.15 billion US dollars; demand-side value about 8.8 trillion US dollars; firms would spend about 3.5 times more on software without open source; 96 per cent of demand-side value created by 5 per cent of developers.

\[4] Sovereign Tech Agency, “[Sovereign Tech Fund](https://www.sovereign.tech/)“. Established October 2022, commissioned by the German Federal Ministry for Economic Affairs and Climate Action; pays from public funds for the maintenance and security of critical open source infrastructure, addressing the free-rider problem in the digital commons.

\[5] Kahneman, D., and Deaton, A. (2010), “High income improves evaluation of life but not emotional well-being”, Proceedings of the National Academy of Sciences, 107(38), 16489 to 16493.

\[6] Killingsworth, M. A., Kahneman, D., and Mellers, B. (2023), “[Income and emotional well-being: A conflict resolved](https://www.pnas.org/doi/10.1073/pnas.2208661120)“, Proceedings of the National Academy of Sciences, 120(10).

\[7] Singapore digital payments: PwC Singapore and Singapore FinTech Association, “[Payments’ State of Play 2026](https://www.pwc.com/sg/en/publications/payments-state-of-play.html)“ (digital-payment adoption about 92 per cent in 2025). PayNow is free of charge for retail users, regulated by the Monetary Authority of Singapore and operated by the Association of Banks in Singapore on the FAST rail.

\[8] Sri Lanka interbank transfers and fee reform: LankaPay [Common Electronic Fund Transfer Switch (CEFTS) fee schedule](https://www.lankapay.net/en/for-you/real-time-payments-cefts), and Central Bank of Sri Lanka, Payment and Settlement Systems Circular No. 02 of 2025, [capping fees and transaction limits](https://www.themorning.lk/articles/iPdTPeZKX9eJ9QWPQ8Wa) to promote digital-payment adoption.

\[9] Zig Software Foundation. Andrew Kelley interview, “[Zig 2026](https://www.youtube.com/watch?v=iqddnwKF8HQ)“ (JetBrains, 27 May 2026), verified against the video transcript: foundation annual income about 670,000 US dollars (21:47); Kelley’s salary 154,000 US dollars, set at the median senior-software-engineer salary in New York City where the nonprofit was formed (23:11 to 23:40); one employee and about five paid full-time contractors, with the vast majority of income going directly to the work (27:04 to 27:28); a spread of individual and corporate donors, with the stated principle that the foundation could refuse any single sponsor’s demand and survive (22:10 to 22:44). See also the [Zig Software Foundation pages](https://ziglang.org/zsf/).

## Author’s related writing

These are the author’s own earlier pieces, part of the same line of argument as this note.

\[10] Anan (2025), “[Navigating the Changing Landscape of Work: Outcome-Based Contributions and Irreplaceable Value](https://anan12.substack.com/p/navigating-the-changing-landscape)“, 18 March 2025. On discovery over instruction, outcome-based contribution, and that knowing syntax alone is not programming.

\[11] Anan (2025), “[Performance: Team and Individual: Remuneration vs. Performance](https://anan12.substack.com/p/performance-team-and-individual)“, 2 February 2025. On the Paretian distribution of contribution and the limits of legible proxy metrics for diffuse value such as good design.

#### Discussion about this post

CommentsRestacks[Anan](https://anan12.substack.com/profile/136489052-anan)[Jul 1](/broken/pages/8b4abcf18a70cb8957e2c1a456f2ea884a038cbd)

Luca Dellanna: Group training is good for introducing standards, but coaching is necessary for installing them into behavior.

ReplyShare[1 reply by Anan](/broken/pages/8b4abcf18a70cb8957e2c1a456f2ea884a038cbd)[1 more comment...](/broken/pages/0baffac6d64e5d5ad6390125e3437bce4fa47cc1)

No posts

### Ready for more?
