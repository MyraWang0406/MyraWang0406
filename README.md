# Zhimin (Myra) Wang

I build research prototypes for **traceable AI-assisted decision-making**.

My work focuses on how AI systems support evidence-grounded reasoning, decision memory, conflict detection, and human oversight in user research, requirements engineering, and organizational workflows.

I am also extending this line of work toward **LLM-agent social simulation**, asking how agents behave under organizational constraints such as hierarchy, incentives, accountability, memory, and conflicting goals.

> Core question:  
> How can AI agents help people make better decisions with evidence, memory, and traceability — without replacing human judgment?

---

## Research Interests

- Human-AI collaboration
- Requirements engineering
- Decision traceability
- Crowd feedback mining
- AI-assisted user research
- Organizational memory
- AI-assisted diagnosis
- LLM-agent social simulation
- Computational social science
- CSCW / HCI

---

## Main Research Thread

### 1. Traceable Requirements & Decision Memory

This line of work explores how AI systems can preserve evidence, prior decisions, falsified assumptions, and conflicting signals during requirements analysis and user research.

| Project | What it does | Research value |
|---|---|---|
| [UserResearchAgent-CF](https://github.com/MyraWang0406/UserResearchAgent-CF) | Decision-memory prototype for evidence citation, falsification tracking, and conflict detection | Tests the principle of “no citation, no decision” in AI-assisted requirements workflows |
| [Agent-Assisted-User-Research-and-Decision-Support](https://github.com/MyraWang0406/Agent-Assisted-User-Research-and-Decision-Support) | Portfolio site for agent-assisted user research and decision-support prototypes | Connects reflective AI, user research, and decision traceability into a coherent research direction |
| [MatrixMirix.WhatIf](https://github.com/MyraWang0406/MatrixMirix.WhatIf) | Multi-agent deliberation prototype for exploring assumptions before decisions | Studies how role-based agents support perspective-taking, scenario decomposition, and reflective reasoning |

The goal is to make AI-assisted decisions inspectable.  
A decision should not only produce an answer, but also preserve the evidence, assumptions, uncertainty, conflicts, and rejected alternatives behind it.

---

### 2. Crowd Feedback → Requirement Signals

Online user feedback is noisy, fragmented, multilingual, and platform-dependent. These projects examine how crowd feedback can be transformed into structured, inspectable requirement intelligence.

| Project | What it does | Research value |
|---|---|---|
| [Auto-sentiment-copilot-V1](https://github.com/MyraWang0406/Auto-sentiment-copilot-V1) | Cross-platform crowd feedback mining system for phones, vehicles, robots, and smart home products | Treats platform identity as a variable rather than a simple source label |
| [CrowdRE2026-Beyond-App-Reviews-Archive](https://github.com/MyraWang0406/CrowdRE2026-Beyond-App-Reviews-Archive) | Submission archive for a CrowdRE 2026 paper on platform-aware crowd feedback mining | Links raw feedback, topic clusters, evidence samples, and requirement candidates |
| [UsedCarInsightForManus](https://github.com/MyraWang0406/UsedCarInsightForManus) | NLP pipeline for second-hand vehicle feedback from Bilibili and Reddit | Surfaces second-hand EV buyers as an often invisible stakeholder group in requirements pipelines |

The goal is not to build another sentiment dashboard.  
The goal is to preserve the chain from raw crowd feedback to requirement candidate:

**source platform → topic cluster → evidence sample → requirement signal**

---

### 3. AI-Assisted Diagnosis in Automated Decision Systems

This line of work applies the same traceability idea to automated system workflows, especially where operators need to understand why a system made or failed a decision.

| Project | What it does | Research value |
|---|---|---|
| [ADX-Mirix-1.15-cursor](https://github.com/MyraWang0406/ADX-Mirix-1.15-cursor) | White-box ad exchange simulator with traceable logs and an AI diagnostic agent | Makes invisible filtering, bidding, and win/loss decisions inspectable |
| [ADX-experiment-V2](https://github.com/MyraWang0406/ADX-experiment-V2) | Experimental dashboard for ad-system A/B testing and decision support | Explores how operators compare outcomes and diagnose metric changes |

This direction studies how AI agents can support operational reasoning without hiding behind black-box recommendations.

Instead of only asking “what happened?”, I am interested in systems that help users inspect:

- what evidence was used
- what rule or model triggered the outcome
- where the decision path failed
- which alternative explanation remains plausible
- what intervention should be tested next

---

### 4. Emerging Direction: LLM-Agent Social Simulation for Organizational Behavior

I am extending my work on decision memory and traceability toward multi-agent social simulation.

The next research question is not only whether an AI system can support one decision, but how multiple agents behave when they operate under organizational constraints such as hierarchy, incentives, risk, accountability, memory, and conflicting goals.

This direction connects my existing prototypes in decision memory, requirement traceability, and diagnostic workflows with computational social science and agent-based simulation.

| Research angle | What I want to study | Possible prototype |
|---|---|---|
| Organizational memory | How past evidence, falsified assumptions, and prior decisions constrain later group decisions | Multi-agent decision-memory simulation |
| Conflict and accountability | How agents respond when goals, incentives, and evidence conflict | Simulated requirement review / escalation workflow |
| Hierarchy and incentives | How KPI pressure, role hierarchy, and risk-shifting affect cooperation | Big-tech-style organizational simulation |
| Human-AI mixed experiments | How human participants and AI agents negotiate, cooperate, or disagree in structured tasks | Hybrid decision-making experiment |
| Cross-cultural / multilingual agents | How language and cultural framing affect simulated decisions and conflict resolution | Multilingual agent simulation scenarios |

This is an early-stage research direction. I treat LLM-agent simulation as a controlled testbed for generating hypotheses about organizational behavior, not as a replacement for human-subject studies.

---

## Exploratory Prototypes: Simulation, Reflection, and Causal Reasoning

These projects are not my main research line yet. I use them to explore how interactive systems help people build causal intuitions, revisit past decisions, and reason through change over time.

| Project | What it explores | Why it matters |
|---|---|---|
| [Cognitive-Learning-Lab](https://github.com/MyraWang0406/Cognitive-Learning-Lab) | Simulation-based learning environment for exploratory causal reasoning | Connects interactive simulation with human sensemaking |
| [temporal-garden](https://github.com/MyraWang0406/temporal-garden) | Temporal reflection prototype examining how people revisit and reinterpret past decisions over time | Explores reflection, reinterpretation, and longitudinal decision memory |
| [Memory-Genesis](https://github.com/MyraWang0406/Memory-Genesis) | Longitudinal personal decision-memory prototype | Explores how people reconstruct past decisions |
| [MatrixMirix.WhatIf](https://github.com/MyraWang0406/MatrixMirix.WhatIf) | Multi-agent reflective decision-support prototype | Explores assumption surfacing and perspective comparison |

These prototypes are exploratory. I use them to test design ideas before turning them into more formal research studies.

---

## Current Focus

I am currently developing a research portfolio around:

1. **Traceable AI-assisted requirements engineering**  
   How AI systems preserve evidence, contradiction, and decision history during requirements work.

2. **Crowd feedback as requirement intelligence**  
   How heterogeneous user feedback across platforms can be converted into evidence-backed requirement signals.

3. **AI-assisted diagnosis for complex workflows**  
   How operators can inspect and act on AI-supported decisions in automated systems.

4. **LLM-agent social simulation for organizational behavior**  
   How simulated agents behave under hierarchy, incentives, accountability pressure, memory constraints, and conflicting goals.

---

## Design Principles

Across these projects, I care about several recurring principles:

### 1. Traceability over generation

AI systems should not only generate outputs.  
They should preserve how an output was produced, which evidence supported it, and which assumptions remained uncertain.

### 2. Human oversight over full automation

I do not treat AI agents as replacements for human judgment.  
I am more interested in how agents help people inspect, compare, challenge, and revise decisions.

### 3. Evidence before recommendation

A recommendation without evidence is difficult to trust.  
A useful AI system should expose the evidence trail behind the recommendation.

### 4. Memory as infrastructure

Many workflow failures happen because teams forget earlier decisions, rejected options, known risks, or prior contradictions.  
I treat decision memory as infrastructure for better reasoning.

### 5. Simulation as hypothesis generation

Simulation cannot replace real-world validation.  
But it can help generate hypotheses, stress-test assumptions, and make invisible dynamics easier to inspect.

---

## Background

I have experience across growth platforms, user research, product operations, and behavioral analytics. This shaped my interest in decision-making under real organizational constraints: incomplete evidence, shifting goals, conflicting stakeholders, weak memory across teams, and pressure to act before information is complete.

Rather than treating AI only as a generation tool, I study how AI systems can help people reason more carefully, preserve decision context, and avoid repeating previously falsified assumptions.

My broader research direction sits at the intersection of:

- Human-AI collaboration
- Requirements engineering
- Organizational decision-making
- Computational social science
- Interactive systems for reflection and reasoning

---

## Selected Project Map

| Area | Representative projects |
|---|---|
| Decision memory and traceability | UserResearchAgent-CF, MatrixMirix.WhatIf, Memory-Genesis |
| Crowd feedback and requirements | Auto-sentiment-copilot-V1, CrowdRE2026-Beyond-App-Reviews-Archive, UsedCarInsightForManus |
| AI-assisted diagnosis | ADX-Mirix-1.15-cursor, ADX-experiment-V2 |
| Simulation and causal reasoning | Cognitive-Learning-Lab, temporal-garden |
| Emerging multi-agent social simulation | Future work connecting decision memory, organizational incentives, and LLM-agent behavior |

---

## Research Availability

I am interested in **RA / PhD opportunities** in:

- HCI
- CSCW
- Human-AI Collaboration
- Requirements Engineering
- AI for organizational decision-making
- Computational Social Science

Timeline: 2026–2027

Email: myra0406@sjtu.edu.cn
