# Hi, I'm 雷金霖 👋

 **I build LLM Agents that actually finish tasks — not just chat.**

CS undergrad · AI Agent / RAG / Applied LLM engineering

---

## 🛠 Tech stack

`Python` · `LLM Function Calling` · `LangChain / LlamaIndex` · `ChromaDB` · `FAISS` · `SQLite` · `Pandas` · `FastAPI` · `MCP` · `Git`

## 🎯 What I focus on

- **Agent workflow** — task decomposition, tool calling, result verification, failure recovery
- **RAG** — document parsing, chunking, hybrid retrieval, citation-grounded answers
- **Evaluation** — building task sets and eval harnesses, then analyzing *why* an agent fails
- **Data agents** — Text-to-SQL, automated reporting

> I don't trust demos. Every repo below ships with an eval set, a metrics report, and a written failure analysis.

## 📌 Featured projects

| Project | What it does | Highlights |
| --- | --- | --- |
| [**task-agent**](https://github.com/ruuy7237/task-agent) | Tool-calling agent written from scratch (no agent framework) | Hand-written plan→call→verify→retry loop, **50-task eval set**, failure taxonomy |
| [**second-brain-rag**](https://github.com/ruuy7237/second-brain-rag) | Personal knowledge base Q&A | Hybrid retrieval (BM25 + dense), citation tracing, **retrieval eval: hit@5 / MRR** |
| [**sql-analysis-agent**](https://github.com/ruuy7237/sql-analysis-agent) | Chinese Text-to-SQL data analyst | Schema linking, SELECT-only safety guard, execution accuracy eval, auto weekly report |
| [**mcp-knowledge-server**](https://github.com/ruuy7237/mcp-knowledge-server) | MCP server exposing my knowledge base | Works with Claude Code / Cursor via MCP |

## 📝 Writing

- [《手写一个 Tool-Calling Agent：从 0 到 50 条任务评测》](https://juejin.cn/) — agent loop 的每一步为什么要这么写
- [《RAG 检索评测：hit@5 提升 18 个点我做对了什么》](https://juejin.cn/) — 混合检索与分块策略的量化对比
- [《Text-to-SQL Agent 的 5 类典型错误》](https://juejin.cn/) — 20 道中文业务题的错误归因

## 📫 Contact

- Email:2071934928@qq.com

---

<!--
要点说明（自用，上传前可删）：
1. 仓库名必须与你的 GitHub 用户名完全一致，README 才会显示在个人主页。
2. 表格里的链接替换成真实仓库地址；仓库 Push 后在 Profile 页 Customize your pins 置顶这 4 个。
3. 三个 JD 都在强调“文档整理/写作”，所以这里特意加了 Writing 区块。
-->
