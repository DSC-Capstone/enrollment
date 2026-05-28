---
name: Babak Salimi

email: bsalimi@ucsd.edu

photo:

website: https://bsalimi.github.io/

industry: false

domain: D33

title: "Safe Agentic AI: Data-Centric Methods for Auditing, Aligning, and Hardening LLM Agents"

bio: |
  Babak Salimi is an Assistant Professor at the Halıcıoğlu Data Science Institute and the Department of Computer Science and Engineering at UC San Diego. His research sits at the intersection of responsible data management, causal inference, and machine learning, with recent emphasis on data-centric foundations for safe and trustworthy LLM-based agents. His work has appeared at NeurIPS, ICML, VLDB, SIGMOD, and ICLR, and has been recognized with an NSF CAREER Award and an ACM SIGMOD Research Highlight. He currently leads projects on data valuation under attack, alignment under uncertain or biased reward signals, and verifiable behavior in agentic systems.

description: |
  LLM-based agents — systems that browse the web, write code, file tickets, and execute tools on our behalf — are racing into production faster than our ability to make them safe. An agent that quietly exfiltrates a credential, follows a prompt-injection embedded in a webpage, or learns from a poisoned trajectory to game its own reward is not a hypothetical: each is a documented failure mode of the systems being deployed today. This domain attacks agent safety from a data-centric angle. Rather than bolt safety on at inference time, students will study and build methods that find unsafe behavior at the data layer — scoring training trajectories for reward hacking, prompt-injection susceptibility, and unsafe tool use; valuing preference and alignment data to surface the examples that actually buy safety vs. the ones that just inflate the corpus; and stress-testing trained agents with adversarial data attacks adapted from my group's recent work on disrupting LLMs (TokenSwap, NeurIPS 2025) and on data valuation under attack (KAIROS / SAVAGE / LAVA). The team will deliver an open-source pipeline that takes an agent training dataset in, returns a per-trajectory safety/value score and a curated subset out, and demonstrates — on standard agent benchmarks — that the curated agent is measurably safer (lower jailbreak rate, lower reward-hacking rate, fewer unsafe tool calls) without sacrificing task success. The result is the kind of evidence regulators, red-teamers, and ML engineers are all currently asking for and nobody has cleanly delivered.

summer: |
  Students should be comfortable with the base DSC prerequisites (DSC 80, 100, 102, 106, 140A, 148, and a probability/inference course). Beyond that, this domain assumes (a) solid Python + PyTorch, (b) prior exposure to deep learning fundamentals — backprop, gradient descent, transformer architectures at the conceptual level (DSC 140B or CSE 151B is helpful), and (c) basic familiarity with the Hugging Face ecosystem (datasets, transformers, trl). Comfort reading recent ML papers is more important than any specific course. Background in causal inference, RL, or statistical learning theory is a plus but not required.

  Readings — please ground yourselves in agent safety and data-valuation literature:
  1. "Data Shapley: Equitable Valuation of Data for Machine Learning" (Ghorbani & Zou, ICML 2019)
  2. "LAVA: Data Valuation without Pre-Specified Learning Algorithms" (Just et al., ICLR 2023)
  3. Our NeurIPS 2025 paper (KAIROS / MMD-based valuation, including the adversarial setting): https://arxiv.org/abs/2506.23799
  4. At least one survey on LLM agents and one on agent safety / red-teaming (e.g., AgentBench, the InjecAgent benchmark, and Anthropic's / OpenAI's recent agent safety writeups).
  5. At least one paper on reward hacking or specification gaming in RLHF.

  Hands-on — pick one:
  - Clone the previous capstone team's code (https://github.com/deepikasenthil24/kairos-data-curation) and reproduce a small KAIROS-curated fine-tuning experiment; come in able to explain every line and identify where you would inject safety scores.
  - Stand up an end-to-end Hugging Face fine-tuning loop on a small open-weights model (e.g., Qwen2.5-1.5B or Llama-3.2-1B) using `trl` on a public instruction / agent-trajectory dataset, then run any open jailbreak or prompt-injection benchmark against the result; come in with a notebook that fine-tunes, evaluates task success, and logs at least one safety metric.

  Q1 replication target: re-implement the MMD/KAIROS valuation pipeline against last year's benchmark, then adapt it so the value function rewards safety (low jailbreak susceptibility, low unsafe-tool-call rate) rather than just accuracy. By the end of Q1 you should have safety-aware data scores for a non-trivial agent training set.

time: Fridays, 11am–12pm (Pacific). Flexible to adjust around students' fall schedules; if a different fixed Friday slot works better for the team I'm open to it.

modality: Zoom

oldstudent: https://deepikasenthil24.github.io/efficient-fine-tuning-data-curation-kairos/

style: |
  I run my capstone domain like a small research group. Students are expected to read papers, present them in section, and own a piece of an open research question end-to-end. I integrate capstone teams into my broader group's data-valuation and LLM-alignment work, which means students will (a) have access to my PhD students and lab infrastructure (DSMLP storage, group Slack, code repos), (b) be expected to present progress weekly, and (c) be encouraged — though not required — to push their work toward a workshop submission or open-source release. I am fairly hands-on early in the quarter while the team gets oriented and lighter-touch in Q2 once the team has its own momentum. Students should come in expecting to read papers, write code, debug GPU jobs, and write up results — in roughly that proportion.

seats: 4

tag: sys

goal: |
  By the end of Q1, each student should be able to: (1) clearly explain the MMD/KAIROS data-valuation framework and the math behind KL, Wasserstein, and MMD divergences, plus the basic threat model for unsafe agents (prompt injection, reward hacking, unsafe tool use); (2) have reproduced the previous capstone's KAIROS-curated fine-tuning result as the Q1 replication project; (3) have stood up a small end-to-end LLM fine-tuning pipeline (a 1–3B open-weights model with LoRA via `trl`) on a public agent / instruction dataset and run at least one safety benchmark against the resulting model; and (4) have a written Q2 proposal that picks one concrete safety angle to attack — e.g., trajectory valuation for safety, prompt-injection-resistant data curation, reward-hacking detection at the data layer, or safety-aware preference data selection — with a baseline, an evaluation plan, and a milestone schedule.

notes: |
  Students who finish strong and want to keep going past the showcase are welcome to continue with my group as undergrad researchers; several past capstone students have done this. I travel for conferences a few times during the year (NeurIPS, ICLR, SIGMOD, VLDB), and I'll give the team plenty of notice and asynchronous coverage when that happens.
---
