# 10. References

> Official documentation first, reputable secondary sources second. **Always prefer the official source** — this list is a starting point and links/numbers change over time.

[← Previous: Concepts Deep Dive](09-concepts-deep-dive.md) · [Back to README →](../README.md)

---

## 10.1 Official model documentation & cards

| Provider | Where to verify models, context, pricing, licenses |
| --- | --- |
| **OpenAI** | [platform.openai.com/docs/models](https://platform.openai.com/docs/models) · [openai.com/api/pricing](https://openai.com/api/pricing) |
| **Anthropic (Claude)** | [docs.claude.com/en/docs/about-claude/models](https://docs.claude.com/en/docs/about-claude/models) · [anthropic.com/pricing](https://www.anthropic.com/pricing) |
| **Google (Gemini)** | [ai.google.dev/gemini-api/docs/models](https://ai.google.dev/gemini-api/docs/models) · [deepmind.google/models/gemini](https://deepmind.google/models/gemini/) |
| **xAI (Grok)** | [docs.x.ai](https://docs.x.ai/) · [x.ai](https://x.ai/) |
| **Meta (Llama)** | [llama.com](https://www.llama.com/) · [ai.meta.com/blog](https://ai.meta.com/blog/) |
| **Alibaba (Qwen)** | [qwenlm.github.io](https://qwenlm.github.io/) · [huggingface.co/Qwen](https://huggingface.co/Qwen) |
| **DeepSeek** | [api-docs.deepseek.com](https://api-docs.deepseek.com/) · [huggingface.co/deepseek-ai](https://huggingface.co/deepseek-ai) |
| **Mistral AI** | [docs.mistral.ai](https://docs.mistral.ai/) · [mistral.ai/news](https://mistral.ai/news/) |
| **NVIDIA (Nemotron)** | [developer.nvidia.com/nemotron](https://developer.nvidia.com/nemotron) · [github.com/NVIDIA-NeMo/Nemotron](https://github.com/NVIDIA-NeMo/Nemotron) |
| **Microsoft (Phi)** | [azure.microsoft.com/products/phi](https://azure.microsoft.com/en-us/products/phi/) · [huggingface.co/microsoft](https://huggingface.co/microsoft) |
| **IBM (Granite)** | [ibm.com/granite](https://www.ibm.com/granite) · [huggingface.co/ibm-granite](https://huggingface.co/ibm-granite) |
| **AI2 (OLMo)** | [allenai.org/olmo](https://allenai.org/olmo) · [huggingface.co/allenai](https://huggingface.co/allenai) |
| **Cohere (Command)** | [docs.cohere.com](https://docs.cohere.com/) · [cohere.com/command](https://cohere.com/command) |

---

## 10.2 Standards & concepts

| Topic | Source |
| --- | --- |
| **MCP (Model Context Protocol)** | [modelcontextprotocol.io](https://modelcontextprotocol.io/) · [Anthropic MCP announcement](https://www.anthropic.com/news/model-context-protocol) |
| **Transformer architecture** | ["Attention Is All You Need" (2017)](https://arxiv.org/abs/1706.03762) |
| **RAG (original paper)** | [Lewis et al., 2020](https://arxiv.org/abs/2005.11401) |
| **LoRA (efficient fine-tuning)** | [Hu et al., 2021](https://arxiv.org/abs/2106.09685) |
| **Scaling laws** | [Kaplan et al., 2020](https://arxiv.org/abs/2001.08361) · [Chinchilla, 2022](https://arxiv.org/abs/2203.15556) |

---

## 10.3 Benchmarks & leaderboards

| Benchmark | Source |
| --- | --- |
| **SWE-bench (Verified / Pro)** | [swebench.com](https://www.swebench.com/) |
| **Chatbot Arena (LMArena)** | [lmarena.ai](https://lmarena.ai/) |
| **GPQA** | [arxiv.org/abs/2311.12022](https://arxiv.org/abs/2311.12022) |
| **Humanity's Last Exam** | [agi.safe.ai](https://agi.safe.ai/) |
| **MMLU / MMLU-Pro** | [arxiv.org/abs/2009.03300](https://arxiv.org/abs/2009.03300) |
| **MMMU (multimodal)** | [mmmu-benchmark.github.io](https://mmmu-benchmark.github.io/) |
| **Artificial Analysis (aggregator)** | [artificialanalysis.ai](https://artificialanalysis.ai/) |
| **LLM-Stats (aggregator)** | [llm-stats.com](https://llm-stats.com/) |

> ⚠️ Aggregators are convenient but secondary. Cross-check against official model cards, and remember the [benchmark caveats](08-benchmarks.md#81-why-benchmarks-exist-and-why-to-be-skeptical).

---

## 10.4 Tools for running models locally

| Tool | Use | Link |
| --- | --- | --- |
| **Ollama** | Easiest local model runner | [ollama.com](https://ollama.com/) |
| **LM Studio** | Desktop GUI for local models | [lmstudio.ai](https://lmstudio.ai/) |
| **llama.cpp** | Efficient CPU/GPU inference (GGUF) | [github.com/ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) |
| **vLLM** | High-throughput serving | [github.com/vllm-project/vllm](https://github.com/vllm-project/vllm) |
| **Hugging Face** | Model hub + libraries | [huggingface.co](https://huggingface.co/) |

---

## 10.5 A note on sourcing & accuracy

This repository was compiled from official documentation and reputable secondary reporting current to **June 2026**. Because the field changes weekly:

- **Numbers are approximate** and rounded where vendors are vague.
- **Pricing, context windows, and availability** change frequently and vary by region and tier (some models face **regional/export-control restrictions**).
- **Benchmarks** vary by harness, settings, and date — treat all scores as directional.

Found something out of date? **[Contributions and corrections are welcome.](../CONTRIBUTING.md)**

---

[← Previous: Concepts Deep Dive](09-concepts-deep-dive.md) · [Back to README →](../README.md)
