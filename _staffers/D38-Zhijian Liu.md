---
name: Zhijian Liu

email: zhijian@ucsd.edu

photo:

website: https://z-lab.ai

domain: D38

title: "Efficient AI: Algorithms and Systems for Foundation Models"

bio: |
  Zhijian Liu is an assistant professor at HDSI, UC San Diego, leading a research group on efficient AI. He received his Ph.D. and S.M. from MIT (advised by Song Han) and his B.Eng. from Shanghai Jiao Tong University, with a gap year as a research scientist at NVIDIA. His research on efficient algorithms and systems has been adopted across industry. He has been recognized with the Qualcomm Innovation Fellowship and as a Rising Star in ML & Systems (MLCommons) and in Data Science (UChicago, UCSD).

description: |
  Foundation models have become spectacularly capable, and spectacularly expensive. A frontier LLM costs millions of dollars to train and run; a vision-language-action model controlling a robot has to respond in tens of milliseconds. This domain is about bridging that gap — through algorithms and systems that make large models efficient enough to actually deploy. We approach the problem from three angles. The first is inference-time acceleration via speculative decoding, where a small "draft" model proposes tokens that a larger target model verifies in parallel; building on our group's recent work on DFlash, we study how to schedule draft sizes adaptively and how to extend drafts past their training context with sliding-window attention. The second is model compression via post-training quantization, where shrinking weights to 4 bits or lower reduces memory footprint dramatically but introduces error that accumulates along long chains of thought; building on our recent work on ParoQuant, we study outlier suppression with learned pairwise rotations and co-design quantization algorithms with their inference kernels. The third is efficient VLA architectures, where we profile modern models such as π0.5 and InternVLA-A1 to identify compute-vs-memory bottlenecks, and study trade-offs between discrete (FAST tokenizer) and continuous (flow-matching) action representations on the LIBERO benchmark. The unifying thread across all three: identify the real bottleneck through careful profiling, then design an algorithmic or systems intervention that moves the Pareto frontier of speed and quality.

summer: |
  Pick the track that interests you and prepare accordingly:

  - Speculative decoding: Read the original speculative decoding paper (Leviathan et al., arXiv:2211.17192) and skim EAGLE-3, Medusa, and the DFlash repo (https://github.com/z-lab/dflash). Run a small Qwen model locally with HuggingFace transformers and make sure you understand the KV cache.

  - Quantization: Read the AWQ paper (Lin et al., arXiv:2306.00978) and the ParoQuant paper (arXiv:2511.10645), and skim the ParoQuant repo (https://github.com/z-lab/paroquant). Try running a quantized 4-bit model locally with vLLM. Make sure you understand why outliers in weights and activations cause large errors at low bit-widths.

  - Efficient VLA: Read the π0.5 paper (arXiv:2504.16054) and the FAST tokenizer paper (arXiv:2501.09747). Get LeRobot (https://github.com/huggingface/lerobot) running locally on a small policy.

  Regardless of track, brush up on PyTorch internals (autograd, torch.compile) and profiling tools (torch.profiler, Nsight Systems), and practice tracing a forward pass through an unfamiliar repo. If you want a head start, attempt the baseline measurement for your chosen track (acceptance length on MATH-500, MMLU-Pro accuracy under INT4, or an nsys profile of π0.5) and bring the numbers to our first meeting.

time: Wed 1-2 PM

modality: Zoom

style: |
  Capstone students will be integrated into my research group. Each team will be paired with a PhD student as a day-to-day technical contact, but I will personally lead the weekly section every week. I am hands-on in early Quarter 1 to ensure each team has a tractable problem and a working baseline, and progressively more hands-off as students take ownership. I expect students to read papers, debug code, and form opinions independently, but I am very available over Slack/email between meetings. The best students will treat the capstone as a real research project, not a class assignment.

seats: 8

tag: sys
---
