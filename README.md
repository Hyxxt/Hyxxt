<p align="center">
  <a href="https://huangyouxiong-10m3k3ol.maozi.io">
    <img src="https://huangyouxiong-10m3k3ol.maozi.io/img/og.png" alt="黄佑雄 · 全栈开发作品集" width="100%">
  </a>
</p>

<h1 align="center">黄佑雄 · Hyxxt</h1>

<p align="center">
  <b>全栈开发</b> · Next.js / TypeScript / Python / FastAPI / PostgreSQL<br>
  2027 届全日制大专 · 广州 · 每周可到岗 5 天
</p>

<p align="center">
  <a href="https://huangyouxiong-10m3k3ol.maozi.io"><img src="https://img.shields.io/badge/作品集-国内直连-16324a?style=flat-square" alt="作品集"></a>
  <a href="https://fde-hospital-ops.onrender.com"><img src="https://img.shields.io/badge/在线演示-医院后勤制度助手-2e7d5b?style=flat-square" alt="医院后勤制度助手"></a>
  <a href="https://claims-agent-2e93.onrender.com"><img src="https://img.shields.io/badge/在线演示-理赔通-2e7d5b?style=flat-square" alt="理赔通"></a>
  <a href="https://labelcare-desk.glacialbowl3.chatgpt.site/"><img src="https://img.shields.io/badge/在线演示-LabelCare-2e7d5b?style=flat-square" alt="LabelCare"></a>
  <a href="https://ai-quote-app.onrender.com"><img src="https://img.shields.io/badge/在线演示-AI%20报价工作台-2e7d5b?style=flat-square" alt="AI 报价工作台"></a>
</p>

---

## 我在做什么

把业务规则写进代码，让模型只负责听懂人话。算钱、判合格这类不能出错的环节交给确定性代码；大模型负责把口语、文档变成结构化信息。

- 5 个已上线项目：**医院后勤制度助手**、**AI 报价工作台**、**理赔通**、**LabelCare**、**RAG 知识库问答**
- 能独立完成前端、后端、数据库和部署；Docker Compose、Kubernetes / Helm、Prometheus 都实际跑过
- 全日制大专在读，没有正式工作经验；项目、数据和边界都写在 README 里，可以当场复现

## 精选项目

| 项目 | 形态 | 在线演示 | 源码 | 关键点 |
| --- | --- | --- | --- | --- |
| **医院后勤制度助手** | FastAPI + pgvector | [fde-hospital-ops.onrender.com](https://fde-hospital-ops.onrender.com) | [Hyxxt/fde-hospital-ops](https://github.com/Hyxxt/fde-hospital-ops) | BGE-Small-ZH ONNX 向量 + BM25 + RRF；岗位权限过滤；Docker Compose / Helm；Prometheus；Recall@3 混合 12/12 |
| **AI 报价工作台** | Next.js 全栈 | [ai-quote-app.onrender.com](https://ai-quote-app.onrender.com) | [Hyxxt/ai-quote-app](https://github.com/Hyxxt/ai-quote-app) | 口语询价 → 模型提取 JSON → 代码查价目表算钱；型号不认识直接阻断；无 Key 自动回退规则解析 |
| **理赔通** | Next.js + Agent | [claims-agent-2e93.onrender.com](https://claims-agent-2e93.onrender.com) | [Hyxxt/claims-agent](https://github.com/Hyxxt/claims-agent) | DeepSeek function calling 最多 6 轮；BM25 条款检索；免责情形明确拒赔；3 个 MCP 工具 |
| **LabelCare** | 浏览器端 AI | [labelcare-desk.glacialbowl3.chatgpt.site](https://labelcare-desk.glacialbowl3.chatgpt.site/) | — | BGE-small-zh 语义匹配 + 规则降级；本地 Qwen2.5-1.5B；21 条模拟报障评测 21/21 |
| **RAG 知识库问答** | Next.js 全栈 | [rag-kb-nr1a.onrender.com](https://rag-kb-nr1a.onrender.com) | [Hyxxt/rag-kb](https://github.com/Hyxxt/rag-kb) | 中文 bigram 倒排索引 + 自写 BM25；Top-4 片段生成带 `[n]` 引用的回答；10 题评测 10/10 |
| **AI 求职作战台** | Next.js 全栈 | [ai-job-match-8d6w.onrender.com](https://ai-job-match-8d6w.onrender.com) | [Hyxxt/ai-job-match](https://github.com/Hyxxt/ai-job-match) | JD + 简历 → 模型只做提取 → 代码算六维匹配分；技能回查简历原句；无 Key 走规则模式 |

> 演示站的价格、客户、知识库文档、JD 和简历均为虚构示例，不连接真实业务系统。Render 免费实例闲置会休眠，首次打开约 30–60 秒。

## 技术栈

<p>
  <img src="https://img.shields.io/badge/Next.js%2016-000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/React%2019-149eca?style=flat-square&logo=react&logoColor=white" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06b6d4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169e1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL + pgvector">
  <img src="https://img.shields.io/badge/SQLite-003b57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Kubernetes%20%2F%20Helm-326ce5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes / Helm">
  <img src="https://img.shields.io/badge/Prometheus-e6522c?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus">
  <img src="https://img.shields.io/badge/DeepSeek%20API-4d6bfe?style=flat-square" alt="DeepSeek API">
</p>

<p><b>AI 编程工具：</b>
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square" alt="Claude Code">
  <img src="https://img.shields.io/badge/Codex-000000?style=flat-square" alt="Codex">
</p>

## 其他项目

作品集里还有 QMS 来料异常管理案例、FluxOps CSV 双表核对、ParcelPilot 发货数据检查、澄光美妆运营台、质检报告自动整理、电商订单 RPA、公开网页采集与巡检等 21 个项目，以及课程实训中的 IT 运维实施与验收。

- 作品集：<https://huangyouxiong-10m3k3ol.maozi.io>
- 简历 PDF：<https://huangyouxiong-10m3k3ol.maozi.io/resume.pdf>

## 联系

- 邮箱：3490882124@qq.com
- 电话：18148856185
- 求职方向：全栈开发（全职）· 广州

---

<p align="center"><sub>算钱、判合格交给代码，模型只负责听懂人话。</sub></p>
