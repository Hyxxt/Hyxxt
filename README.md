<p align="center">
  <a href="https://huangyouxiong.pages.dev">
    <img src="https://huangyouxiong.pages.dev/img/og.png" alt="黄佑雄 · AI 全栈开发作品集" width="100%">
  </a>
</p>

<h1 align="center">黄佑雄 · Hyxxt</h1>

<p align="center">
  <b>AI 全栈开发</b> · Next.js / TypeScript / RAG / Python<br>
  2027 届全日制大专 · 广州 · 每周可到岗 5 天
</p>

<p align="center">
  <a href="https://huangyouxiong.pages.dev"><img src="https://img.shields.io/badge/作品集-huangyouxiong.pages.dev-16324a?style=flat-square" alt="作品集"></a>
  <a href="https://ai-quote-app.onrender.com"><img src="https://img.shields.io/badge/在线演示-AI%20报价工作台-2e7d5b?style=flat-square" alt="AI 报价工作台"></a>
  <a href="https://rag-kb-nr1a.onrender.com"><img src="https://img.shields.io/badge/在线演示-RAG%20知识库-2e7d5b?style=flat-square" alt="RAG 知识库"></a>
  <a href="https://ai-job-match-8d6w.onrender.com"><img src="https://img.shields.io/badge/在线演示-AI%20求职作战台-2e7d5b?style=flat-square" alt="AI 求职作战台"></a>
  <a href="https://ai-order-followup.onrender.com"><img src="https://img.shields.io/badge/在线演示-AI%20订单跟进-2e7d5b?style=flat-square" alt="AI 订单跟进助手"></a>
</p>

---

## 我在做什么

把业务规则写进代码，让模型只负责听懂人话。算钱、判合格这类不能出错的环节，交给确定性代码；大模型负责把口语、文档变成结构化信息。

- 四个已上线的 Next.js 全栈项目：**AI 报价工作台**、**RAG 知识库问答**、**AI 求职作战台**、**AI 订单跟进助手**
- 关注：结构化输出、降级与错误处理、检索评测、可复核的 AI 应用
- 目前是全日制大专在读，没有正式工作经验；项目、数据和边界都写在 README 里，可以当场复现

## 四个 Next.js 全栈项目

| 项目 | 在线演示 | 源码 | 关键点 |
| --- | --- | --- | --- |
| **AI 报价工作台** | [ai-quote-app.onrender.com](https://ai-quote-app.onrender.com) | [Hyxxt/ai-quote-app](https://github.com/Hyxxt/ai-quote-app) | 口语询价 → 大模型提取 JSON → 代码查价目表算钱；型号不认识直接阻断；无 Key / 超时自动回退规则解析 |
| **RAG 知识库问答** | [rag-kb-nr1a.onrender.com](https://rag-kb-nr1a.onrender.com) | [Hyxxt/rag-kb](https://github.com/Hyxxt/rag-kb) | 中文 bigram 倒排索引 + 自写 BM25；Top-4 片段生成带 `[n]` 引用的回答；资料不足拒答；10 题检索评测 10/10 |
| **AI 求职作战台** | [ai-job-match-8d6w.onrender.com](https://ai-job-match-8d6w.onrender.com) | [Hyxxt/ai-job-match](https://github.com/Hyxxt/ai-job-match) | JD + 简历 → 模型只做提取 → 代码算六维匹配分；技能必须回查简历原句；无 Key 走规则模式；高/低匹配样例 79 / 45 |
| **AI 订单跟进助手** | [ai-order-followup.onrender.com](https://ai-order-followup.onrender.com) | [Hyxxt/ai-order-followup](https://github.com/Hyxxt/ai-order-followup) | 客户口语改单 → 模型提取变更 → 规则改单重算金额；单位 / 交期风险阻断；无 Key 可跑；11 组接口冒烟 |

> 四个演示站的价目表、客户、知识库文档、JD 和简历均为虚构示例，不连接真实业务系统。Render 免费实例闲置会休眠，首次打开约 30–60 秒。AI 求职作战台和 AI 订单跟进助手同时开源，`npm run dev` 可本地复现。

## 技术栈

<p>
  <img src="https://img.shields.io/badge/Next.js%2016-000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/React%2019-149eca?style=flat-square&logo=react&logoColor=white" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06b6d4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/SQLite-003b57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Turso-4ff8d2?style=flat-square&logo=turso&logoColor=black" alt="Turso">
  <img src="https://img.shields.io/badge/Render-46e3b7?style=flat-square&logo=render&logoColor=black" alt="Render">
  <img src="https://img.shields.io/badge/DeepSeek%20API-4d6bfe?style=flat-square" alt="DeepSeek API">
  <img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white" alt="Python">
</p>

<p><b>AI 编程工具：</b>
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square" alt="Claude Code">
  <img src="https://img.shields.io/badge/Codex-000000?style=flat-square" alt="Codex">
</p>

## 其他项目

作品集里还有质检报告自动整理、服装辅料订单流水线、电商订单 RPA、公开网页采集与巡检等可运行原型，以及课程实训中的 IT 运维实施与验收。

- 作品集：<https://huangyouxiong.pages.dev>
- 简历 PDF：[huangyouxiong.pages.dev/resume.pdf](https://huangyouxiong.pages.dev/resume.pdf)

## 联系

- 邮箱：3490882124@qq.com
- 电话：18148856185
- 求职方向：AI 全栈开发（全职）· 广州

---

<p align="center"><sub>算钱、判合格交给代码，模型只负责听懂人话。</sub></p>
