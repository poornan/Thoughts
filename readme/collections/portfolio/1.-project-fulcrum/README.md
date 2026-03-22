---
description: Regional Procurement
---

# 1. Project—Fulcrum

Singapore's Government Electronic Business (GeBIZ) was a pioneering procurement system for the internet era. However, technology and strategy have advanced through several generations since its inception. This evolution represents more than just a name change; it signifies a fundamental shift in how we achieve our goals.

Consider the evolution of communication: from a bird carrying mail, to a postman, to email and instant messaging, and now to AI assistants. In each step, the core purpose—delivering a message—remained the same, but the method and capabilities were completely transformed.

Similarly, the future of government procurement lies not in just another electronic system, but in a true "[platform](../../books/platform-revolution-how-networked-markets-are-transforming-the-economy-1-april-2016.md)." Guided by the principles of a "[Platform Strategy](../../books/platform-strategy-innovation-through-harmonization-architect-elevator-book-series-2-april-2024.md)," this approach moves beyond simple transactions. A modern platform connects and integrates disparate systems and stakeholders, fostering an open ecosystem that avoids vendor lock-in. It is designed to enable, not just to control.

With this vision, I am conceptualizing a next-generation procurement platform for governments and intergovernmental organizations like ASEAN. The objective is to create a unified system that allows different countries to collaborate, streamline their processes, and [realize collective benefits](digital-government-procurement-transforming-governance-for-700-million-lives.md).

---

## From Electronic to Digital: The Naming Convention as a Design Statement

Government Electronic Business (GeBIZ) is Singapore's one-stop government e-procurement portal. The "e" reflects the era it was born in: digitise the paper form, move the transaction online, connect buyer to supplier through a portal. That was the right architecture for its time. It succeeded.

The next stage is not more electronics. It is a different kind of system entirely. Government digital Business (GdBIZ) is the name this project uses for that shift because the distinction matters. "Electronic" means taking an existing process and putting it on a screen. "Digital" means rethinking what the process is.

Electronic procurement systems manage workflows. A tender is published, responses are collected, an award is made. The system tracks the lifecycle of each transaction. A digital procurement platform treats procurement as a domain model: suppliers, capabilities, contract performance, market signals, and policy objectives become first-class entities in the system, not just metadata attached to a transaction form. The difference is between a system that knows what happened and a platform that understands what it means.

---

## Economies of Scale to Economies of Speed

Systems like GeBIZ were built for Economies of Scale. Centralise procurement across all ministries and statutory boards. Aggregate demand. Reduce duplication. That logic works when the goal is cost reduction through volume.

The paradigm that follows is Economies of Speed. In a world where supply chains shift quarterly, where technology procurement cycles have compressed from years to months, and where policy responses need to be assembled rather than invented, the advantage goes to whoever can compose a procurement outcome fastest from available components. Speed here is not about rushing. It is about reducing the latency between identifying a need and fulfilling it, across every layer: discovery, matching, contracting, delivery, and feedback.

Scale optimises for the steady state. Speed optimises for the rate of change. Both are necessary. The architecture that serves one does not automatically serve the other.

---

## The Three-Phase Vision (GeBIZ: From Vision to Reality, 2006)

The original architects of GeBIZ documented a three-phase evolution in "GeBIZ: From Vision to Reality" (DSTA Horizons, 2006, Carol Lo, Chia Puay Long, Tey Soon Heng):

1. **Funded project**: government funds the initial development and infrastructure. MOF funded the first two years of operational costs.
2. **Self-sustaining portal**: the platform generates revenue through user fees to fund its own operations. GeBIZ transitioned to this model on 1 April 2004.
3. **IP commercialisation**: the platform's intellectual property is licensed to other governments. The document states: "The idea is to outsource the application maintenance of GeBIZ and grant the awarded vendor the licence to customise and sell GeBIZ overseas with the aim of lowering the cost of maintenance."

Phase 1 was completed. Phase 2 has been operational since 2004, with the portal continuing to recover costs through supplier subscription fees. Phase 3, as described in the document, envisioned licensing the GeBIZ IP to a commercial vendor to customise and sell to other governments. This did not happen. IDA International (2009-2016) exported broader e-government expertise to countries like Oman, Bhutan, Brunei, and Timor-Leste, but these were general e-government consultancy engagements, not the GeBIZ procurement platform specifically. When IDA was restructured into GovTech and IMDA in 2016, IDA International was dissolved. There is no publicly available evidence that the GeBIZ IP commercialisation vision from 2006 was carried forward.

The IP in question was never the source code. It was the institutional knowledge, the governance framework, and the domain expertise required to build and operate a national e-procurement system. That expertise remains valuable. No vehicle currently exists to export it.

Project Fulcrum does not revisit whether Phase 3 succeeded or failed. It starts from a different observation: the fundamental shift from electronic to digital enables architectural dimensions that were not available when Phase 3 was first conceived. A digital platform can be composed, configured, and extended in ways a monolithic electronic system cannot.

The objective of Project Fulcrum is to design and provide the platform and technical capabilities that would make IP commercialisation architecturally possible. Multi-tenancy, composability, cloud-native deployment, procurement as a domain model: these are the prerequisites. Rather than licensing a codebase or exporting consultancy, the GdBIZ model treats the platform as a composable system that different governments can configure for their own procurement domains while sharing a common infrastructure layer.

Fulcrum enables. Singapore decides. The vision is not to sell one country's system to another. It is to build the system that a region builds on, a multi-national procurement infrastructure that serves governments across ASEAN and beyond.

---

## Architectural Distinction: Workflow vs. Domain Model

The clearest way to understand the electronic-to-digital shift is through how a system models its own purpose.

**Workflow management** (the electronic paradigm): The system knows there is a tender. It knows the tender has stages. It moves the tender through those stages and records what happens at each one. The intelligence lives in the process definition. Change the process and you change what the system can do.

**Procurement as domain model** (the digital paradigm): The system knows what procurement is. It understands suppliers as entities with capabilities, track records, and risk profiles. It understands contracts as living relationships, not completed transactions. It understands policy objectives (SME participation, sustainability, strategic autonomy) as constraints that shape every procurement decision, not as reporting requirements applied after the fact.

In domain-driven design terms, the electronic paradigm is process-centric. The digital paradigm is domain-centric. The former automates what humans used to do manually. The latter enables outcomes that were not previously possible at all.

---

## Sources

1. **Carol Lo, Chia Puay Long, Tey Soon Heng**. "GeBIZ: From Vision to Reality." DSTA Horizons, 2006, pp. 16-23. [scribd.com/document/578968832/dh02200602-gebiz-from-vision-to-reality](https://www.scribd.com/document/578968832/dh02200602-gebiz-from-vision-to-reality)
2. **GeBIZ About Us**. [gebiz.gov.sg/about-us.html](https://www.gebiz.gov.sg/about-us.html)
3. **IDA International**. Wholly owned subsidiary of IDA, established February 2009, ceased operations 31 March 2016. [en.wikipedia.org/wiki/IDA_International](https://en.wikipedia.org/wiki/IDA_International)
4. **Toppan Ecquaria**. "Exporting Public Service Infocomm with IDA International." [toppanecquaria.com](https://toppanecquaria.com/exporting-public-service-infocomm-with-ida-international/)
5. **Centre for Public Impact**. "GeBIZ: government e-procurement system in Singapore." [centreforpublicimpact.org](https://centreforpublicimpact.org/public-impact-fundamentals/gebiz-government-e-procurement-system-in-singapore/)
