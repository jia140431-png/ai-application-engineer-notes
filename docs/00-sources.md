# 来源与覆盖范围

[返回目录](../README.md)

## 可核对的原始记录

原对话：《AI应用工程师面试题》，conversation ID：`6adb72e8-d244-83e9-9ec7-36dd7bd7648e`。这是个人对话标识，不是公开可访问资料链接。本仓库只整理学习内容，不附整段私人聊天。

通过对话读取接口取回 5 轮，接口报告没有更早页。可见内容包括：

| 记录 | 用途 | 限制 |
|---|---|---|
| 已学 5 模块、36 讲的总结 | 确定范围与数量 | 不是每一讲的大纲 |
| 模块 05 第七讲 HITL | 整理暂停、恢复、重放与审批边界 | 已去掉不可访问互动控件 |
| 模块 05 第八讲架构选型 | 整理技术分层与选型 | 是提炼重写，不是逐字复刻 |
| 用户 RAG 排查回答及反馈 | 整理诊断案例 | 不沿用主观面试评分为客观结论 |

## 内容标识

- **补充复习**：01—04 全部，以及 05 的前六单元；根据模块主题和通用原理重新组织。缺失原文，不声称还原原课。
- **原对话整理**：05 第七、八讲；保留重点、压缩示例，不保留完整逐字文本。
- **原对话复盘 + 补充**：RAG 排查案例；用明确的阶段证据替代“看见某症状就断定某组件坏了”。

待补：模块 01—04 全部原课文、05 前六讲原课文及实际标题；原始互动题、图与答题结果。未取回不代表原课未讲过。

## 参考来源

基础理论参考原始论文；阅读论文不是本资料的前置要求。

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762)：Attention 与 Transformer。
- [Retrieval-Augmented Generation](https://arxiv.org/abs/2005.11401)：检索与生成结合的研究背景。
- [ReAct](https://arxiv.org/abs/2210.03629)：推理与行动交替的研究背景。

以下官方页面于 2026-11-05 核对其概念定位，本文不提供依赖具体版本的可运行 API 示例：

- [Spring AI ChatClient](https://docs.spring.io/spring-ai/reference/api/chatclient.html)：模型交互与同步/流式调用。
- [LangGraph Interrupts](https://docs.langchain.com/oss/python/langgraph/interrupts)：中断与恢复语义。
- [MCP 简介](https://modelcontextprotocol.io/docs/getting-started/intro)：连接外部工具与数据的协议。
- [A2A 官方文档](https://a2a-protocol.org/latest/)：Agent 间互操作。

这里没有复用招聘信息、薪资结论或课程助手的能力评分。各框架的版本兼容性、完整能力和部署要求，应另外按目标环境核实。
