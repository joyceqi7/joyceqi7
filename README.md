# 张琪 

上海理工大学系统科学硕士在读，求职方向是 AI 应用开发和 Agent 开发。

- **大模型应用**：主导大模型舆情分析系统上线，负责 Prompt 设计、结构化输出校验、知识库注入和成本控制。
- **Agent 开发**：参与移动端 AI 智能体平台的 AI Skill 设计、Agent 开发和多模型工作流编排。
- **工程基础**：熟悉 Python、FastAPI、Docker，做过幂等支付和订阅回调，日常用 Codex、Claude Code 开发。

## 项目

### [Sailson AI 工作台](https://github.com/joyceqi7/sailson-ai) · AI 舆情与竞品监控平台

Sailson 内部多部门协作的 AI 工作台，我参与了平台开发。用通义千问做 Facebook 评论的分类和情感分析，用 Apify 抓取 TikTok 数据做竞品监控和报表，管理 KOL 名单并批量发信建联、用 AI 识别回信里的报价，按部门分配权限并统计 API 成本。

`Python` `Flask` `PostgreSQL` `通义千问` `Apify` `FastAPI` `React`

### [PUBG Social Hub](https://github.com/joyceqi7/pubg-social-hub) · 游戏社媒分析平台

Sailson 为 PUBG MOBILE 官号运营团队开发的社媒分析平台。我参与了平台开发，其中 AI 舆情模块由我主要完成：每天采集五个平台官号的新增评论，用 DeepSeek 做翻译、分类、情感判断和风险识别，生成每条结论都能追溯到原评论的日报。

`Python` `FastAPI` `DeepSeek API` `Apify` `Next.js` `Docker`

### [safety-web](https://github.com/joyceqi7/safety-web) · 事故报告风险图分析平台

用 DeepSeek 把事故调查报告抽取成风险节点和关系图，再用六种 GATv2 图神经网络模型做节点筛查。后端是 FastAPI 和 PyTorch Geometric，前端是中文分析工作台，已部署到阿里云。

`Python` `FastAPI` `PyTorch Geometric` `DeepSeek API` `Docker`

### [SailReels](https://github.com/joyceqi7/sailreels) · TikTok 短剧小程序

TikTok Minis 短剧小程序。我是核心开发，负责登录、Beans 支付、订阅状态机、激励广告防刷和埋点链路，前后端都有参与。

`Python` `FastAPI` `PostgreSQL` `Redis` `Celery` `React`

### [TikTok 代理商中台](https://github.com/joyceqi7/tt-bc-admin) · 广告代理商业务中台

TikTok 一级代理商的开户、充值、钱包和报表中台。我是支付模块的主要完成人，负责统一支付网关、幂等资金账本和退款审核。

`Java` `Spring Boot` `MyBatis-Plus` `MySQL` `Redis` `Vue 3`

### [TT Shop 履约系统](https://github.com/joyceqi7/tt-shop-fulfillment) · 虚拟商品自动发码

TikTok Shop 美区虚拟商品的自动发码履约系统：Webhook 验签后幂等入库，arq 队列编排发货，卡密库用 SKIP LOCKED 取码，另有兜底对账、死信重试和告警。

`Python` `FastAPI` `SQLAlchemy` `Redis` `arq`

## 研究

硕士课题是职业事故风险传播网络的关键路径识别与稳健干预：用大模型把非结构化事故报告转成可追溯至原文的风险传播网络，再做传播仿真和预算约束下的稳健干预。

## 联系

2234328287hmz@gmail.com
