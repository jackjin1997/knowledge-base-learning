# knowledge-base-learning

面向 agent 开发者的 RAG / 知识库系统中文深度教程（HTML 系列，图文并茂）。

**入口：直接用浏览器打开 [`index.html`](index.html)（学习地图）**，或本地起服务：

```bash
python3 -m http.server 8931 --directory knowledge-base-learning
# → http://localhost:8931
```

## 章节

| 章 | 文件 | 内容 |
|---|---|---|
| 00 | `index.html` | 学习地图：全景图、学习路径、选型速查表 |
| 01 | `01-history.html` | RAG 演进史：三次定义漂移、2017–2026 时间线、「RAG 已死」之争 |
| 02 | `02-pipeline.html` | **★ 传统 RAG 全链路**：chunking / embedding / HNSW / hybrid+RRF / 重排 / 评估 |
| 03 | `03-parsing.html` | 文档解析与 OCR：管线派 vs VLM 派、OmniDocBench、选型决策树 |
| 04 | `04-graphrag.html` | 微软 GraphRAG 代码精读（`../graphrag`）：Leiden 社区、Map-Reduce、成本画像 |
| 05 | `05-lightrag.html` | LightRAG 代码精读（`../LightRAG`）：双层检索、存储抽象、评测争议 |
| 06 | `06-pageindex.html` | PageIndex 代码精读（`../PageIndex`）：无向量推理式树搜索 |
| 07 | `07-frontier.html` | 前沿：Self-RAG/CRAG、HippoRAG、ColPali、agentic RAG、记忆系统 |
| 08 | `08-practice.html` | 本地实战（`../gbrain` `../MiroFish` `../ragflow`）：仓库对照、RAGFlow 工程集成拆解与选型决策图 |
| 09 | `09-industry.html` | 工业界产品拆解：Manus 上下文工程、Kimi agentic RL 搜索、豆包法条场景与火山引擎知识库栈、法律垂直 RAG 对照 |
| 10 | `10-recent.html` | 2025–2026 编年：deep research 普及、RL 学检索谱系、记忆系统演化、context engineering 学科化、Agent+Wiki 专题（DeepWiki / Karpathy llm-wiki）（含 2026 上半年实时调研） |
| 11 | `11-background.html` | 自维护知识库：agentic wiki、Gwern Daydreaming、Letta 睡眠计算、Claude Dreaming——「后台认知层」+ 体系边界声明 |

样式：`assets/style.css`（全系列共享）。代码引用行号基于 2026-07 的本地仓库检出，仓库更新后行号可能漂移。
