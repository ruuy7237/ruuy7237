<div align="center">

# Hi, I'm 雷金霖

### 我在做能真正干完活的 LLM Agent —— 任务拆解 · 工具调用 · 评测驱动

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3500&pause=1000&color=2563EB&center=true&vCenter=true&width=480&lines=Building+LLM+Agents;that+actually+finish+tasks;RAG+%2B+Tool+Calling+%2B+Eval)](https://git.io/typing-svg)

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![RAG](https://img.shields.io/badge/RAG-FF6F00?logo=postman&logoColor=white)](https://python.langchain.com/)
[![MCP](https://img.shields.io/badge/MCP-00ADD8?logo=simpleicons&logoColor=white)](https://modelcontextprotocol.io/)
[![MySQL](https://img.shields.io/badge/MySQL-00758F?logo=mysql&logoColor=white)](https://www.mysql.com/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)](https://git-scm.com/)

</div>

---

## 🧠 关于我

AI Agent 方向的开发者。比起"能不能调通"，我更关心**能不能稳定跑完、错了怎么办、怎么用数据证明它变好了** —— 这也是我把评测写进每个项目的原因。

-  **做事方式**：每个项目都从评测集开始 —— 先定义"什么算对"，再写实现，最后量化"改了哪、提升了多少"。所以我的仓库没有只有录屏的 demo，都有可复现的成绩单和失败分析。
-  **Agent**：不依赖框架手写过完整的 agent loop（规划 → 工具调用 → 结果校验 → 失败重试），理解 function calling 每个环节的坑，而不是只会拼 LangChain 的 API。
-  **RAG**：做过分块策略与混合检索（BM25 + 稠密 + RRF）的量化对比，答案带引用溯源；知道"检索没召回"往往比"模型不行"更常见。
-  **数据**：用 SQLite / Pandas 处理真实业务数据，做过中文 Text-to-SQL，包含安全护栏、执行准确率评测与错误归因。
-  **表达**：踩过的坑会写成博客，把"为什么这么设计"讲清楚 —— 文档能力和代码能力一样是工程素养。

## 🚀 精选项目

| 项目 | 做什么 | 亮点 |
| --- | --- | --- |
| [🤖 **task-agent**](https://github.com/ruuy7237/task-agent) | 手写工具调用 Agent（零框架） | 手写 plan→call→verify→retry 循环、**50 道任务评测集**、失败归因 |
| [🧠 **second-brain-rag**](https://github.com/ruuy7237/second-brain-rag) | 个人知识库问答 | BM25 + 稠密混合检索、引用溯源、**hit@5 / MRR 评测** |
| [📊 **sql-analysis-agent**](https://github.com/ruuy7237/sql-analysis-agent) | 中文 Text-to-SQL 数据分析 | 模式链接、SELECT-only 护栏、执行准确率评测、自动周报 |
| [🔌 **mcp-knowledge-server**](https://github.com/ruuy7237/mcp-knowledge-server) | 把知识库封装成 MCP 服务 | 支持 Claude Code / Cursor 通过标准协议调用 |

## ✍️ 写作

- [手写一个 Tool-Calling Agent：从 0 到 50 条任务评测](https://juejin.cn/post/7691517675235262518) — 逐层拆解 agent loop 每一步为什么这么写：参数校验、结果校验、失败重试与步数护栏
- [RAG 检索评测：hit@5 提升 18 个点我做对了什么](https://juejin.cn/post/7691517675235311670) — 分块策略与 BM25 / 稠密 / 混合检索的量化对比实验记录
- [Text-to-SQL Agent 的 5 类典型错误](https://juejin.cn/post/7691553508860117028) — 20 道中文业务题的错误归因：schema 链接、日期、聚合、护栏误伤与自修复

## 📫 联系我

- 🔥 掘金：[juejin.cn/user/93922281663914](https://juejin.cn/user/93922281663914)
- 📮 Email：2071934928@qq.com
- 💻 GitHub：就是我的作品集

---
