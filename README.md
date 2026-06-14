<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:00bfbf&height=220&section=header&text=Anatoliy%20Serputov&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=Software%20Engineer%20%E2%80%A2%20LLM%20Infrastructure%20%E2%80%A2%20Inference%20Systems&descSize=16&descColor=00bfbf&descAlignY=55)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/serputov)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:serputof7@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aserputov)

</div>

## `> whoami`

Software Engineer building **LLM infrastructure at scale**. I design autonomous agent frameworks, optimize inference pipelines, and build the systems that make large language models actually work in production.

Currently architecting **LLM agent systems with Model Context Protocol (MCP)** — from code-generation compilers to root-cause analysis agents powered by Claude API. Experienced in shipping high-throughput distributed systems with ML-driven workloads.

When I'm not at work, I'm benchmarking inference engines, profiling KV cache bottlenecks, and quantizing models on Apple Metal.

---

## What I'm Building

<table>
<tr>
<td width="50%" valign="top">

### [LLM Inference Benchmark](https://github.com/aserputov/llm-inference-benchmark)
Benchmarking framework measuring inference throughput (tokens/sec), per-token latency, and memory footprint across model sizes. Covers **INT4/8-bit quantization on Apple Metal GPU**, thread-scaling analysis, and sub-linear OPS parallelization for decode vs near-linear scaling for prefill.

`Python` `llama.cpp` `Metal` `GGUF`

</td>
<td width="50%" valign="top">

### [Next-Token Prediction Engine](https://github.com/aserputov/aserputov3)
Frequency-based language model implementing core next-token prediction from scratch — n-gram statistics, vocabulary search, probability ranking. Beam-search inspired ranking algorithm that surfaces high-probability completions in O(log n) time.

`Python` `NLP` `Probability` `Beam Search`

</td>
</tr>
</table>

---

## What I'm Contributing

### 🏆 Open Source Contributions
* **[vLLM Project](https://github.com/vllm-project/vllm)**: Contributed to the distributed inference engine. Clarified aggregation semantics for the NIXL KV Cache Connector in Disaggregated Serving architectures ([PR #45607](https://github.com/vllm-project/vllm/pull/45607)).

