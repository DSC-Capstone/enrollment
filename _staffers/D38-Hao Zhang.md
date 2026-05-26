---
name: Hao Zhang

email: haz094@ucsd.edu

photo: 

website: https://haozhang.ai/

industry: false

domain: D38

title: "Efficient LLM Inference Systems: Scaling Large Language Models from Single GPU to Datacenters"

bio: | 
  Hao Zhang is an Assistant Professor in Halıcıoğlu Data Science Institute and the Department of Computer Science and Engineering at UC San Diego. Before joining UCSD, he was a postdoctoral researcher at UC Berkeley working with Ion Stoica from 2021 to 2023. He completed his Ph.D. in Computer Science at Carnegie Mellon University with Eric Xing from 2014 to 2020. During his PhD, he took a leave to work at the ML platform startup Petuum Inc from 2016 to 2021. His research lies at the intersection of machine learning and systems. His work includes FastVideo, DistServe, vLLM, Chatbot Arena, Vicuna, Alpa, Poseidon, and Petuum. His research has been recognized with a Sloan Research Fellowship (2026), a Google ML and Systems junior faculty award (2025), the Jay Lepreau Best Paper Award at OSDI'21, and an NVIDIA Pioneer Research Award at NeurIPS'17. He was nominated for MIT TR35 (China) in 2024. He joined Snowflake through acquihiring in 2023 and also co-founded the nonprofit LMSYS Org, which maintains many popular open models, evaluation platforms, and systems.

description: |
  The deployment of large language models (LLMs) is now central to modern AI infrastructure, yet inference remains constrained by GPU memory, latency, throughput, and cost. As models scale to hundreds of billions of parameters and context windows stretch to millions of tokens, naive serving strategies break down. The field has responded with a wave of systems-level innovations: PagedAttention and KV cache management (vLLM, SOSP'23), disaggregated prefill/decode serving (DistServe, OSDI'24), speculative decoding, continuous batching, KV cache offloading to CPU and SSD (Mooncake, LMCache), distributed inference across heterogeneous accelerators, and specialized scheduling for long-context and agentic workloads. This domain explores the open problems in LLM serving — how to push throughput and latency Pareto frontiers further, how to serve mixture-of-experts and reasoning models efficiently, how to handle KV cache at exabyte scale, and how to co-design model architectures with serving systems. Students will gain hands-on experience with vLLM and SGLang, profile real workloads, and propose interventions that move the state of the art.

  Suggested references:

  Kwon et al., Efficient Memory Management for Large Language Model Serving with PagedAttention, SOSP 2023 (vLLM)
  Zhong et al., DistServe: Disaggregating Prefill and Decoding for Goodput-optimized LLM Serving, OSDI 2024

summer: |
  N/A

  learning pytorch / vllm / sglang

time: Monday 2pm

modality: Zoom

ta: https://zhongyan0721.github.io/tpu-dflash/

style: |
  hands off

seats: 6

tag: sys

goal: |
  reproduce some small LLM pre training
---
