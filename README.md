# 张琪 

上海理工大学系统科学硕士在读，求职方向是 AI 应用开发和 Agent 开发。

- **大模型应用**：主导大模型舆情分析系统上线，负责 Prompt 设计、结构化输出校验、知识库注入和成本控制。
- **Agent 开发**：参与移动端 AI 智能体平台的 AI Skill 设计、Agent 开发和多模型工作流编排。
- **工程基础**：熟悉 Python、FastAPI、Docker，做过幂等支付和订阅回调，日常用 Codex、Claude Code 开发。

## 项目

### [PUBG Social Hub · AI 舆情模块](https://github.com/joyceqi7/pubg-social-hub-sentiment)

Sailson 实习项目，我是舆情模块的主要完成人。每天采集五个平台官号的新增评论，用 DeepSeek 做翻译、分类、情感判断和风险识别，生成每条结论都能追溯到原评论的日报。我做了结构化输出校验、游戏术语知识库、证据约束、缓存与预算控制和独立容器部署。

`Python` `FastAPI` `DeepSeek API` `Apify` `Next.js` `Docker`

### [safety-web](https://github.com/joyceqi7/safety-web) · 事故报告风险图分析平台

用 DeepSeek 把事故调查报告抽取成风险节点和关系图，再用六种 GATv2 图神经网络模型做节点筛查。后端是 FastAPI 和 PyTorch Geometric，前端是中文分析工作台，已部署到阿里云。

`Python` `FastAPI` `PyTorch Geometric` `DeepSeek API` `Docker`

### [daily-report-bot](https://github.com/joyceqi7/daily-report-bot) · 游戏社媒热点早报

每天抓取 Reddit、Google News 和 YouTube Shorts 的素材，交给 Gemini 写成趋势拆解和脚本建议，生成 HTML 邮件发出，由 GitHub Actions 定时运行。

`Python` `Gemini API` `GitHub Actions`

## 其他实习项目

代码归 Sailson 所有，没有公开，这里只写我负责的部分。

| 项目 | 我负责的部分 | 技术 |
| --- | --- | --- |
| SailReels · TikTok 短剧小程序 | 核心开发。登录、支付与订阅状态机、激励广告防刷、埋点去重 | FastAPI、PostgreSQL、Redis、Celery、React |
| TikTok 代理商中台 | 支付模块主要完成人。统一支付网关、幂等资金账本、退款审核 | Java、Spring Boot、MySQL、Redis、Vue 3 |

## 研究

硕士课题是职业事故风险传播网络的关键路径识别与稳健干预：用大模型把非结构化事故报告转成可追溯至原文的风险传播网络，再做传播仿真和预算约束下的稳健干预。

## 联系

2234328287hmz@gmail.com
