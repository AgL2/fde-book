# 《FDE：AI 时代的落地工程师》

> **Forward Deployed Engineer: The Engineer Who Ships AI to the Real World**
>
> 从完全零基础到专家的 FDE（前沿部署工程师）系统教程 —— 像一本书一样完整，像一本实战手册一样好用。

[![Book Status](https://img.shields.io/badge/status-写作中-orange)]()
[![Chapters](https://img.shields.io/badge/chapters-18-blue)]()
[![License](https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)]()

---

## 📖 这本书讲什么

**FDE（Forward Deployed Engineer，前沿部署工程师）** 是当下 AI 行业最火热的复合型岗位：常驻客户现场，既懂技术又懂业务，负责把大模型能力落地为可用的生产系统，并交付可验证的业务结果。

- OpenAI 官方称其为弥合 **"部署鸿沟（Deployment Gap）"** 的关键角色
- a16z 称其为 **"创业公司里最热的岗位"**
- 工信部已将 FDE 写入国家部委文件；领英数据显示 FDE 新增岗位两年增长 **42 倍**
- 国内成熟 FDE 年薪普遍 **60-120 万元**，前沿实验室资深 FDE 中位薪酬 **48.5 万美元**

这本书面向**完全零基础**的读者，不需要你事先懂大模型，也不需要你有交付经验。我们会从"FDE 是什么"讲起，一路走到你能独立完成一次 30 天的企业级 AI 交付。

## ✍️ 写作风格

- 参照 O'Reilly《Hands-On》系列：**每章都有可运行的代码、可复现的案例、章末习题**
- 每章附 **"知识点卡"**：一张卡片浓缩本章核心，方便复习
- 每章附 **"一线故事"**：来自 Palantir、OpenAI、Anthropic、商汤、阿里云等公开案例
- 全书中文写作，技术术语首次出现时给出英文原文

## 📚 完整目录

### 第一篇 · 认知篇：什么是 FDE

- [第 1 章 FDE 是什么：从 Palantir 阿富汗战场到 OpenAI 部署鸿沟](./chapters/part-01-cognition/ch01.md)
- [第 2 章 FDE 不是什么：与驻场工程师、交付顾问、AI 工程师的本质区别](./chapters/part-01-cognition/ch02.md)
- [第 3 章 为什么是现在：MIT 95% 报告、a16z 判断与产业趋势](./chapters/part-01-cognition/ch03.md)

### 第二篇 · 技术篇：FDE 的武器库

- [第 4 章 大模型基础：API、上下文、微调与推理](./chapters/part-02-tech/ch04.md)
- [第 5 章 Prompt Engineering 与 Agent 范式](./chapters/part-02-tech/ch05.md)
- [第 6 章 Agent 编排框架：LangGraph / Dify / n8n / CrewAI](./chapters/part-02-tech/ch06.md)
- [第 7 章 MCP 协议与工具生态：从零写一个 MCP Server](./chapters/part-02-tech/ch07.md)
- [第 8 章 RAG 与企业知识库：RAGFlow、向量库、文档解析](./chapters/part-02-tech/ch08.md)
- [第 9 章 私有化部署与安全：Docker/K8s、权限、审计与回滚](./chapters/part-02-tech/ch09.md)
- [第 10 章 评估（Evals）：让系统"敢上线"的最后一公里](./chapters/part-02-tech/ch10.md)

### 第三篇 · 方法论篇：交付的艺术

- [第 11 章 需求考古学：把"我们想要点 AI"翻译成可交付目标](./chapters/part-03-methodology/ch11.md)
- [第 12 章 OpenAI 四原则：从结果出发、让成功可复制](./chapters/part-03-methodology/ch12.md)
- [第 13 章 商汤"123 法则"与 30 天上线节奏](./chapters/part-03-methodology/ch13.md)
- [第 14 章 沉淀与反哺：从定制代码到通用 harness](./chapters/part-03-methodology/ch14.md)

### 第四篇 · 实战篇：三个完整项目

- [第 15 章 智能客服：RAG + 语音，eval 从 60% 到 90%](./chapters/part-04-projects/ch15.md)
- [第 16 章 精准运营 Agent：对接存量系统与权限治理](./chapters/part-04-projects/ch16.md)
- [第 17 章 内部效率工具：OpenAI Codex 案例复刻](./chapters/part-04-projects/ch17.md)

### 第五篇 · 成长篇：职业跃迁

- [第 18 章 简历、作品集与面试：从 40 万到百万的路径](./chapters/part-05-growth/ch18.md)

> 完整版目录（含状态标记）另见 [SUMMARY.md](./SUMMARY.md)

## 🗺️ 阅读路线

```
零基础读者      → 顺序阅读 1→18（每章 4-6 小时，含实战练习）
有工程背景      → 快速浏览第 1-3 章 → 精读 7/10/11/12 → 直接做第四篇项目
在职转型者      → 第 1/2/3 章 + 第 11 章 + 第 18 章，判断转型路径
团队培训负责人  → 按周计划使用：认知篇 1 周，技术篇 4 周，方法论 2 周，实战 3 周
```

## 🛠️ 环境准备

- Python 3.10+ / Node.js 20+
- 一个主流大模型 API Key（OpenAI / Anthropic / 国内任意模型服务均可）
- Docker（第四篇实战需要）

各章正文内嵌完整示例代码与章末练习，配套独立 `examples/` 代码库将另行发布。

## 🤝 如何参与

- 发现错误或建议补充 → 欢迎 Issue / PR（见 [CONTRIBUTING.md](./CONTRIBUTING.md)）
- 一线 FDE 从业者 → 欢迎在"一线故事"板块分享你的经历（匿名可选）
- 翻译志愿者 → 英文版规划中，可先开 Issue 认领章节

## 📜 版权

本书采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh) 许可：署名、非商业、相同方式共享。代码示例采用 [MIT License](./LICENSE)。

> 注：本教程正在写作中，计划出版实体书。GitHub 版将保持开源，欢迎 Star ⭐ 关注更新。
