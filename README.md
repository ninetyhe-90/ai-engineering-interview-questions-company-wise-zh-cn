<p align="center">
    <img alt="AI 工程面试题(按公司分类)" src="https://github.com/ninetyhe-90/ai-engineering-interview-questions-company-wise/blob/main/assets/banner.png">
</p>

# AI 工程面试题(按公司分类)

> AI 工程面试题(按公司分类)——你攻克顶级 AI 公司 AI 工程面试的速查手册。
>
> 收录 35 家公司 AI 工程面试中真实出现过的题目,按公司逐一整理;凡是能找到答案的,都在题目下方附上答案链接。
>
> 这些面试题与答案对以下岗位有帮助:
>
> - AI 工程师(AI Engineer)
> - 生成式 AI 工程师(Gen AI Engineer)
> - LLM 工程师(LLM Engineer)
> - Agentic AI 工程师
> - AI Agent 工程师
> - 机器学习工程师(Machine Learning Engineer)
> - 研究工程师(Research Engineer)
> - 应用科学家(Applied Scientist)
> - 前向部署工程师(Forward Deployed Engineer)
> - AI 解决方案架构师(AI Solutions Architect)
> - AI 平台工程师(AI Platform Engineer)
> - 应用 AI 工程师(Applied AI Engineer)
> - LLM 推理与性能工程师(LLM Inference and Performance Engineer)
> - MLOps 工程师
> - LLMOps 工程师

> **关于本仓库**
>
> 本仓库是 [pallavi-shekhar/ai-engineering-interview-questions-company-wise](https://github.com/pallavi-shekhar/ai-engineering-interview-questions-company-wise) 的中文版。
>
> 当前翻译进度:**已翻译框架(简介、目录、使用说明)与「跨公司通用面试题」全部内容**;各公司的专属题目与角色/面试流程说明仍为英文,见 [README.en.md](./README.en.md)。欢迎继续补充公司部分的中文翻译。

## 目录

- [如何使用本仓库](#如何使用本仓库)
- [跨公司通用面试题](#跨公司通用面试题)
  - [LLM 内部机制与架构](#llm-内部机制与架构)
  - [推理服务与 GPU 性能](#推理服务与-gpu-性能)
  - [RAG 与检索](#rag-与检索)
  - [Agent 与工具调用](#agent-与工具调用)
  - [微调后训练与对齐](#微调后训练与对齐)
  - [评估与可观测性](#评估与可观测性)
  - [安全安保与负责任 AI](#安全安保与负责任-ai)
  - [多模态语音与音频 AI](#多模态语音与音频-ai)
  - [AI 系统设计](#ai-系统设计)
  - [编码与数据结构](#编码与数据结构)
- [前沿 AI 实验室](#前沿-ai-实验室)
  - [Anthropic](#anthropic)
  - [OpenAI](#openai)
  - [Google DeepMind and Google AI](#google-deepmind-and-google-ai)
  - [Meta (Superintelligence Labs, FAIR, Llama)](#meta-superintelligence-labs-fair-llama)
  - [xAI](#xai)
  - [Mistral AI](#mistral-ai)
  - [Cohere](#cohere)
  - [DeepSeek](#deepseek)
  - [Moonshot AI (Kimi)](#moonshot-ai-kimi)
  - [Zhipu AI (GLM)](#zhipu-ai-glm)
  - [Alibaba (Qwen)](#alibaba-qwen)
  - [Sarvam AI](#sarvam-ai)
- [大型科技公司的 AI 组织](#大型科技公司的-ai-组织)
  - [Microsoft](#microsoft)
  - [Amazon (AWS)](#amazon-aws)
  - [Apple](#apple)
  - [NVIDIA](#nvidia)
  - [Tesla](#tesla)
  - [Consumer-Scale ML Companies (Uber, Netflix, LinkedIn, Airbnb, Pinterest, Spotify)](#consumer-scale-ml-companies-uber-netflix-linkedin-airbnb-pinterest-spotify)
- [AI 基础设施与平台公司](#ai-基础设施与平台公司)
  - [Databricks](#databricks)
  - [Groq](#groq)
  - [Together AI](#together-ai)
  - [Hugging Face](#hugging-face)
  - [Scale AI](#scale-ai)
  - [Perplexity](#perplexity)
- [AI 原生应用公司](#ai-原生应用公司)
  - [Cursor (Anysphere)](#cursor-anysphere)
  - [Cognition (Devin, Windsurf)](#cognition-devin-windsurf)
  - [Sierra](#sierra)
  - [Harvey](#harvey)
  - [Glean](#glean)
  - [Character.AI](#characterai)
  - [ElevenLabs](#elevenlabs)
  - [Abridge](#abridge)
  - [Figure AI](#figure-ai)
  - [Waymo](#waymo)
- [前向部署与企业级 AI](#前向部署与企业级-ai)
  - [Palantir](#palantir)

### 由 [Outcome School](https://outcomeschool.com) 整理与维护

> Outcome School 的 AI 与机器学习课程:[AI and Machine Learning Program](https://outcomeschool.com/program/ai-and-machine-learning)

### 关注 Outcome School

- [YouTube](https://youtube.com/@OutcomeSchool)
- [X/Twitter](https://x.com/outcome_school)
- [LinkedIn](https://www.linkedin.com/company/outcomeschool)
- [GitHub](https://github.com/OutcomeSchool)

---

> **说明:我们会持续补充新的题目与答案。**
>
> 想看按主题组织的题目与答案,请见 [AI Engineering Interview Questions and Answers](https://github.com/amitshekhariitbhu/ai-engineering-interview-questions)。

---

## 如何使用本仓库

- 这里的题目都整理自公开报道的面试经历,不包含任何机密内容。面试流程总在变化,并且会因团队、级别和地区而异,因此请把每个公司的板块当作"这家公司关心什么"的地图,而不是"你一定会被问到什么"的脚本。
- 先看[跨公司通用面试题](#跨公司通用面试题)。这些是在许多公司都会反复出现的题目。每道题只列一次,并标注了会问它的公司,因此公司板块里不会重复出现。
- 然后看你的目标公司。每个公司板块都包含它覆盖的岗位、公开报道的面试流程,以及按主题分组的公司专属题目。
- 凡是已有答案的题目,答案链接就放在题目下方。我们会持续补充答案。

---

## 跨公司通用面试题

> 这些问题会在许多公司的 AI 工程面试中出现。每道题在此只列一次,并标注了会问它(或它的公司特定变体)的公司。请先吃透这些。

### LLM 内部机制与架构

- 解释缩放点积注意力(scaled dot-product attention),以及 1/sqrt(d_k) 缩放因子的作用。
  - 答案:[注意力中 √dₖ 缩放因子背后的数学](https://outcomeschool.com/blog/scaling-dot-product-attention) 及 [注意力背后的数学:Q、K、V](https://outcomeschool.com/blog/math-behind-attention-qkv)
- 什么是 KV 缓存?在大规模场景下它对显存有什么影响?请推导公式。
  - 出现于:[OpenAI](#openai)、[xAI](#xai)、[Mistral AI](#mistral-ai)、[Amazon](#amazon-aws)、[Apple](#apple)、[NVIDIA](#nvidia)、[Together AI](#together-ai)、[Character.AI](#characterai)
  - 答案:[什么是 LLM 中的 KV Cache?](https://outcomeschool.com/blog/kv-cache-in-llms) 及 [KV Cache 压缩](https://outcomeschool.com/blog/kv-cache-compression)
- 什么是多查询注意力(MQA)和分组查询注意力(GQA)?它们分别牺牲了什么?
  - 出现于:[Meta](#meta-superintelligence-labs-fair-llama)、[Mistral AI](#mistral-ai)
  - 答案:[分组查询注意力(Grouped Query Attention)](https://outcomeschool.com/blog/grouped-query-attention)
- 什么是多头潜在注意力(MLA)?DeepSeek 为什么要引入它?
  - 出现于:[DeepSeek](#deepseek)、[Moonshot AI](#moonshot-ai-kimi)
  - 答案:[KV Cache 压缩](https://outcomeschool.com/blog/kv-cache-compression)
- 解释 FlashAttention。它并没有减少 FLOPs,为什么却更快?
  - 出现于:[Together AI](#together-ai)
  - 答案:[解读 LLM 中的 Flash Attention](https://outcomeschool.com/blog/decoding-flash-attention)
- 字节对编码(Byte Pair Encoding)是如何工作的?它有哪些失效场景(数字、代码、非拉丁文字)?
  - 出现于:[Alibaba](#alibaba-qwen)、[Sarvam AI](#sarvam-ai)、[Hugging Face](#hugging-face)
  - 答案:[字节对编码](https://outcomeschool.com/blog/bpe-in-llms) 及 [大语言模型(LLM)中的分词](https://www.youtube.com/watch?v=sK2s9I84EVI)
- Transformer 中的位置编码是什么?它是如何演进的(正弦式 → 可学习 → RoPE → ALiBi)?
  - 答案:[LLM 中的位置嵌入](https://outcomeschool.substack.com/p/positional-embeddings-in-llms) 及 [RoPE(旋转位置编码)背后的数学](https://outcomeschool.com/blog/math-behind-rope-rotary-position-embedding)
- 解释 RoPE,以及位置插值 / YaRN 如何把上下文扩展到训练长度之外。
  - 出现于:[Meta](#meta-superintelligence-labs-fair-llama)、[Moonshot AI](#moonshot-ai-kimi)、[Alibaba](#alibaba-qwen)
  - 答案:[RoPE(旋转位置编码)背后的数学](https://outcomeschool.com/blog/math-behind-rope-rotary-position-embedding)
- Chinchilla 缩放定律讲了什么?它与早期关于缩放的直觉有何不同?
  - 出现于:[Anthropic](#anthropic)
- 什么是混合专家(mixture-of-experts)架构?它如何在不增加 FLOPs 的前提下扩展模型容量?
  - 出现于:[Mistral AI](#mistral-ai)、[Cohere](#cohere)、[DeepSeek](#deepseek)、[Moonshot AI](#moonshot-ai-kimi)、[Zhipu AI](#zhipu-ai-glm)、[Alibaba](#alibaba-qwen)
  - 答案:[混合专家(Mixture of Experts)详解](https://outcomeschool.com/blog/mixture-of-experts)
- 解释预训练、监督微调与偏好优化之间的区别。
  - 出现于:[Meta](#meta-superintelligence-labs-fair-llama)、[Scale AI](#scale-ai)
  - 答案:[解读 InstructGPT](https://outcomeschool.com/blog/decoding-instructgpt) 及 [基于人类反馈的强化学习(RLHF)](https://outcomeschool.com/blog/reinforcement-learning-from-human-feedback-rlhf)
- 比较贪婪解码、束搜索、top-k、top-p 与温度采样。各自在什么情况下会失效?
  - 出现于:[Google DeepMind](#google-deepmind-and-google-ai)、[Apple](#apple)、[Perplexity](#perplexity)
  - 答案:[温度如何控制 LLM 的输出?](https://outcomeschool.com/blog/how-does-temperature-control-llm-output) 及 [Top-k 与 Top-p 采样是如何工作的?](https://outcomeschool.com/blog/how-do-top-k-and-top-p-sampling-work)
- 长上下文中的"中间遗忘"(lost-in-the-middle)问题是什么?如何缓解?
  - 出现于:[Moonshot AI](#moonshot-ai-kimi)
  - 答案:[LLM 中的中间遗忘问题](https://outcomeschool.com/blog/lost-in-the-middle-problem-in-llms)
- 为什么现代 Transformer 把 LayerNorm 放在每个 block 之前?什么是 RMSNorm?
  - 答案:[RMSNorm(均方根层归一化)](https://outcomeschool.com/blog/rmsnorm-root-mean-square-layer-normalization)
- 解释 SwiGLU,以及为什么门控激活在现代 LLM 的 MLP 模块中取代了 ReLU/GELU。
  - 出现于:[Meta](#meta-superintelligence-labs-fair-llama)
  - 答案:[LLM 中的前馈网络](https://outcomeschool.com/blog/feed-forward-networks-in-llms)
- 请逐张量地讲一遍仅解码器(decoder-only)Transformer 的一次前向传播都发生了什么。
  - 出现于:[Anthropic](#anthropic)
  - 答案:[解读 Transformer 架构](https://outcomeschool.com/blog/decoding-transformer-architecture)

### 推理服务与 GPU 性能

- 解释 prefill 和 decode 两个阶段。为什么 prefill 受算力限制,而 decode 受显存带宽限制?
  - 出现于:[Moonshot AI](#moonshot-ai-kimi)、[NVIDIA](#nvidia)、[Together AI](#together-ai)
  - 答案:[Prefill 与 Decode:LLM 推理优化](https://outcomeschool.com/blog/prefill-vs-decode-llm-inference-optimization)
- 什么是连续批处理(在途批处理)?它为什么取代了静态批处理?
  - 出现于:[Anthropic](#anthropic)、[xAI](#xai)、[Mistral AI](#mistral-ai)、[NVIDIA](#nvidia)、[Together AI](#together-ai)
  - 答案:[LLM 中的连续批处理](https://outcomeschool.com/blog/continuous-batching-in-llms)
- PagedAttention 是如何工作的?它解决了 KV 缓存的什么碎片化问题?
  - 出现于:[NVIDIA](#nvidia)、[Together AI](#together-ai)
  - 答案:[LLM 中的 Paged Attention](https://outcomeschool.com/blog/paged-attention-in-llms) 及 [vLLM 是如何工作的?](https://outcomeschool.com/blog/how-does-vllm-work)
- 什么是投机解码(speculative decoding)?为什么它不会降低输出质量?什么情况下它没有帮助?
  - 出现于:[NVIDIA](#nvidia)、[Together AI](#together-ai)
  - 答案:[投机解码](https://outcomeschool.com/blog/speculative-decoding)
- 解释前缀缓存 / 提示缓存(prompt caching)。何时该用它?什么会使已缓存的前缀失效?
  - 出现于:[Moonshot AI](#moonshot-ai-kimi)、[Character.AI](#characterai)
  - 答案:[提示缓存是如何工作的?](https://outcomeschool.com/blog/how-does-prompt-caching-work)
- 在推理服务中比较 FP16、BF16、FP8、INT8、INT4 与 FP4。每往下降一档会坏在哪里?
  - 出现于:[Mistral AI](#mistral-ai)、[Apple](#apple)、[NVIDIA](#nvidia)、[Together AI](#together-ai)、[Character.AI](#characterai)
  - 答案:[模型量化是如何工作的?](https://outcomeschool.com/blog/how-does-model-quantization-work)
- 比较张量并行、流水线并行、数据并行、序列并行与专家并行。什么时候要把它们组合使用?
  - 出现于:[Google DeepMind](#google-deepmind-and-google-ai)、[Meta](#meta-superintelligence-labs-fair-llama)、[Amazon](#amazon-aws)、[NVIDIA](#nvidia)
- 估算服务一个 70B 模型所需的 GPU 显存:权重、KV 缓存、激活值、碎片。
  - 出现于:[NVIDIA](#nvidia)
  - 答案:[什么是 LLM 中的 KV Cache?](https://outcomeschool.com/blog/kv-cache-in-llms) 及 [LLM 中的 Paged Attention](https://outcomeschool.com/blog/paged-attention-in-llms)
- 什么是 TTFT、TPOT、ITL 和吞吐?它们之间如何相互权衡?
  - 出现于:[Microsoft](#microsoft)、[Apple](#apple)、[Perplexity](#perplexity)
  - 答案:[Prefill 与 Decode:LLM 推理优化](https://outcomeschool.com/blog/prefill-vs-decode-llm-inference-optimization) 及 [LLM 中的首 token 延迟问题](https://www.youtube.com/watch?v=XD8DD4cEHu0)
- 做一下 roofline 计算:一张 H100 在 batch size 为 1 时,为一个 70B 模型每秒能产生多少 token?
  - 出现于:[NVIDIA](#nvidia)、[Together AI](#together-ai)
  - 答案:[Prefill 与 Decode:LLM 推理优化](https://outcomeschool.com/blog/prefill-vs-decode-llm-inference-optimization)
- 什么情况下你会选择 vLLM、SGLang、TensorRT-LLM 还是自研栈?
  - 出现于:[NVIDIA](#nvidia)、[Together AI](#together-ai)
  - 答案:[vLLM 是如何工作的?](https://outcomeschool.com/blog/how-does-vllm-work)、[SGLang 是如何工作的?](https://outcomeschool.com/blog/how-does-sglang-work) 及 [TensorRT-LLM 是如何工作的?](https://outcomeschool.com/blog/how-does-tensorrt-llm-work)
- 你如何把 LLM 服务成本降低 10 倍?请列举所有可用的手段并排序。
  - 出现于:[Microsoft](#microsoft)、[Amazon](#amazon-aws)、[NVIDIA](#nvidia)、[Cursor](#cursor-anysphere)
  - 答案:见视频 [LLM 推理优化](https://www.youtube.com/watch?v=jV2sCj4lHYk) 及 [LLM 推理优化](https://outcomeschool.com/blog/llm-inference-optimization)
- 一次没有改模型的发布之后,p99 延迟翻倍了。请讲讲你的排查思路。
  - 出现于:[OpenAI](#openai)、[Amazon](#amazon-aws)、[Databricks](#databricks)、[Perplexity](#perplexity)
- 什么是分块预填充(chunked prefill)?为什么它能改善混合流量下的尾延迟?
- 解释预填充/解码分离(prefill/decode disaggregation)式服务,以及它何时才划算。
  - 出现于:[Moonshot AI](#moonshot-ai-kimi)、[Groq](#groq)
  - 答案:[LLM 推理中的 Prefill-Decode 分离](https://outcomeschool.com/blog/prefill-decode-disaggregation)

### RAG 与检索

- 对大型技术文档语料,你会采用什么分块策略?为什么?
  - 出现于:[Glean](#glean)
  - 答案:[RAG 的分块策略](https://outcomeschool.com/blog/chunking-strategies-for-rag)
- 如何在稀疏检索器(BM25)和稠密检索器之间做选择?什么时候两者都需要?
  - 出现于:[Microsoft](#microsoft)、[Perplexity](#perplexity)、[Glean](#glean)
  - 答案:[混合检索(Hybrid Search)是如何工作的?](https://outcomeschool.com/blog/how-does-hybrid-search-work)
- 什么是重排序器(reranker)?何时该用它?交叉编码器(cross-encoder)的代价是什么?
  - 出现于:[Cohere](#cohere)、[Microsoft](#microsoft)、[Perplexity](#perplexity)
  - 答案:[Reranker 是如何工作的?](https://outcomeschool.com/blog/how-does-a-reranker-work)
- 你会如何评估 RAG 流水线的质量:分别评估检索和生成?
  - 出现于:[Cohere](#cohere)
  - 答案:[LLM 评估](https://outcomeschool.com/blog/llm-evaluation)
- 什么是 HyDE(假设文档嵌入)?它在什么时候优于标准的稠密检索?
  - 答案:[HyDE 在 RAG 中是如何工作的?](https://outcomeschool.com/blog/how-does-hyde-work)
- Agentic RAG 与标准 RAG 有何不同?什么时候值得引入这份额外复杂度?
  - 答案:[Agentic RAG](https://outcomeschool.com/blog/agentic-rag)
- 嵌入检索中的语义漂移(semantic drift)由什么引起?如何检测?
  - 出现于:[Cohere](#cohere)
- 设计一个权限感知的检索:用户绝不能看到其在源系统中无权访问的内容。
  - 出现于:[Microsoft](#microsoft)、[Databricks](#databricks)、[Glean](#glean)、[Palantir](#palantir)
- 比较 HNSW、IVF-PQ 与扁平(flat)索引。如何选择?recall@k 会带来多少延迟代价?
  - 答案:[近似最近邻(ANN)搜索是如何工作的?](https://outcomeschool.com/blog/how-does-approximate-nearest-neighbor-ann-search-work) 及 [向量数据库是如何工作的?](https://outcomeschool.com/blog/how-does-a-vector-database-work)
- 如何在检索流水线中处理表格、图和多栏 PDF?
- 当底层语料持续变化时,如何保持索引新鲜?
  - 出现于:[Perplexity](#perplexity)、[Cursor](#cursor-anysphere)
- 如何把生成答案中的每一项主张都归因到具体的检索片段?
  - 出现于:[Perplexity](#perplexity)、[Harvey](#harvey)、[Abridge](#abridge)

### Agent 与工具调用

- 解释 ReAct 模式,以及相比单纯的思维链(chain-of-thought)它解决了什么。
  - 答案:[ReAct Agent](https://outcomeschool.com/blog/react-agent) 及 [思维链(CoT)提示是如何工作的?](https://outcomeschool.com/blog/how-does-chain-of-thought-prompting-work)
- 在 agent 循环中,你如何处理工具调用错误、超时和重试?
  - 出现于:[OpenAI](#openai)、[Cognition](#cognition-devin-windsurf)
  - 答案:[AI Agent 循环](https://outcomeschool.com/blog/ai-agent-loop)
- 结构化输出与函数调用(function calling)有什么区别?
  - 出现于:[Mistral AI](#mistral-ai)、[Apple](#apple)
  - 答案:[LLM 中的函数调用是如何工作的?](https://outcomeschool.com/blog/how-does-function-calling-work-in-llms)
- 什么是 MCP(Model Context Protocol)?它与传统函数调用有何不同?
  - 出现于:[Microsoft](#microsoft)
  - 答案:见视频 [AI 工程详解:LLM、RAG、MCP、Agent、微调、量化](https://www.youtube.com/watch?v=lnfWvX66FUk) 及 [什么是 MCP(Model Context Protocol)?](https://outcomeschool.com/blog/what-is-mcp-model-context-protocol)
- 工具多到什么程度算太多?如何设计 LLM 真的能正确使用的工具 schema?
  - 出现于:[Anthropic](#anthropic)、[Cognition](#cognition-devin-windsurf)
  - 答案:见视频 [AI 工程详解:LLM、RAG、MCP、Agent、微调、量化](https://www.youtube.com/watch?v=lnfWvX66FUk)
- 多 agent 编排是如何工作的?它在什么时候会崩溃?
  - 出现于:[Cognition](#cognition-devin-windsurf)
  - 答案:[多 Agent 系统](https://outcomeschool.com/blog/multi-agent-systems) 及 [AI 编排](https://outcomeschool.com/blog/ai-orchestration)
- 为长时间运行的 agent 设计记忆:存什么、存在哪里、如何检索?
  - 出现于:[Anthropic](#anthropic)
  - 答案:[AI Agent 记忆](https://outcomeschool.com/blog/ai-agent-memory)
- agent 如何决定是调用工具还是用自己的知识回答?
  - 答案:[LLM 中的函数调用是如何工作的?](https://outcomeschool.com/blog/how-does-function-calling-work-in-llms)
- 什么能让 agent 循环正确终止?如何限制成本和步数?
  - 答案:[AI Agent 循环](https://outcomeschool.com/blog/ai-agent-loop) 及 [修复 AI agent 中的死循环](https://www.linkedin.com/posts/pallavi-shekhar_ai-aiagents-machinelearning-share-7440257380707364864-5Ycc)
- 在生产系统中,如何让 agent 的动作可逆,或至少可审计?
  - 出现于:[Palantir](#palantir)
- 为一个会执行有后果动作的 agent 设计人在环路(human-in-the-loop)审批。
  - 出现于:[OpenAI](#openai)、[Palantir](#palantir)
- 你的 agent 跑久了之后跑偏了,还很自信地在做错的事。请诊断。

### 微调后训练与对齐

- 完整讲一遍 RLHF:奖励模型、策略优化、KL 惩罚。
  - 答案:[基于人类反馈的强化学习(RLHF)](https://outcomeschool.com/blog/reinforcement-learning-from-human-feedback-rlhf) 及 [近端策略优化(PPO)](https://outcomeschool.com/blog/proximal-policy-optimization-ppo)
- 什么是 DPO?为什么它在许多实验室取代了基于 PPO 的 RLHF?什么时候在线 RL 仍然更好?
  - 出现于:[Hugging Face](#hugging-face)、[Scale AI](#scale-ai)
  - 答案:[直接偏好优化(DPO)](https://outcomeschool.com/blog/direct-preference-optimization-dpo)
- 解释 GRPO,以及为什么在大规模下去掉价值网络很重要。
  - 出现于:[DeepSeek](#deepseek)
  - 答案:[组相对策略优化(GRPO)](https://outcomeschool.com/blog/group-relative-policy-optimization-grpo)
- 从数学上解释 LoRA 的分解。它为什么有效?如何选择秩 r?
  - 答案:[LoRA——LLM 的低秩适配](https://outcomeschool.com/blog/lora-low-rank-adaptation-of-llms)
- QLoRA 是如何实现显存降低的?它的量化权衡是什么?
  - 出现于:[Hugging Face](#hugging-face)
  - 答案:见视频 [AI 工程详解:LLM、RAG、MCP、Agent、微调、量化](https://www.youtube.com/watch?v=lnfWvX66FUk) 及 [模型量化是如何工作的?](https://outcomeschool.com/blog/how-does-model-quantization-work)
- 比较 LoRA、prefix tuning、prompt tuning 与全量微调。分别何时选用?
  - 出现于:[Sarvam AI](#sarvam-ai)、[Apple](#apple)
  - 答案:[微调是如何工作的?](https://outcomeschool.com/blog/how-does-fine-tuning-work) 及 [Prefix Tuning 是如何工作的?](https://outcomeschool.com/blog/how-does-prefix-tuning-work)
- 什么是灾难性遗忘?微调时如何缓解?
  - 出现于:[Mistral AI](#mistral-ai)
  - 答案:[LLM 中的持续学习](https://outcomeschool.com/blog/continual-learning-in-llms)
- 提示、RAG 还是微调:请给出你的决策框架,并附上成本与延迟。
  - 出现于:[OpenAI](#openai)、[Mistral AI](#mistral-ai)、[Cohere](#cohere)、[Microsoft](#microsoft)、[Databricks](#databricks)、[Glean](#glean)
  - 答案:见视频 [AI 工程详解:LLM、RAG、MCP、Agent、微调、量化](https://www.youtube.com/watch?v=lnfWvX66FUk)
- 做一下用 Adam 以 bf16 全量微调一个 7B 模型的 GPU 显存计算。再算用 LoRA 的情况。
  - 出现于:[Mistral AI](#mistral-ai)、[Hugging Face](#hugging-face)
- 什么是 RLVR(可验证奖励的 RL)?它在哪些方面优于学习式奖励模型?
  - 出现于:[Zhipu AI](#zhipu-ai-glm)、[Alibaba](#alibaba-qwen)、[Sarvam AI](#sarvam-ai)、[Scale AI](#scale-ai)
  - 答案:[组相对策略优化(GRPO)](https://outcomeschool.com/blog/group-relative-policy-optimization-grpo)
- 解释 RLHF 中的奖励黑客(reward hacking),以及各实验室如何应对。
  - 出现于:[Scale AI](#scale-ai)
  - 答案:[基于人类反馈的强化学习(RLHF)](https://outcomeschool.com/blog/reinforcement-learning-from-human-feedback-rlhf)
- 什么是蒸馏?如何用大模型构建一个强的小模型?
  - 出现于:[Alibaba](#alibaba-qwen)
  - 答案:[知识蒸馏是如何工作的?](https://outcomeschool.com/blog/how-does-knowledge-distillation-work)

### 评估与可观测性

- 设计一个 LLM-as-judge 评估。它有哪些已知偏差?如何校正?
  - 出现于:[Perplexity](#perplexity)
  - 答案:[LLM 作为裁判(LLM as a Judge)](https://outcomeschool.com/blog/llm-as-a-judge)
- 当没有标注真值、专家又很贵时,如何构建评估集?
  - 出现于:[Cohere](#cohere)、[Harvey](#harvey)
- 在生产 RAG 系统中,如何检测和度量幻觉?
  - 出现于:[Anthropic](#anthropic)、[OpenAI](#openai)、[Cursor](#cursor-anysphere)
- 设计一个回归门禁,用来决定 prompt 或模型改动能否上线。
  - 出现于:[Anthropic](#anthropic)
- 为什么基准分数提升了,用户却说系统变差了?请列举原因。
  - 出现于:[Cognition](#cognition-devin-windsurf)
- 什么是基准污染(benchmark contamination)?如何防范?
  - 出现于:[Zhipu AI](#zhipu-ai-glm)、[Alibaba](#alibaba-qwen)、[Scale AI](#scale-ai)
  - 答案:[LLM 评估](https://outcomeschool.com/blog/llm-evaluation)
- 生产级 LLM 系统需要哪些可观测性:traces、spans、成本、反馈?
  - 答案:[AI Agent 可观测性](https://outcomeschool.com/blog/ai-agent-observability)
- 在生产中如何管理 prompt 版本和回滚?
- 设计在线评估:你会记录什么、采样什么、对什么做 A/B?
  - 出现于:[Perplexity](#perplexity)
- 如何评估一个 agent(相对于单次模型回答)?
  - 出现于:[Moonshot AI](#moonshot-ai-kimi)、[Zhipu AI](#zhipu-ai-glm)、[Scale AI](#scale-ai)、[Cognition](#cognition-devin-windsurf)
  - 答案:[AI Agent 评估](https://outcomeschool.com/blog/ai-agent-evaluation)

### 安全安保与负责任 AI

- 什么是提示注入(直接与间接)?你的分层防御是什么?
  - 出现于:[Anthropic](#anthropic)、[OpenAI](#openai)、[Microsoft](#microsoft)、[Sierra](#sierra)
  - 答案:[LLM 中的提示注入](https://outcomeschool.com/blog/prompt-injection-in-llms)
- 讲讲 LLM 应用的 OWASP Top 10,以及哪些在实践中真的会造成危害。
- 越狱(jailbreaking)和对抗性提示(adversarial prompting)有什么区别?
  - 答案:[LLM 中的提示注入](https://outcomeschool.com/blog/prompt-injection-in-llms)
- 为面向消费者的助手设计护栏。输入过滤、输出过滤,还是两者都用?
  - 出现于:[Sierra](#sierra)、[Character.AI](#characterai)
  - 答案:[LLM 护栏是如何工作的?](https://outcomeschool.com/blog/how-do-llm-guardrails-work)
- 什么是 Constitutional AI?它与 RLHF 有何不同?什么是 RLAIF?
  - 出现于:[Anthropic](#anthropic)
- 如何防止一个拥有工具访问权限的 agent 通过恶意网页外泄数据?
  - 出现于:[OpenAI](#openai)
  - 答案:[LLM 中的提示注入](https://outcomeschool.com/blog/prompt-injection-in-llms)
- 如何在 prompt、日志和训练数据中处理 PII(个人身份信息)?
  - 出现于:[Abridge](#abridge)
- 什么是机制可解释性(mechanistic interpretability)?实验室为什么投入它?
- 你会如何审计一个已部署模型在不同用户群体上的差异化表现?
  - 出现于:[Microsoft](#microsoft)
- 为一个即将发布的模型设计红队计划。
  - 答案:[LLM 评估](https://outcomeschool.com/blog/llm-evaluation)

### 多模态语音与音频 AI

- 视觉语言模型如何把图像送进 LLM:投影器、交叉注意力,还是原生 token?
  - 出现于:[Meta](#meta-superintelligence-labs-fair-llama)、[Alibaba](#alibaba-qwen)
  - 答案:[多模态 AI](https://outcomeschool.com/blog/multimodal-ai) 及 [解读视觉 Transformer(ViT)](https://outcomeschool.com/blog/decoding-vision-transformer-vit)
- 从图像到视频,会有什么变化?
  - 出现于:[Meta](#meta-superintelligence-labs-fair-llama)
- 为实时语音 agent 做延迟预算:VAD、ASR、LLM、TTS、网络。时间花在哪里?
  - 出现于:[Sarvam AI](#sarvam-ai)、[ElevenLabs](#elevenlabs)
  - 答案:[设计一个实时语音 AI Agent](https://outcomeschool.com/blog/design-a-real-time-voice-ai-agent)
- 为语音 agent 设计打断(barge-in)处理。
  - 出现于:[ElevenLabs](#elevenlabs)
  - 答案:[设计一个实时语音 AI Agent](https://outcomeschool.com/blog/design-a-real-time-voice-ai-agent)
- 级联式 ASR+LLM+TTS 与原生语音到语音:请为双方辩护。
  - 出现于:[ElevenLabs](#elevenlabs)
  - 答案:[设计一个实时语音 AI Agent](https://outcomeschool.com/blog/design-a-real-time-voice-ai-agent)
- 在没有唯一正确答案的情况下,如何评估 ASR 质量(超越 WER)和 TTS 质量?
  - 出现于:[ElevenLabs](#elevenlabs)
- 在生产 ASR 系统中如何处理语码转换(code-switching)和口音?
  - 出现于:[Sarvam AI](#sarvam-ai)、[Abridge](#abridge)
- 解释流式 TTS 的分块与抖动缓冲(jitter buffer)大小设置。
  - 出现于:[ElevenLabs](#elevenlabs)
- 设计一个说话人分离(diarisation)系统,并解释如何归属角色,而不只是聚类。
  - 出现于:[Abridge](#abridge)
- 如何在一个索引中对图像、视频和文本构建多模态检索?
  - 答案:[图像嵌入是如何工作的?](https://outcomeschool.com/blog/how-do-image-embeddings-work)

### AI 系统设计

- 设计一个面向 1000 万文档、带每用户权限的企业级 RAG 助手。
  - 出现于:[OpenAI](#openai)、[Microsoft](#microsoft)、[Amazon](#amazon-aws)、[Databricks](#databricks)、[Scale AI](#scale-ai)
- 设计一个代码助手:仓库索引、上下文组装、编辑应用、评估。
  - 出现于:[Cursor](#cursor-anysphere)
  - 答案:[Cursor 是如何工作的?](https://outcomeschool.com/blog/how-does-cursor-work) 及 [Claude Code 是如何工作的?](https://outcomeschool.com/blog/how-does-claude-code-work)
- 设计一个能执行真实动作、并可升级到人工的客服 agent。
  - 出现于:[Consumer-Scale ML Companies](#consumer-scale-ml-companies-uber-netflix-linkedin-airbnb-pinterest-spotify)、[Sierra](#sierra)
- 为大型商品目录设计语义搜索。
  - 出现于:[Character.AI](#characterai)
  - 答案:[语义搜索是如何工作的?](https://outcomeschool.com/blog/how-does-semantic-search-work)
- 设计一个结合分类器与 LLM 的内容审核系统。
  - 出现于:[Meta](#meta-superintelligence-labs-fair-llama)
- 设计一个文档智能流水线:输入扫描版 PDF,输出结构化字段,规模 1000 万文档。
  - 出现于:[Palantir](#palantir)
- 为拥有数千张表的数仓设计一个 Text-to-SQL 系统。
  - 出现于:[Databricks](#databricks)、[Palantir](#palantir)
- 设计一个会议助手:录音、说话人分离、摘要、待办事项、集成。
  - 出现于:[Microsoft](#microsoft)
- 设计一个 LLM 网关:跨供应商路由、故障转移、缓存、预算与限流。
  - 出现于:[Perplexity](#perplexity)、[Palantir](#palantir)
  - 答案:[LLM 路由](https://outcomeschool.com/blog/llm-routing) 及 [语义缓存是如何工作的?](https://outcomeschool.com/blog/how-does-semantic-caching-work)
- 为面向数亿用户的消费级聊天助手设计服务栈。
  - 出现于:[Anthropic](#anthropic)、[OpenAI](#openai)、[Google DeepMind](#google-deepmind-and-google-ai)、[Meta](#meta-superintelligence-labs-fair-llama)、[xAI](#xai)
  - 答案:[深入 ChatGPT:按下回车之后会发生什么](https://outcomeschool.substack.com/p/inside-chatgpt-what-happens-after) 及 [LLM 推理优化](https://outcomeschool.com/blog/llm-inference-optimization)

### 编码与数据结构

- 用 NumPy 或 PyTorch 从零实现带因果掩码的缩放点积注意力。
  - 出现于:[Anthropic](#anthropic)、[Google DeepMind](#google-deepmind-and-google-ai)、[Amazon](#amazon-aws)
  - 答案:[注意力背后的数学:Q、K、V](https://outcomeschool.com/blog/math-behind-attention-qkv) 及 [注意力中的因果掩码](https://outcomeschool.com/blog/causal-masking-in-attention)
- 实现多头注意力,然后把它改造成分组查询注意力。
  - 出现于:[Google DeepMind](#google-deepmind-and-google-ai)、[Mistral AI](#mistral-ai)、[Alibaba](#alibaba-qwen)
  - 答案:[Transformer 中的多头注意力](https://outcomeschool.com/blog/multi-head-attention-in-transformers) 及 [分组查询注意力](https://outcomeschool.com/blog/grouped-query-attention)
- 实现一个 KV 缓存和单步解码。
  - 出现于:[Moonshot AI](#moonshot-ai-kimi)
  - 答案:[什么是 LLM 中的 KV Cache?](https://outcomeschool.com/blog/kv-cache-in-llms)
- 从零实现 BPE 的训练与编码。
  - 答案:[字节对编码](https://outcomeschool.com/blog/bpe-in-llms)
- 在 logits 向量上实现 top-k、top-p 与温度采样。
  - 出现于:[Google DeepMind](#google-deepmind-and-google-ai)、[Apple](#apple)
  - 答案:[温度如何控制 LLM 的输出?](https://outcomeschool.com/blog/how-does-temperature-control-llm-output) 及 [Top-k 与 Top-p 采样是如何工作的?](https://outcomeschool.com/blog/how-do-top-k-and-top-p-sampling-work)
- 实现 O(1) get/put 的 LRU 缓存,然后加上 TTL。
  - 出现于:[OpenAI](#openai)、[xAI](#xai)、[Alibaba](#alibaba-qwen)
- 实现一个令牌桶限流器,然后让它分布式化。
  - 出现于:[Anthropic](#anthropic)、[OpenAI](#openai)、[xAI](#xai)、[Cohere](#cohere)
- 写一个针对 API 的异步批处理器,支持并发限制、带抖动的重试和错误隔离。
  - 出现于:[Anthropic](#anthropic)、[Perplexity](#perplexity)
- 写一个流式 SSE/JSON 解析器,能处理任意分块边界。
  - 出现于:[Cohere](#cohere)
  - 答案:[Token 流式输出是如何工作的?](https://outcomeschool.com/blog/how-does-token-streaming-work)
- 实现一个带重叠、且绝不切断语义单元的文本分块器。
  - 出现于:[Harvey](#harvey)
  - 答案:[RAG 的分块策略](https://outcomeschool.com/blog/chunking-strategies-for-rag)
- 在嵌入上实现余弦相似度检索,然后解释为什么你最终不会直接上线它。
  - 答案:[向量数据库是如何工作的?](https://outcomeschool.com/blog/how-does-a-vector-database-work)
- 实现一个最小 agent 循环,包含工具分发、错误处理和步数预算。
  - 出现于:[Cognition](#cognition-devin-windsurf)
  - 答案:[AI Agent 循环](https://outcomeschool.com/blog/ai-agent-loop)

---

## 前沿 AI 实验室

> 以下各公司的岗位覆盖、公开面试流程与公司专属题目,目前仍为英文,见 [README.en.md](./README.en.md)。中文翻译进行中。

### Anthropic

- 中文版:[待翻译](./README.en.md#anthropic)

### OpenAI

- 中文版:[待翻译](./README.en.md#openai)

### Google DeepMind and Google AI

- 中文版:[待翻译](./README.en.md#google-deepmind-and-google-ai)

### Meta (Superintelligence Labs, FAIR, Llama)

- 中文版:[待翻译](./README.en.md#meta-superintelligence-labs-fair-llama)

### xAI

- 中文版:[待翻译](./README.en.md#xai)

### Mistral AI

- 中文版:[待翻译](./README.en.md#mistral-ai)

### Cohere

- 中文版:[待翻译](./README.en.md#cohere)

### DeepSeek

- 中文版:[待翻译](./README.en.md#deepseek)

### Moonshot AI (Kimi)

- 中文版:[待翻译](./README.en.md#moonshot-ai-kimi)

### Zhipu AI (GLM)

- 中文版:[待翻译](./README.en.md#zhipu-ai-glm)

### Alibaba (Qwen)

- 中文版:[待翻译](./README.en.md#alibaba-qwen)

### Sarvam AI

- 中文版:[待翻译](./README.en.md#sarvam-ai)

## 大型科技公司的 AI 组织

### Microsoft

- 中文版:[待翻译](./README.en.md#microsoft)

### Amazon (AWS)

- 中文版:[待翻译](./README.en.md#amazon-aws)

### Apple

- 中文版:[待翻译](./README.en.md#apple)

### NVIDIA

- 中文版:[待翻译](./README.en.md#nvidia)

### Tesla

- 中文版:[待翻译](./README.en.md#tesla)

### Consumer-Scale ML Companies (Uber, Netflix, LinkedIn, Airbnb, Pinterest, Spotify)

- 中文版:[待翻译](./README.en.md#consumer-scale-ml-companies-uber-netflix-linkedin-airbnb-pinterest-spotify)

## AI 基础设施与平台公司

### Databricks

- 中文版:[待翻译](./README.en.md#databricks)

### Groq

- 中文版:[待翻译](./README.en.md#groq)

### Together AI

- 中文版:[待翻译](./README.en.md#together-ai)

### Hugging Face

- 中文版:[待翻译](./README.en.md#hugging-face)

### Scale AI

- 中文版:[待翻译](./README.en.md#scale-ai)

### Perplexity

- 中文版:[待翻译](./README.en.md#perplexity)

## AI 原生应用公司

### Cursor (Anysphere)

- 中文版:[待翻译](./README.en.md#cursor-anysphere)

### Cognition (Devin, Windsurf)

- 中文版:[待翻译](./README.en.md#cognition-devin-windsurf)

### Sierra

- 中文版:[待翻译](./README.en.md#sierra)

### Harvey

- 中文版:[待翻译](./README.en.md#harvey)

### Glean

- 中文版:[待翻译](./README.en.md#glean)

### Character.AI

- 中文版:[待翻译](./README.en.md#characterai)

### ElevenLabs

- 中文版:[待翻译](./README.en.md#elevenlabs)

### Abridge

- 中文版:[待翻译](./README.en.md#abridge)

### Figure AI

- 中文版:[待翻译](./README.en.md#figure-ai)

### Waymo

- 中文版:[待翻译](./README.en.md#waymo)

## 前向部署与企业级 AI

### Palantir

- 中文版:[待翻译](./README.en.md#palantir)

---

## 致谢与许可

- 英文原版:[pallavi-shekhar/ai-engineering-interview-questions-company-wise](https://github.com/pallavi-shekhar/ai-engineering-interview-questions-company-wise),由 [Outcome School](https://outcomeschool.com) 整理与维护。
- 本仓库遵循 [Apache License 2.0](./LICENSE)。
