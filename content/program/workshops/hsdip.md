---
title: "ICAPS'26 Workshop: HSDIP"
date: 2026-03-23T10:51:00+02:00
draft: false
---

# Workshop on Heuristics and Search for Domain-independent Planning (HSDIP 2026)

## Important dates

| Schedule            |          |
|---------------------|----------|
| Submission          | ~~May 7, 2026~~ May 14, 2026 |
| Notification        | May 28, 2026|
| Camera Ready        | ~~June 8, 2026~~ June 14, 2026 |
| Workshop            | June 29, 2026 |
<br/>
All deadlines are _AoE(UTC-12)_.
<br/>

## Aim and Scope of the Workshop

Heuristics and search algorithms are the two key components of heuristic search, one of the main approaches to many variations of domain-independent planning, including classical planning, temporal planning, planning under uncertainty and adversarial planning. This workshop seeks to understand the underlying principles of current heuristics and search methods, their limitations, ways for overcoming those limitations, as well as the synergy between heuristics and search.

The HSDIP workshop has always been welcoming of multidisciplinary work, for example, drawing inspiration from operations research (like row and column generation algorithms), convex optimization (like gradient optimization for hybrid planning), constraint programming, satisfiability, or applications of machine learning in heuristic search (e.g., learning heuristics, or heuristic selection).

The workshop is meant to be an open and inclusive forum, and we encourage papers that report on work in progress or that do not fit the mold of a typical conference paper.
Contributions do not have to show that a new approach outperforms the state of the art. While performance measured in the number of evaluated nodes, time, and solution quality remains relevant, in this workshop we seek above all crisp and meaningful ideas and understanding. We are interested in all variations of domain-independent planning such as classical planning, temporal planning, hybrid planning, planning under uncertainty, adversarial planning, or (model-based) reinforcement learning. Non-trivial negative results are welcome to the workshop, but we expect the authors to argue for the significance of the presented results.

## Topics of Interest

Examples of typical topics for submissions to this workshop are:

- automatic derivation of heuristic estimators for domain-independent planning
- formal results showing equivalence or dominance between heuristics
- novel heuristic methods dealing with planning with numeric variables
  and effects, partial observability and non-deterministic action effects
- heuristic estimators for domain-independent planning via procedures or
  suitably defined encodings of declarative descriptions of planning tasks into
  satisfiability or optimisation
- novel search techniques for domain-independent planning that explicitly aim at
  exploiting effectively the properties of existing heuristics
- empirical observations of synergies between heuristics and search in
  domain-independent planning
- challenging domains for existing combinations of heuristics and search
  algorithms
- applications of machine learning in heuristic search, e.g., learning heuristics,
  adaptive search strategies, or heuristic selection
- interesting algorithmic optimizations for the calculation of a
  heuristic or the execution of a search

## Schedule

<style>
.hsdip-schedule {
  --accent: #f5821f;
  --accent-soft: #fff4ea;
  --line: #ededed;
  margin: 1.5rem 0 2.5rem;
}
.hsdip-schedule .hsdip-day {
  margin: 0 0 .25rem;
  font-size: 1.45rem;
  color: #2b2b2b;
  border-bottom: 2px solid var(--accent);
  padding-bottom: .3rem;
}
.hsdip-schedule .hsdip-session {
  display: flex;
  align-items: baseline;
  gap: .6rem;
  margin: 1.9rem 0 .6rem;
}
.hsdip-schedule .hsdip-session .name {
  font-size: 1.12rem;
  font-weight: 700;
  color: var(--accent);
}
.hsdip-schedule .hsdip-session .clock {
  font-size: .9rem;
  color: #777;
  font-variant-numeric: tabular-nums;
}
.hsdip-schedule .hsdip-note {
  color: #666;
  font-style: italic;
  margin: .4rem 0 .9rem;
}
.hsdip-schedule table {
  width: 100%;
  border-collapse: collapse;
  margin: .4rem 0 1.1rem;
  font-size: .92rem;
  background: #fff;
  border: 1px solid var(--line);
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 1px 3px rgba(0, 0, 0, .07);
}
.hsdip-schedule thead { display: none; }
.hsdip-schedule tbody td {
  padding: .55rem .85rem;
  border-top: 1px solid var(--line);
  vertical-align: top;
  line-height: 1.4;
}
.hsdip-schedule tbody tr:nth-child(even) { background: #faf9f8; }
.hsdip-schedule tbody tr:hover { background: var(--accent-soft); }
.hsdip-schedule td:first-child,
.hsdip-schedule th:first-child {
  white-space: nowrap;
  font-weight: 700;
  color: var(--accent);
  font-variant-numeric: tabular-nums;
  width: 1%;
}
.hsdip-schedule td:nth-child(2) { font-weight: 600; color: #222; }
.hsdip-schedule td:nth-child(3) { color: #555; }
.hsdip-schedule td:last-child,
.hsdip-schedule th:last-child {
  text-align: center;
  white-space: nowrap;
  width: 1%;
  color: #888;
  font-size: .82rem;
  font-variant-numeric: tabular-nums;
}
.hsdip-schedule .hsdip-break {
  display: flex;
  align-items: center;
  gap: .5rem;
  background: var(--accent-soft);
  border-left: 4px solid var(--accent);
  padding: .55rem .9rem;
  margin: 1rem 0 1.6rem;
  border-radius: 6px;
  font-weight: 600;
  color: #8a4b12;
}
@media (max-width: 600px) {
  .hsdip-schedule table { font-size: .82rem; }
  .hsdip-schedule td, .hsdip-schedule th { padding: .4rem .5rem; }
}
</style>

<div class="hsdip-schedule">

<h3 class="hsdip-day">Morning</h3>

<div class="hsdip-session"><span class="name">Session 1</span><span class="clock">9:00-10:30</span></div>

<p class="hsdip-note">9:00 — Introduction</p>

| Time | Paper | Authors | Len |
|------|-------|---------|-----|
| 9:05 | A\* with h^max Definitely Finds Optimal Plans -- Formally Verifying a Planner Based on Heuristic Search | Gregor Behnke, Simone Kilian and Malvin Gattinger | L |
| 9:20 | Eager vs. Lazy Duplicate Detection in A\* | Yuki Suzuki and Alex Fukunaga | L |
| 9:35 | Base Strategy Still Matters: Triangle Search in Domain-Independent Planning | Jordan Thayer, Sofia Lemons and Jendrik Seipp | L |
| 9:50 | Compact Representatives of Potential Heuristics | Simon Dold and Malte Helmert | S |
| 10:00 | Delete Relaxation with Axioms | Travis Rivera Petit, Simon Dold, David Speck and Malte Helmert | L |
| 10:15 | GONDOR to the Rescue: Satisficing Planning with Low Memory | Yonatan Vernik, Alexander Tuisov and Alexander Shleyfman | S |

<div class="hsdip-break">Coffee break - 10:30-10:50</div>

<div class="hsdip-session"><span class="name">Session 2</span><span class="clock">10:50–12:30</span></div>

| Time | Paper | Authors | Len |
|------|-------|---------|-----|
| 10:50 | Parallelizing Classical Planning: Critical Path Heuristics on the GPU | Markus Fritzsche, David Speck, Daniel Gnad and Simon Ståhlberg | S |
| 11:00 | Parallel Lifted Planning via Semi-Naive Datalog Evaluation | Dominik Drexler, Oliver Joergensen and Jendrik Seipp | L |
| 11:15 | Distributed Parallel Datalog in Automated Planning | Oliver Joergensen, Dominik Drexler and Jendrik Seipp | L |
| 11:30 | Dynamic Tree Databases in Automated Planning | Oliver Joergensen, Dominik Drexler and Jendrik Seipp | L |
| 11:45 | Pattern Database Heuristics for Lifted Planning | Mika Skjelnes, Dominik Drexler, Jordan Thayer, Daniel Gnad and Jendrik Seipp | S |
| 11:55 | Reviving Partial Order Causal Link (POCL) Planning: Is It Possible? Is It Worth It? | Scott Howsam, Harrison Oates and Pascal Bercher | L |
| 12:10 | A Quantitative Evaluation Pipeline for Map Partitioning for Grid Pathfinding | Yan Wu, Chenyuan Zhang, Yangmengfei Xu and Guang Hu | L |

<div class="hsdip-break">Lunch break - 12:30-14:00</div>

<h3 class="hsdip-day">Afternoon</h3>

<div class="hsdip-session"><span class="name">Session 3</span><span class="clock">14:00-15:30</span></div>

| Time | Paper | Authors | Len |
|------|-------|---------|-----|
| 14:00 | When Local Plans Cannot Be Global: A Sheaf-Theoretic View of Decomposition in Numeric Planning | Jiajia Song and Guang Hu | L |
| 14:15 | On the Optimality of Numeric Planning with Control Variables | Ángel Aso-Mollar, Diego Aineto, Enrico Scala and Eva Onaindia | L |
| 14:30 | A Notion of Width for Numeric Planning Problems | Giacomo Rosa, Nir Lipovetzky, Jean Honorio, Sebastian Sardina and Enrico Scala | L |
| 14:45 | Domain-Abstraction Heuristics for Simple Numeric Planning | Markus Fritzsche, Mikhail Gruntov, Alexander Shleyfman and Daniel Gnad | S |
| 14:55 | Counting Plans with Heuristic State-Space Search | David Speck | S |
| 15:05 | Make Yourself Special: Qualified Dominance Task Reformulation For Optimal Planning | Rasmus Tollund and Álvaro Torralba | L |

<div class="hsdip-break">Coffee break - 15:30-15:50</div>

<div class="hsdip-session"><span class="name">Session 4</span><span class="clock">15:50-17:30</span></div>

| Time | Paper | Authors | Len |
|------|-------|---------|-----|
| 15:50 | Bounded-Suboptimal Beam Search | Devin Wild Thomas, Stephen Wissow, Michael Bauer, Paige McAfee and Wheeler Ruml | L |
| 16:05 | Computing Potential Heuristics Without Grounding PDDL Actions | Pascal Lauer, Álvaro Torralba and Daniel Fišer | L |
| 16:20 | A Comparison of Cost Partitioning Algorithms for Multiple Sequence Alignment | Mika Skjelnes, Daniel Gnad and Jendrik Seipp | L |
| 16:35 | Learning Admissible Heuristics via Cost Partitioning | Hugo Barral, Quentin Cappart, Marie-José Huguet and Sylvie Thiébaux | L |
| 16:50 | Bound-Aware Heuristic Discovery with Large Language Models: A 15-Puzzle Case Study | Xiaojia Li, Csaba Kiss, Roland Molontay and József Pintér | L |
| 17:05 | Automated Planning with Incomplete Open World Models | Mikhail Soutchanski | L |

<p class="hsdip-note">17:20 — Closing remarks</p>

</div>

<small>Talk length is shown in the last column: <strong>L</strong> = long paper (12+3 min), <strong>S</strong> = short paper (8+2 min).</small>


## Submission Details

Please format submissions in AAAI style (see instructions in the Author Kit at [this link](https://aaai.org/authorkit26-1/)). Long (up to 9 pages including references) and short (up to 5 pages including references) papers are the standard category, submissions shorter than the page limit are welcome. Long papers will be allocated a longer presentation at the workshop.

Submissions will be made through EasyChair: [Submission Website](https://easychair.org/conferences/?conf=icapshsdip2026)


The following conditions apply:

- Submissions will be *double blind* (except for two program chairs who will see author names).
- Papers will be reviewed by a member of the organizing committee, and/or external reviewers selected by the organizing committee, according to the usual criteria such as relevance to the workshop, significance of the contribution, and technical quality.
- Discussions between reviewers and organizers will remain *private*.

At least one author of each accepted paper must attend the workshop in order to present the paper.

### Policy on Previously Published Materials

*Previously published papers* to conferences *other than ICAPS* are allowed. They will only receive a light review for relevance by a member of the organizing committee. Please do not submit papers accepted at the main conference.

*Rejected papers from the main conference* are welcome if you do your utmost to address the comments given by ICAPS reviewers.

*Parallel submissions* sent to other conferences are allowed from our side. It is your responsibility to ensure that those venues allow for papers submitted to be published in parallel "informal" ways (e.g. in workshop proceedings or websites without associated ISSN/ISBN).

## Workshop Committee

### Organizing Committee
You can contact us at [hsdip@googlegroups.com](mailto:hsdip@googlegroups.com).

- [Malte Helmert](https://ai.dmi.unibas.ch/people/helmert/), University of Basel, Switzerland
- [Arnaud Lequen](https://mrlab.ai/arnaud-lequen/), Linköping University, Sweden
- [Alison Paredes](https://mulab.ai/member/alison.paredes/), Queen's University, Canada
- [Devin Thomas](https://dwthomas.github.io/), University of New Hampshire, United States
