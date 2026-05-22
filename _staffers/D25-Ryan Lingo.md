---
name: Ryan Lingo and Rajeev Chhajer

email: ryan_lingo@honda-ri.com and rajeev_chhajer@honda-ri.com

photo:

website: www.99plabs.com

domain: D25

title: "Epistemic Engines: Turning Raw Data into Living Knowledge Bases for AI Agents"

bio: |
  Rajeev Chhajer is the Chief Engineer at Honda Research Institute USA and leads the Software-defined Intelligence team at 99P Labs. He is a founding member of 99P Labs, a research initiative dedicated to developing sustainable technologies and innovative approaches to global challenges. His research focuses on smart city ecosystems, embedded systems, and connectivity to support sustainable and efficient mobility. Ryan Lingo is an Applied AI Research Engineer and Developer Advocate at 99P Labs. His work focuses on intelligent systems, with research interests in large language models, synthetic data, and applied machine learning. He has an academic background in philosophy and has held roles in data science and software engineering, with experience spanning academic research, industry, consulting, and early-stage startups.

description: |
  Data is everywhere, but most of it sits in forms that are hard to use: buried in PDFs, scattered across spreadsheets, locked in databases, streaming from sensors, hiding in web pages. What if we could take all of that, normalize it into a clean, readable format like Markdown, and hand it to AI agents that build and maintain structured knowledge from it? That's the core question behind this domain. We'll explore how to turn messy, heterogeneous data (structured and unstructured) into a common substrate that LLM-powered agents can read, reason over, link together, and keep current. From there, the question opens up: what does it mean to "create knowledge" from data? That could look like an agent that synthesizes a living wiki from research papers, one that tracks and reconciles contradictory claims across news sources, one that monitors a domain and surfaces what's missing, or something else entirely. A hard problem running through all of this is evaluation: how do you measure whether a system is actually producing good knowledge? Factual accuracy is just the starting point. You also need to think about coverage, coherence, source grounding, staleness, and whether the system knows what it doesn't know. Designing the right evaluation framework may be as interesting as building the system itself. A key starting point is Andrej Karpathy's "LLM Wiki" pattern (https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f), where raw sources flow into a folder and an LLM agent compiles and maintains an interlinked Markdown knowledge base, browsable in Obsidian. Students will build on this idea and push it in their own direction. Relevant references include Lewis et al. on retrieval-augmented generation (https://arxiv.org/abs/2005.11401), Hogan et al. on knowledge graphs (https://arxiv.org/abs/2003.02320), Gärdenfors' Knowledge in Flux on belief revision, and the Stanford STORM project on LLM-driven research synthesis (https://storm.genie.stanford.edu/).

summer: |
  1. Build Karpathy's LLM Wiki yourself. This is the most important summer task. Follow Karpathy's gist (https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) to set up an Obsidian vault with a raw/ folder for sources and a wiki/ folder where an LLM agent maintains interlinked Markdown notes. Use OpenCode (https://opencode.ai) as your agentic coding tool. It's free, open-source, and works with 75+ LLM providers including local models via Ollama. Drop in 10-20 sources on a topic you care about (research papers, articles, transcripts) and have the agent compile a wiki from them. Browse the result in Obsidian's graph view. The goal is to feel both the power and the limitations: where does the synthesis break down? What gets lost? What would you add?

  2. Read these:
  Karpathy's original thread on LLM knowledge bases: https://x.com/karpathy/status/2039805659525644595
  Lewis et al., "Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks" (2020): https://arxiv.org/abs/2005.11401
  Hogan et al., "Knowledge Graphs" (2021): https://arxiv.org/abs/2003.02320
  Skim the Stanford STORM project: https://storm.genie.stanford.edu/

  3. Get familiar with the tools. Install and try OpenCode (https://opencode.ai/docs). Install Obsidian (https://obsidian.md) and explore plugins like Dataview and Graph View. If you haven't used a vector database (Chroma, Weaviate, etc.), set one up and run some queries. If you've never worked with graph databases (Neo4j), watch an intro tutorial.

  4. Think about what interests you. The domain is deliberately open. Some directions you might explore: evidence grounding (can every claim trace back to a source?), belief revision (what happens when new evidence contradicts old beliefs?), contradiction detection across sources, confidence scoring, hypothesis generation (what's missing from the knowledge base?), cross-domain transfer (can patterns from one field unlock insights in another?). Come to fall with at least one domain you'd want to point this system at (scientific literature, journalism, clinical data, competitive intelligence, something else) and a rough sense of which problem within it excites you most.

  5. Start thinking about evaluation. This is one of the hardest parts of the project and worth thinking about early. If your system produces a knowledge base, how do you know it's any good? You might evaluate factual accuracy against ground truth, measure coverage relative to a source corpus, check whether every claim is grounded in evidence, test how well the system handles contradictions, or assess whether it correctly identifies gaps. There's no single right answer here. Part of the research is figuring out what "good knowledge" means for your specific domain and building a way to measure it. Come to fall with some initial thoughts on what you'd want to measure and how.

  Technologies you'll use: Python, OpenCode, Obsidian, LLM APIs, Markdown as a knowledge substrate, possibly vector databases and graph databases. If any of these are unfamiliar, spend time with them over the summer.

time: Weekly at the student team discretion

modality: Zoom

ta: TBA

style: |
  We plan to take an engaged but student-led approach to mentoring. We'll work closely with the students throughout the project, meeting regularly, providing guidance, and being available for feedback and support. That said, we're looking for high-agency students who are excited to take ownership of their learning and direction. The best mental model for this capstone is "learning in public." Students will play an active role in shaping the plan and setting objectives. Rather than being given step-by-step instructions, they'll be encouraged to explore, make decisions, and figure out how to execute their ideas, with our mentorship to guide the way. We'll help them think critically, problem-solve, and communicate their process and outcomes clearly. While we won't dictate tasks at a granular level, we'll be present every week and ensure they have the support and structure they need to succeed.

seats: 12

tag: llm
---
