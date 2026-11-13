---
layout: default
title: "Horizon Summary: 2026-11-14 (ZH)"
date: 2026-11-14
lang: zh
---

# Horizon 每日速递 - 2026-11-14

> 从原始资讯中去重并归纳合并出 9 条高价值核心情报。

---

**AI 创作者雷达**
1. [DeepSeek 开放全家桶应用 API](#item-ai-creator-1) ⭐️ 7.5/10
2. [Claude Code 2.1.323 新增实验性 Code Mode](#item-ai-creator-2) ⭐️ 7.0/10
3. [OpenAI 发布 ChatGPT Wallet：agent 可在用户批准下完成购买](#item-ai-creator-3) ⭐️ 6.5/10
4. [Seedance 2.5 Flash 与 Kling 4.0 Flash 低价档对比待核实](#item-ai-creator-4) ⭐️ 6.5/10
5. [HackerNoon 统计 2212 条爆款 AI 提示词的共性](#item-ai-creator-5) ⭐️ 6.5/10
6. [openJiuwen 发布 RSI 原生 AgentOS，细节待披露](#item-ai-creator-6) ⭐️ 6.5/10
7. [开源生命科学模型 Fx-Bio-1031 宣称盲测超越 GPT-6-Astra 与 Opus-5](#item-ai-creator-7) ⭐️ 6.5/10
8. [Reddit 用户称其 Claude 工具链被新模型改造成本地 DeepSeek harness](#item-ai-creator-8) ⭐️ 6.5/10
9. [OpenAI 据称在 Daybreak 安全套件中把 AI Agent 渗透测试与自动修复配对](#item-ai-creator-9) ⭐️ 6.5/10

---

## AI 创作者雷达

<a id="item-ai-creator-1"></a>
### [DeepSeek 开放全家桶应用 API](https://mp.weixin.qq.com/s/78KBHc4-4N5b2vfL9SkutQ) ⭐️ 7.5/10

DeepSeek 宣布开放“全家桶应用 API”：开发者在原有 API 中开启对应参数，即可获得深度思考搜索、文件输入、阅读链接、语音等对话能力，服务端自动完成工具调用与上下文拼接。V4.1-Flash 模型已在三个接口支持；Search、Fetch、OCR、ASR、TTS 可单独调用。官方同时开源了可导入历史对话的前端 Demo，并给出体验地址。具体参数细节、各接口规格与实测效果仍待核实。

telegram · zaihuapd · 11月13日 14:27

**「为何值得关注」** 此次变化在于 DeepSeek 把搜索、文件、链接阅读、语音等能力以参数开关形式并入原有 API，并开源可本地部署网页端的前端 Demo；对开发者的实际影响尚待实测验证。

**「内容角度」** 可做角度：从“开启参数即获得工具调用与上下文拼接”这一设计出发，梳理 DeepSeek 全家桶 API 的接入方式与可单独调用的 Search、Fetch、OCR、ASR、TTS 接口，并说明官方前端 Demo 的本地部署路径，同时标注参数细节与实测效果仍待核实。

**标签**: `#\#DeepSeek`, `#\#AI应用开发`, `#\#API实操`, `#\#开源工具`, `#\#AI效率工具`

---

<a id="item-ai-creator-2"></a>
### [Claude Code 2.1.323 新增实验性 Code Mode](https://code.claude.com/docs/en/changelog) ⭐️ 7.0/10

Claude Code 于 11 月 12 日发布 2.1.323 版本，新增实验性 Code Mode，允许 Claude 以 JavaScript 调用工具，并可由组织层面关闭。同版本加强插件管理：声明的版本范围不匹配的插件将不被安装或更新，plugin validate 新增对 TypeScript 钩子的类型检查；此外还扩展了 .docx 文档上传与 30 秒钩子心跳等改进。

telegram · zaihuapd · 11月13日 03:47

**「为何值得关注」** 这是 Claude Code 在工具调用方式上的实验性变化，且提供了组织级关闭开关，说明官方在推进的同时保留了管控手段；插件版本校验与钩子类型检查则属于对现有插件生态的收紧。这些改动已随版本发布，但 Code Mode 的实际效果与稳定性尚未在材料中体现。

**「内容角度」** 可做角度：梳理 2.1.323 中 Code Mode 的定位——让 Claude 用 JavaScript 调用工具、组织可关闭——并对照同版本的插件版本校验与 TypeScript 钩子类型检查，说明这次更新在“放开调用方式”与“收紧插件管理”两个方向上的具体变化。

**标签**: `#\#ClaudeCode`, `#\#AI编程工具`, `#\#CodeMode`, `#\#插件管理`, `#\#AI提效`

📌 **同日该 AI 其他重要动态汇总**：
- **Reddit 用户称用 Claude Code 自动调优 AI Agent 并开源**：r/ClaudeAI 一条帖子称，作者因厌倦手动调优 AI Agent，改为让 Claude Code 自动完成调优并将成果开源；目前仅有标题，调优对象、实现步骤、仓库地址与效果均无法核实。[原题](https://news.google.com/rss/articles/CBMioAFBVV95cUxPakJmVkEzd09MeDRpTXhOV09HemdFWEYxSTZ4UGY3UTktRnR1OXBUTHV6dzVxaG05MjBMOE9VRmswWmFMY1hlU0NUWksydmRwd1ZtcHBQSnFWU2NzYlZLeHRUeTEyemx1b2FMRngtWmFOaVNQb3JoU2hQbldQMXE0S1ladl9qcjVvR1owdlhNN1pTUHB6YTJ4QjZPLVBTSHNY?oc=5)（rss · Reddit - r/ClaudeAI · 11月13日 19:28）
- **Reddit 用户称其 Claude 工具链被新模型改造成本地 DeepSeek harness**：发帖者称 2 月至 7 月搭建的“legal harness”在 Opus 5.5 与 Fable 5.2 出现后被改造成 100% 本地 DeepSeek harness，并为 2018 年 V100 显卡编写自定义 GPU kernel、称仓库已公开；材料仅一行标题，无正文与仓库链接。[原题](https://news.google.com/rss/articles/CBMioAFBVV95cUxQRGxFTmhxcXlrd1pCN0p6OUFqZnVGcVhIWTVNV2tZeFl3dTdlaFFvWHFjYzVBUjlOQlRPeWRqY2t6MF9XTkZZLXF0ODVURjlEVG1hN1EwUkwwSDBZaXpPWVdYUmllMG1OcF9ZdWhYdVdoeHpGMVZKcjZmeXNTTEhkNXR5T29POURZRXNpUDR1Q1ZQXzlpQ3FEVHdGZnFQZzhP?oc=5)（rss · Reddit - r/ClaudeAI · 11月12日 23:33）

---

<a id="item-ai-creator-3"></a>
### [OpenAI 发布 ChatGPT Wallet：agent 可在用户批准下完成购买](https://openai.com/index/introducing-chatgpt-wallet) ⭐️ 6.5/10

OpenAI 官方发布 ChatGPT Wallet，称其为一种安全方式，让 ChatGPT Work、Codex 和 dots 中的 agent 在用户批准下完成购买，并沿用现有卡片保护。目前官方仅给出这一句功能说明，具体实现步骤、可用范围、额度限制与实际效果均未披露，有待核实。

rss · OpenAI News \(官方动态\) · 11月13日 15:00

**「为何值得注意」** 这是 OpenAI 首次把支付能力明确接入 ChatGPT Work、Codex 和 dots 的 agent 场景，意味着 agent 从“建议”走向“代为执行交易”的一步；但官方尚未说明上线时间、地区与风控细节，实际影响仍不确定。

**「内容角度」** 可做角度：梳理“用户批准 + 沿用现有卡片保护”这一设计，讨论 agent 代付在授权边界、误购责任和撤销机制上留下的待解问题，并明确区分官方已说明与尚未披露的部分。

**标签**: `#\#ChatGPT`, `#\#AIAgent`, `#\#AI支付`, `#\#OpenAI动态`, `#\#效率工具`

📌 **同日该 AI 其他重要动态汇总**：
- **OpenAI 据称在 Daybreak 安全套件中把 AI Agent 渗透测试与自动修复配对**：Reddit r/ChatGPT 一条简讯标题称，OpenAI 在名为 Daybreak 的安全套件中把 AI Agent 渗透测试与自动修复功能配对；仅有标题，无版本号、发布时间、价格、限制或效果数据，功能范围与实现方式待核实。[原题](https://news.google.com/rss/articles/CBMinwFBVV95cUxNYVRoS3NFT3lsZnhFT1B2YVQwMzE3UEhZSHFteFBKc0ZwVWFXUkU1SGhCRmtUa0J0ODhvN1l6dDR2Slo5Y2pqQzE2MFdwV0J2ajJaSWgxbXVBTC12SXh6WDRhMjhLM1FqX04zSUJOTzZNWTZITXpkREdOYmRpT1VtdGVtVjc0Q2xCdHdyTElHSVFYUEFPTDF3NGFoUzY1VnM?oc=5)（rss · Reddit - r/ChatGPT · 11月13日 11:10）

---

<a id="item-ai-creator-4"></a>
### [Seedance 2.5 Flash 与 Kling 4.0 Flash 低价档对比待核实](https://news.google.com/rss/articles/CBMid0FVX3lxTE1ad0NSWUZaRllwTXhsbHhLNzJmMndVSTE4QU5saWk4VjlMSEJ2OU1TWV91cTlnY0I2WllqXzBValdWLUFOMkNabWVVNUxKeUhJSnJZd0p1cVNqLVNiWktTZkdRNnk3R2NqVE1vbFVqenB6c0YyY2dn?oc=5) ⭐️ 6.5/10

OrcaRouter 发布了一篇标题为《Seedance 2.5 Flash vs Kling 4.0 Flash: Which Cheap Tier Is Actually Cheaper》的对比文章，声称比较两款 AI 视频生成模型低价档位的实际成本。目前可获取的材料仅有标题与来源，没有正文摘要，也没有具体价格、额度、版本参数或实测数据，因此“哪个更便宜”的结论尚无法核实。受影响的主要是关注 AI 视频生成成本、考虑选用低价档位的创作者与团队。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月13日 05:59

**「内容角度」** 可做角度：以“低价档到底便宜在哪”为问题，先列出对比一款视频模型成本时需要核对的维度（单价、额度、分辨率与时长限制、失败重试成本），再说明这篇对比文章目前只给出标题、缺少可验证数据，提醒读者不要仅凭标题下结论。

**标签**: `#\#AI视频生成`, `#\#Seedance`, `#\#可灵Kling`, `#\#成本对比`, `#\#AI短剧`

---

<a id="item-ai-creator-5"></a>
### [HackerNoon 统计 2212 条爆款 AI 提示词的共性](https://news.google.com/rss/articles/CBMilAFBVV95cUxNSXpoemZIaHMwMklkc29ibzZ5SUpYOHpNaU15TnI2NWpJcm1fUDB2SVozN2tsZUYxcnVxQTVFVGFuNGlxclYyQmR5a1NnSHd5b012aGhLUVlSeEZiLWJQcFRWWkdLS0RTUUpncGV3VmRJUFZlQkJ4SmtIa0Y5U3hvb0JFaXV0RG12Q2R0UlFUb0VzSWlM?oc=5) ⭐️ 6.5/10

HackerNoon 发表了一篇题为《I Counted What 2,212 Viral AI Video and Image Prompts Have in Common》的文章，称其统计了 2212 条爆款 AI 视频与图像提示词的共同特征。目前可获取的材料只有标题和来源，文章的具体统计口径、样本来源、结论以及发布时间之外的细节均未披露，相关说法尚待核实。受影响的主要是关注 AI 视频与图像创作、提示词写法的内容创作者。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月13日 01:35

**「内容角度」** 可做角度：以“2212 条样本的统计结论是否可复现”为线索，先说明文章标题给出的样本量与主题，再指出目前缺少统计方法和结论细节，提醒读者区分“作者自述的统计”与可验证的规律。

**标签**: `#\#AI视频`, `#\#提示词工程`, `#\#AI绘画`, `#\#内容创作`, `#\#爆款拆解`

---

<a id="item-ai-creator-6"></a>
### [openJiuwen 发布 RSI 原生 AgentOS，细节待披露](https://www.qbitai.com/2026/11/509653.html) ⭐️ 6.5/10

openJiuwen 于 2026 年 11 月 13 日发布号称“RSI 原生”的 AgentOS，官方导语称“想要什么功能，让 Agent 自己开发”，暗示 Agent 可自行开发所需功能并持续迭代。目前公开材料仅有标题与这一句导语，未给出具体功能参数、版本号、开源仓库地址或实操步骤，实际能力与效果均待核实。受影响人群为关注 AI Agent 开发平台与智能体迭代方式的开发者。

rss · 量子位 QbitAI \(国内AI前沿与应用\) · 11月13日 06:54

**「为何值得注意」** AgentOS 与“Agent 自我开发、持续迭代”是当前智能体赛道的关注方向，此次发布提供了新的产品宣称；但除标题与导语外尚无技术细节或第三方验证，宣称能否落地仍不确定。

**「内容角度」** 可做角度：以“一句导语能说明什么”为线索，梳理 openJiuwen 此次发布中可确认的信息与缺失的关键项（功能边界、实现方式、是否开源、如何验证迭代效果），把它作为观察 AgentOS 类产品宣称与落地差距的样本。

**标签**: `#\#AIAgent`, `#\#AgentOS`, `#\#openJiuwen`, `#\#智能体开发`, `#\#AI前沿`

---

<a id="item-ai-creator-7"></a>
### [开源生命科学模型 Fx-Bio-1031 宣称盲测超越 GPT-6-Astra 与 Opus-5](https://www.qbitai.com/2026/11/509663.html) ⭐️ 6.5/10

量子位 RSS 条目称，无界前沿开源生命科学模型 Fx-Bio-1031，并在高难度盲测中超越 GPT-6-Astra 与 Opus-5，同时支持本地部署、数据不出域。目前可核实的只有标题与一句导语，具体基准测试名称、评测设置、模型参数与开源许可均未披露，"超越"结论尚待原始评测材料验证。受影响的主要是关注生命科学 AI 落地、对数据合规与私有化部署有要求的团队。

rss · 量子位 QbitAI \(国内AI前沿与应用\) · 11月13日 07:06

**「内容角度」** 可做角度：把"盲测超越两大闭源模型"当作待验证的宣称来处理，先梳理这条消息目前公开了哪些信息、缺哪些关键证据（基准、评测方、参数规模、开源协议），再讨论生命科学场景下"本地部署、数据不出域"为何会成为选型关注点。

**标签**: `#\#AI前沿`, `#\#开源模型`, `#\#生命科学AI`, `#\#本地部署`, `#\#AI工具`

---

<a id="item-ai-creator-8"></a>
### [Reddit 用户称其 Claude 工具链被新模型改造成本地 DeepSeek harness](https://news.google.com/rss/articles/CBMioAFBVV95cUxQRGxFTmhxcXlrd1pCN0p6OUFqZnVGcVhIWTVNV2tZeFl3dTdlaFFvWHFjYzVBUjlOQlRPeWRqY2t6MF9XTkZZLXF0ODVURjlEVG1hN1EwUkwwSDBZaXpPWVdYUmllMG1OcF9ZdWhYdVdoeHpGMVZKcjZmeXNTTEhkNXR5T29POURZRXNpUDR1Q1ZQXzlpQ3FEVHdGZnFQZzhP?oc=5) ⭐️ 6.5/10

一位 Reddit 用户（r/ClaudeAI）发帖称，自己从 2 月到 7 月搭建了一套让 Claude 更可预测的“legal harness”，并称在 Opus 5.5 和 Fable 5.2 出现后，这套工具被改造成 100% 本地的 DeepSeek harness，还为 2018 年的 V100 显卡编写了自定义 GPU kernel，并称仓库已公开。目前材料只有这一行标题，没有正文、实现细节、仓库链接或开源许可信息，模型名称与硬件效果均无法核实。

rss · Reddit - r/ClaudeAI \(长文本与生产力实操\) · 11月12日 23:33

**「为何值得注意」** 帖子把“让模型更可预测”的工具链与本地化部署、旧显卡适配放在同一条叙事里，这类工作流话题在 Claude 用户社区中较受关注。但标题所述的新模型改造与 kernel 效果目前只是发帖者自述，尚无独立证据。

**「内容角度」** 可做角度：以“一条只有标题、没有正文和仓库链接的 Reddit 自述”为样本，讨论如何核实这类“工具链被新模型自动改造并手写 GPU kernel”的说法——需要哪些可验证材料（仓库地址、许可、复现步骤、基准数据），以及为什么仅有标题时不宜直接当作事实转述。

**标签**: `#\#Claude`, `#\#本地部署`, `#\#AI工作流`, `#\#开源项目`, `#\#GPU`

---

<a id="item-ai-creator-9"></a>
### [OpenAI 据称在 Daybreak 安全套件中把 AI Agent 渗透测试与自动修复配对](https://news.google.com/rss/articles/CBMinwFBVV95cUxNYVRoS3NFT3lsZnhFT1B2YVQwMzE3UEhZSHFteFBKc0ZwVWFXUkU1SGhCRmtUa0J0ODhvN1l6dDR2Slo5Y2pqQzE2MFdwV0J2ajJaSWgxbXVBTC12SXh6WDRhMjhLM1FqX04zSUJOTzZNWTZITXpkREdOYmRpT1VtdGVtVjc0Q2xCdHdyTElHSVFYUEFPTDF3NGFoUzY1VnM?oc=5) ⭐️ 6.5/10

一条来自 Reddit r/ChatGPT 的简讯标题称，OpenAI 在名为 Daybreak 的安全套件中，将 AI Agent 渗透测试与自动修复功能配对。目前可获取的信息只有标题，没有正文摘要、版本号、发布时间、价格、使用限制或效果数据，因此具体功能范围、实现方式和实际效果均待核实。可能受影响的是关注 AI Agent 在安全测试与自动化修复场景落地的开发者和安全从业者。

rss · Reddit - r/ChatGPT \(热门Prompt与趣味用法\) · 11月13日 11:10

**「内容角度」** 可做角度：以“只有标题、没有细节”为切入点，梳理这条消息中哪些是可验证的表述（产品名 Daybreak、AI Agent 渗透测试与自动修复配对），哪些仍属未知，并说明在缺少正文与官方说明时不宜据此判断能力或影响。

**标签**: `#\#AIAgent`, `#\#AI安全`, `#\#OpenAI`, `#\#自动化工作流`, `#\#科技资讯`

---

<!-- HORIZON_TRENDING -->
## 🔥 GitHub 今日 Trending Top 3（按今日新增 star）

#### 1. [GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src)
- ⭐ 今日 +1,875 · 总 4,790 · 🍴 266 · TypeScript · Apache-2.0 · 最近推送 0 小时前
- 榜单位置：第 2 位
- 简介：Keep your coding agent up to date with the latest web best practices
- 这是什么：Modern Web Guidance 的源仓库，包含编写、校准和评估该内容的代码与文档。
- 适合谁：适合使用编码代理的开发者，帮助代理避免旧模式、采用现代 Web 平台方案。
- 上手：运行 npx modern-web-guidance@latest install 按向导安装。

#### 2. [we-promise/sure](https://github.com/we-promise/sure)
- ⭐ 今日 +944 · 总 14,715 · 🍴 1,115 · Ruby · AGPL-3.0 · 最近推送 2 小时前
- 榜单位置：第 5 位
- 简介：The personal finance app for everyone (by everyone)
- 这是什么：面向所有人的个人财务应用，是已废弃 Maybe Finance 项目的社区分支。
- 适合谁：适合想自托管个人财务应用的用户，可通过 Docker 部署并使用浏览器、桌面或移动客户端。
- 上手：按 docs/hosting/docker.md 使用 Docker 自托管。

#### 3. [openai/codex-security](https://github.com/openai/codex-security)
- ⭐ 今日 +754 · 总 13,111 · 🍴 1,022 · TypeScript · Apache-2.0 · 最近推送 1 小时前
- 榜单位置：第 3 位
- 简介：OpenAI's Codex Security CLI and TypeScript SDK for finding, validating, and fixing security vulnerabilities. npm: https://www.npmjs.com/package/@openai/codex-security
- 这是什么：OpenAI 的 Codex Security CLI 与 TypeScript SDK，用于发现、验证和修复代码漏洞。
- 适合谁：适合开发与安全团队在 Codex、终端或自动化流程中扫描和修复漏洞。
- 上手：全局安装 @openai/codex-security，运行 cs login 后执行 cs scan .

> 中文摘要由 AI 根据仓库简介与 README 生成，仅供参考。
