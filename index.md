--- 
layout: page
--- 

Hi there, I am a PhD student and Minerva Scholar at the University of Glasgow.

_Website last updated: September 2026_.

<p>&nbsp;</p>

## Research interests
I am mainly interested in problems at the intersection of computing, mathematics, and economics. 

I tackle questions like _"What are good/fair/robust rules and outcomes, and can we design efficient algorithms to achieve them?"_, currently mostly in matching and allocation settings involving preferences or utilities, such as Stable Roommates, Stable Fixtures, Housing Markets, and Kidney Exchanges. 

Some broader applicable keywords are _Algorithms & Complexity, Market and Mechanism Design, (Algorithmic) Game Theory,_ and _(Computational) Social Choice._

Most of my research is theoretical, but I am also excited about experimental research, real-world applications, and tools (e.g., see our platform [matwa.optimalmatching.com](https://matwa.optimalmatching.com/)). I am lucky to be supervised by [Professor David Manlove](https://www.dcs.gla.ac.uk/~davidm/) and [Dr Sofiat Olaosebikan](https://www.dcs.gla.ac.uk/~sofiat/).
<p>&nbsp;</p>


## Selected research

[Click here](publications) for a full list of my research papers, including 8+ peer-reviewed publications. [This short paper](https://doi.org/10.65109/SLTP2592) gives a concise summary of my PhD research (so far). Below is a selection of my favourite recent works.

- **A Minimax Perspective on Almost-Stable Matchings**, Frederik Glitzner and David Manlove. [[Full preprint](https://arxiv.org/abs/2601.14195)] [[AAMAS 2026](https://doi.org/10.65109/PCDE6577)]
  - When full stability in a matching market is unachievable, how should we distribute the instability? Standard approaches minimise instability globally, which can unfairly concentrate justified envy locally onto a few agents. We introduce a minimax approach to this problem: what if we minimise the worst-case instability experienced by any single participant? While we uncover strong computational intractability barriers and discouraging bounds for worst-case outcomes, we provide fast approximate and heuristic approaches and show promising average-case results.

- **Near-Feasible Stable Matchings: Incentives and Optimality**, Frederik Glitzner. [[Full preprint](https://arxiv.org/abs/2602.10851)] [[AAMAS 2026](https://doi.org/10.65109/RZEM3915)]
  - In centralised matching markets, what happens when no stable outcome exists? Recent "near-feasibility" approaches tweak agent capacities to reach existence. But this raises questions: (how much) do these modifications affect stability in the original market, and do they give participants a strong incentive to deviate? We develop a formal framework to quantify these strategic incentives in capacitated, non-bipartite matching markets. Surprisingly, we show that minimal capacity modifications and minimal deviation incentives are fundamentally compatible, and optimal solutions can often be computed efficiently.

- **Weakly Popular and Super Popular Matchings**, Gergely Csáji and Frederik Glitzner. [[Preprint](https://arxiv.org/abs/2310.12269)]
  - Popular matchings offer a democratic way, based on a majority vote, to clear a centralised market: an outcome is popular if it is not defeated by another outcome. Unfortunately, in the matching context, popular outcomes are not guaranteed to exist when preferences contain ties. We introduce weak and super popularity, two refined voting mechanisms where agents either never or always support a different outcome if it provides equal utility. We prove that weakly popular matchings always exist and, while computing maximum-size weakly popular matchings turns out to be computationally hard, we provide an efficient approximation algorithm with tight guarantees. Our evaluation on real junior doctor allocation data shows that our mechanism can successfully match almost all doctors while causing only minimal instability.

- **Unsolvability and Beyond in Many-to-Many Non-bipartite Stable Matching**, Frederik Glitzner and David Manlove. [[Transactions on Economics and Computation](https://doi.org/10.1145/3814616)]
  - In complex matching markets, participants can have non-unit capacity constraints and non-bipartite preferences. This model generalises the classical Stable Roommates model, but it inherits its fundamental limitation: a stable matching might not exist. How can we characterise the structure of such markets, and can we exploit this structure algorithmically to still find good solutions? Building on classical stable matching theory, we introduce the "generalised stable partition" (GSP), a powerful tool that neatly characterises the solution space. We show that GSPs can be computed efficiently and how to use GSPs to find near-feasible stable matchings.


<p>&nbsp;</p>


## Talks and presentations

[Click here](talks) for a full list of my 20+ talks and presentations. Below is a selection of my favourite events/talks this year.

- **Minimax Almost-Stable Matchings**, [JECCO 2026](https://jecco2026.gitlab.io): the 2nd UK Workshop for Junior Researchers in Economics and Computation (at _University of Oxford_).
- **Designing Pairwise-Stable Seating Graph Arrangements**, [MATCH-UP 2026](https://matchup2026.crest.science/): the 8th International Workshop on Matching Under Preferences (at _New York University, Paris_).
- **Near-Feasible Stable Matchings: Incentives and Optimality**, [AAMAS 2026](https://cyprusconferences.org/aamas2026/): the 25th International Conference on Autonomous Agents and Multiagent Systems (in _Paphos, Cyprus_).
  
<p>&nbsp;</p>


## Teaching
I have a great passion for teaching and, as a [Minerva Scholar](https://www.gla.ac.uk/schools/computing/postgraduateresearch/prospectivestudents/scholarshipsandfundingopportunities/minervascholarships/), I get to spend a significant portion of my time doing it. Some courses I have supported, and the years in which I supported them, are listed below:
- As (Guest) Lecturer:
  - [Algorithms and Data Structures M](https://www.gla.ac.uk/coursecatalogue/course/?code=COMPSCI5004) - 2026
  - [Algorithmics 2 (H)](https://www.gla.ac.uk/coursecatalogue/course/?code=COMPSCI4003) - 2025
- As Tutor:
  - [Quantum Computing (H)](https://www.gla.ac.uk/coursecatalogue/course/?code=COMPSCI4105) - 2025, 2026
  - [Algorithmics 1 (H)](https://www.gla.ac.uk/coursecatalogue/course/?code=COMPSCI4009) -  2024, 2025, 2026
  - [Algorithmics (GA)](https://www.gla.ac.uk/coursecatalogue/course/?code=COMPSCI2026) - 2024, 2026
  - [Algorithmic Foundations 2](https://www.gla.ac.uk/coursecatalogue/course/?code=COMPSCI2003) - 2024, 2026
  - [Computing Fundamentals](https://www.gla.ac.uk/coursecatalogue/course/?code=COMPSCI1006) - 2026
  - [Algorithms and Data Structures M](https://www.gla.ac.uk/coursecatalogue/course/?code=COMPSCI5004) - 2026
  - [Algorithms and Data Structures 2](https://www.gla.ac.uk/coursecatalogue/course/?code=COMPSCI2007) - 2023, 2024, 2025
  - [Networks and Operating Systems Essentials 2](https://www.gla.ac.uk/coursecatalogue/course/?code=COMPSCI2024) - 2022, 2023

<p>&nbsp;</p>


## Academic and community roles
I have held a variety of academic positions over the last 4+ years, including my current role as [Minerva Scholar](https://www.gla.ac.uk/schools/computing/postgraduateresearch/prospectivestudents/minervascholarships/) (entry-level research and teaching position), and previous roles as an [SSPS Project Lead](https://www.gla.ac.uk/myglasgow/students/newsletter/archive/2024/headline_1136086_en.html) (to improve a second-year undergraduate computing course) and general Teaching Assistant.

On the editorial side, I have reviewed for the journals
- [Discrete Applied Mathematics (DAM)](https://www.sciencedirect.com/journal/discrete-applied-mathematics)
- [European Journal of Operational Research (EJOR)](https://www.sciencedirect.com/journal/european-journal-of-operational-research)
- [Information Processing Letters (IPL)](https://www.sciencedirect.com/journal/information-processing-letters)
- [Theoretical Economics (TE)](https://econtheory.org)
- [Transactions on Economics and Computation (TEAC)](https://dl.acm.org/journal/teac)

and for the conferences
- [European Symposium on Algorithms 2026 (ESA)](https://algo-conference.org/2026/esa/)
- [8th International Workshop on Matching Under Preferences (MATCH-UP)](https://matchup2026.crest.science/)
- [Symposium On Discrete Algorithms 2025 (SODA)](https://www.siam.org/conferences-events/siam-conferences/soda25/)
- [45th Foundations of Software Technology and Theoretical Computer Science (FSTTCS)](https://www.fsttcs.org.in/2025/)

Recently, I co-organised the [29th Postgraduate Combinatorial Conference (PCC)](https://sites.google.com/view/pcc2025/home) in Glasgow, which was great fun. I also organised the weekly [FATA Research Section](https://www.gla.ac.uk/schools/computing/research/researchsections/fata-section/) seminars in the academic year 2025/26, and was a member of the [British Combinatorial Committee](https://www.britishcombinatorics.org.uk/) and the School's Learning & Teaching Committee.

In the past, I have supported the [University of Zurich's Blockchain Center](https://www.blockchain.uzh.ch/) as a voluntary Research Engineer, represented my undergraduate cohort to the School of Computing Science and the School of Mathematics and Statistics as a Class Rep, and acted as a Peer Assisted Learning Mentor for new undergraduate students. I also had fun helping out at the [Glasgow Science Festival 2024](https://www.gla.ac.uk/events/sciencefestival/)!


<p>&nbsp;</p>

## Industry experience
Before the PhD, I worked as a Software Dev Engineer at [Amazon](https://www.amazon.co.uk/gp/video/livetv), Consultant at [BearingPoint](https://www.bearingpoint.com/en-gb/), and in IT Dev & Ops at the [Global Legal Entity Identifier Foundation](https://www.gleif.org/en). A few more details about that can be found on my [LinkedIn Page](https://www.linkedin.com/in/frederik-g).

<p>&nbsp;</p>


## Other activities
Previously, I thought I would end up in the space industry and was very active in [GU Orbit](https://uk.linkedin.com/company/gu-orbit), a society for near-space and orbital projects. At the time, I also had the chance to join a European Space Agency [project for rocket science](https://www.esa.int/Education/Fly_A_Rocket). 

These days, I am probably either repairing things at [Repair Cafe Glasgow](https://repaircafeglasgow.org/), appreciating nicely crafted or designed objects and buildings, enjoying (and sometimes making) good food, or [exploring the Scottish highlands and islands](scotland).
