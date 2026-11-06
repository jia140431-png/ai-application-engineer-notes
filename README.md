# AI 应用工程师学习笔记

面向有后端背景、以原理扫盲和面试复习为主的中文资料。不要求完成编码项目。

## 阅读边界

本资料覆盖用户确认学完的五个模块（6 + 6 + 8 + 8 + 8 = 36 讲），**不是逐字讲义**。初版为复习提纲；现在依据用户提供的分享对话逐批扩充。

截至 2026-11-07，模块 04 与模块 05 共 16 讲已根据取回的课程正文整理为独立文档。第一批完成 05.06—05.08，第二批补齐 05.01—05.05，第三批完成模块 04 八讲。原课内容与新增解释分别标记；课程中的代码和项目验收建议按用户“先扫盲、暂缓实战”的要求改为原理说明与纸上复习，不代表已完成实践。

模块 01—03 的 20 个复习单元目前仍是初版提纲，尚未按原课重做。已通过原聊天向前加载保存其大部分材料，后续将核对缺段并分批整理。
模块 06、07 不在本次已学范围内。文中评估、观测、幂等等内容服务于前五模块的工程理解，不表示完成了 LLMOps 专项课程。学习完成度也不等于岗位胜任度；面试必须区分理解、设计与亲手实施。

## 第三批：模块 04

- [04.01 Agent 的本质与 Workflow](docs/module-04/01-agent-workflow.md)
- [04.02 ReAct](docs/module-04/02-react.md)
- [04.03 Planning 与任务分解](docs/module-04/03-planning.md)
- [04.04 Tool Engineering](docs/module-04/04-tool-engineering.md)
- [04.05 Memory 与 Context Engineering](docs/module-04/05-memory-context.md)
- [04.06 Human-in-the-loop 与可靠执行](docs/module-04/06-hitl-reliability.md)
- [04.07 安全与效果评估](docs/module-04/07-security-evaluation.md)
- [04.08 生产级 Agent 系统设计](docs/module-04/08-production-design.md)

## 已完成的模块 05 深入整理

- [05.01 Spring AI 与 Agent 框架入门](docs/module-05/01-spring-ai-introduction.md)：模型与 Java 工具闭环、可信身份、设备调查证据边界。
- [05.02 调用链与工具循环](docs/module-05/02-tool-calling-internals.md)：Advisor 顺序、递归子链、模型与工具调用计数。
- [05.03 State、Memory 与 Checkpoint](docs/module-05/03-state-memory-checkpoint.md)：任务恢复、事件日志、标识关系与崩溃窗口。
- [05.04 LangGraph 图编排](docs/module-05/04-langgraph.md)：Node、Edge、Reducer、Super-step、Command 与 Send。
- [05.05 MCP 底层机制](docs/module-05/05-mcp.md)：协议角色、传输、版本、能力发现与授权边界。
- [05.06 Multi-Agent 多智能体协作原理](docs/module-05/06-multi-agent.md)：四种模式、会议协调、A2A 对象、交接契约、冲突与评估。
- [05.07 Human-in-the-loop 在 Agent 框架中的实现原理](docs/module-05/07-human-in-the-loop.md)：中断恢复、节点重放、父子任务、审批与幂等、原课测验。
- [05.08 Agent 技术架构全景与框架选型](docs/module-05/08-architecture-selection.md)：四个选型维度、企业消息案例、业务与执行状态、系统设计问答。
- [分批补充进度](docs/09-expansion-progress.md)：哪些已有正文、哪些仍待原始资料。

## 目录

| 模块 | 复习单元 | 笔记 |
|---|---:|---|
| 01 大模型基础原理 | 6 | [进入](docs/01-foundations.md) |
| 02 模型 API 与 Prompt | 6 | [进入](docs/02-api-prompt.md) |
| 03 RAG 检索增强生成 | 8 | [进入](docs/03-rag.md) |
| 04 Agent 与工具调用 | 8 | [进入](docs/04-agent-tools.md) |
| 05 Agent 框架与编排原理 | 8 | [进入](docs/05-orchestration.md) |

- [来源、覆盖范围与待补清单](docs/00-sources.md)
- [术语与技术对比](docs/06-glossary-comparisons.md)
- [面试自测与参考答案](docs/07-interview.md)
- [RAG 故障排查案例](docs/08-rag-diagnosis.md)

## 怎么复习

第一轮：按模块阅读，能画出模型生成、RAG、工具循环和审批恢复四条链路。

第二轮：合上笔记回答每个单元的问题，再用模块末尾的答案检查概念边界。

第三轮：按面试题进行 2 分钟口述。用“原理 → 取舍 → 失败场景 → 验证方法”组织答案。可以纸上推演，不需要为了复习新建编码项目。

## 维护约定

每次补充写清日期、来源与适用版本；框架接口、协议版本、模型价格和上下文限制以实际部署版本官方文档为准。不要把模拟案例、计划功能或对话助手的评价写成本人项目业绩。

初版日期：2026-11-05；最近补充：2026-11-07。图解使用 Mermaid，可在 GitHub 阅读。
