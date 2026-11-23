---
layout: default
title: "Horizon Summary: 2026-11-23 (ZH)"
date: 2026-11-23
lang: zh
---

# Horizon 每日速递 - 2026-11-23

> 从原始资讯中去重并归纳合并出 11 条高价值核心情报。

---

**AI 创作者雷达**
1. [OpenCode 页面显示 GLM-5.3 与 DeepSeek V4.1 Flash API 降至四折](#item-ai-creator-1) ⭐️ 7.0/10
2. [腾讯 Chatterfly 语音输入工具开启限时内测](#item-ai-creator-2) ⭐️ 7.0/10
3. [谷歌为 Chrome AI 代理搭建模拟互联网测试环境](#item-ai-creator-3) ⭐️ 7.0/10
4. [开源 MCP server 支持在 Claude Desktop 本地查询健康数据](#item-ai-creator-4) ⭐️ 7.0/10
5. [ProPR：自托管 GitHub 编排工具，宣称已合并 5000+ PR](#item-ai-creator-5) ⭐️ 7.0/10
6. [蚂蚁开源医疗健康模型 LingSante-3.1-flash](#item-ai-creator-6) ⭐️ 7.0/10
7. [蚂蚁阿福上线实时视频看健康功能](#item-ai-creator-7) ⭐️ 7.0/10
8. [Seedeo MCP 称将 Suno、Kling、Veo 接入 ChatGPT 与 Claude 连接器](#item-ai-creator-8) ⭐️ 6.5/10
9. [Alphr 发布 2026 年 AI 角色生成器榜单，正文内容待核实](#item-ai-creator-9) ⭐️ 6.5/10
10. [SSBCrack 发布“2026 年 7 款最佳 Runway 替代工具”文章](#item-ai-creator-10) ⭐️ 6.5/10
11. [Reddit 帖称 6 天搭出跨平台 AI 智能体系统，细节待核实](#item-ai-creator-11) ⭐️ 6.5/10

---

## AI 创作者雷达

<a id="item-ai-creator-1"></a>
### [OpenCode 页面显示 GLM-5.3 与 DeepSeek V4.1 Flash API 降至四折](https://opencode.ai/console/models) ⭐️ 7.0/10

OpenCode 模型价格页显示，GLM-5.3 与 DeepSeek V4.1 Flash 均标注「60% off」，即按原价四折计费。页面列出每百万 token 单价：GLM-5.3 输入 $0.56、输出 $1.76、缓存读取 $0.104；DeepSeek V4.1 Flash 输入 $0.12、输出 $0.48、缓存读取 $0.0024。上述信息来自价格页面转述，折扣是否为限时、模型能力与上下文长度等条件尚待核实，受影响的主要是通过 OpenCode 调用这两款模型的开发者。

telegram · zaihuapd · 11月22日 03:48

**「为何值得关注」** 两款模型同时出现四折标价，直接改变按 token 计费的调用成本，对成本敏感的 API 使用者有现实参考价值；但折扣的持续时间和适用范围目前只有页面标注，尚无进一步说明。

**「内容角度」** 可做角度：以 OpenCode 价格页列出的输入、输出、缓存读取三项单价为基准，对比 GLM-5.3 与 DeepSeek V4.1 Flash 在四折后的每百万 token 成本差异，并注明折扣条件与模型规格仍待官方确认。

**标签**: `#AI模型API`, `#DeepSeek`, `#GLM`, `#成本优化`, `#AI工具测评`

---

<a id="item-ai-creator-2"></a>
### [腾讯 Chatterfly 语音输入工具开启限时内测](https://chatterfly.tencent.com/) ⭐️ 7.0/10

腾讯推出 AI 语音输入工具 Chatterfly，目前处于限时内测阶段，已开放 Windows、macOS 和 Android 版下载，iOS 版即将发布。官方定位是“不必想好，开口就成稿”，除语音转文字外，还宣称能理解上下文与场景，把零散口语整理成流畅表达，甚至直接执行任务，并支持轻声、嘈杂或弱网环境识别、随时唤起和积累词库。上述识别效果与任务执行能力目前仅有产品方描述，尚待实测核实。

telegram · zaihuapd · 11月22日 12:36

**「为何值得关注」** 腾讯以限时内测形式切入 AI 语音输入这一效率工具赛道，且同时覆盖桌面与移动端，属于近期可验证的新产品动作；但其实际识别准确率和“执行任务”能力尚未有独立验证。

**「内容角度」** 可做角度：以“语音转文字”与“口语成稿并执行任务”的定位差异为线索，梳理 Chatterfly 已公布的支持平台、内测状态和功能宣称，并标注哪些能力仍需实测。

**标签**: `#AI语音输入`, `#效率工具`, `#腾讯AI`, `#AI提效`, `#语音转文字`

---

<a id="item-ai-creator-3"></a>
### [谷歌为 Chrome AI 代理搭建模拟互联网测试环境](https://www.landian.news/archives/128701.html) ⭐️ 7.0/10

谷歌为 Chrome 的 AI 代理搭建了一个名为 Mirror Dimension 的模拟互联网，在隔离环境中测试其打开网站、搜索浏览、登录、加购和完成任务等操作。据蓝点网转述，该环境包含数千个模拟网站，每名工程师单独隔离测试，每天运行超过 1000 个测试案例，重点防御恶意网页的提示词注入等攻击。上述实现细节与测试效果目前仅有简讯来源，尚待核实。

telegram · zaihuapd · 11月23日 01:30

**「为何值得关注」** 浏览器内 AI 代理正从演示走向实际执行网页操作，如何在上线前安全地测试登录、加购等敏感动作成为现实问题。谷歌此次披露的隔离测试思路，反映的是测试方法上的变化，而非已证实的防护效果。

**「内容角度」** 可做角度：从“模拟互联网”这一测试方法切入，梳理浏览器 AI 代理在真实网页中执行操作时面临的风险，以及隔离环境、每日上千测试案例这类做法能覆盖什么、不能覆盖什么。

**标签**: `#AIAgent`, `#Chrome`, `#浏览器自动化`, `#提示词注入`, `#AI安全`

---

<a id="item-ai-creator-4"></a>
### [开源 MCP server 支持在 Claude Desktop 本地查询健康数据](https://news.google.com/rss/articles/CBMioAFBVV95cUxORDNoZkdTTlJHU2lLTHBYUTFJbVd6R2dqb244N1FZRHJCZ3VZRFc1TnI0M0FSSk52dzJlU05tRWhIR1pybWFWSFNHZ0RBaDc5dXB1TTl4ZWZxRVJtVkpSM2p5ejVxb0E4T3A3LWhVbmdjT25MWDVSTUFiaXI4Uzh2RFFWWTRUN29Ib1lPZUpvSW1zMW9WeV9IUVVHQ3c0Z08y?oc=5) ⭐️ 7.0/10

一位 Reddit 用户发布开源 MCP server，称可在 Claude Desktop 中本地查询 Apple Health、WHOOP 与 Oura 的健康数据。标题标注当前版本为 v0.8.2，并称该版本精简了工具 token。材料仅有标题，具体实现方式、token 裁剪幅度与实际效果均待核实。

rss · Reddit - r/ClaudeAI \(长文本与生产力实操\) · 11月22日 11:22

**「内容角度」** 可做角度：以“本地健康数据接入 Claude Desktop”为线索，梳理这个开源 MCP server 声称覆盖的三类数据源与 v0.8.2 的 token 精简改动，并明确标注哪些细节尚待作者文档或代码验证。

**标签**: `#MCP`, `#ClaudeDesktop`, `#开源项目`, `#健康数据`, `#AI工作流`

---

<a id="item-ai-creator-5"></a>
### [ProPR：自托管 GitHub 编排工具，宣称已合并 5000+ PR](https://news.google.com/rss/articles/CBMiogFBVV95cUxPMkJPaGwxOTVNQVJMNGNaNDV4eE90UkhHdFVuZEd0Z0t5bzNSVTYzUVJwZllMZ2ZrSGZTYlNYaFZxMVg4WVA4eERIUm9FejBmaVFrdWVqTzh1akZNMUszZkJ4OXF0RGVHVVZLdktYaC1ZSmt2TXpDbnJWUXoyMkZpWkpnbG11YnNVT3lWZWI2VTNPY0hjNTdDS3hsWG1ZQkNxY0E?oc=5) ⭐️ 7.0/10

Reddit r/ClaudeAI 出现一条关于 ProPR 的帖子，称其为自托管的 GitHub 编排工具，用于调度 Claude Code、Codex 等编码 Agent。标题宣称已合并 5,000+ 个 PR，其中 1,500+ 用于构建自身，并以 Apache 2.0 开源。目前仅有标题，没有正文细节，上述数字与具体实现均未经核实。

rss · Reddit - r/ClaudeAI \(长文本与生产力实操\) · 11月22日 22:51

**「为何值得注意」** 编码 Agent 的编排与自托管工作流是当前实操关注点，而“用 Agent 构建 Agent 工具自身”的自举说法提供了一个可验证的观察切口；但材料未说明发布时间线、版本或实际效果，影响尚不可判断。

**「内容角度」** 可做角度：以“自举式开发”为线索，梳理 ProPR 宣称的 5,000+ 合并 PR 与 1,500+ 自建 PR 分别对应什么工作流，并明确标注这些数字目前仅来自标题、待核实。

**标签**: `#ClaudeCode`, `#AI Agent`, `#开源工具`, `#自动化工作流`, `#GitHub提效`

---

<a id="item-ai-creator-6"></a>
### [蚂蚁开源医疗健康模型 LingSante-3.1-flash](https://www.36kr.com/newsflashes/4081776064140163) ⭐️ 7.0/10

11 月 23 日，蚂蚁宣布开源百灵医疗健康模型 LingSante-3.1-flash，称其在多项推理、安全对齐和 Agent 评测中达到开源 SOTA。据全球医疗 AI 评测平台 InclusionMed 综合指数，该模型位列全球开源模型首位。模型面向专业医疗场景，支持最长 1M Token 上下文，可处理大量病历、检查报告和医学文献，开展复杂病例分析、医学证据检索与综合，并通过工具调用辅助完成多步骤医疗任务。目前该模型已在蚂蚁阿福上使用，具体实测效果尚待核实。

rss · 36氪 \(AI与科技快讯\) · 11月23日 03:17

**「为何值得关注」** 这是蚂蚁在医疗垂直领域的一次开源发布，同时给出 1M Token 长上下文、Agent 工具调用和 InclusionMed 开源榜首等具体规格与评测声明；不过这些性能与排名目前来自发布方口径，实际使用效果仍需独立验证。

**「内容角度」** 可做角度：从“1M Token 上下文 + Agent 工具调用”切入，梳理 LingSante-3.1-flash 面向病历、检查报告和医学文献的公开能力边界，并区分官方评测声明与尚待核实的实际表现。

**标签**: `#AI大模型`, `#开源模型`, `#AI医疗`, `#Agent工作流`, `#AI前沿`

---

<a id="item-ai-creator-7"></a>
### [蚂蚁阿福上线实时视频看健康功能](https://www.36kr.com/newsflashes/4081738682045569) ⭐️ 7.0/10

11 月 23 日，蚂蚁集团旗下健康 AI“蚂蚁阿福”发布新版，基于蚂蚁百灵医疗健康系列模型，新增实时视频“看健康”功能。用户可通过视频通话让 AI 观察症状、状态和药品，分析健康问题，并联动医生在线把关。同时，App 升级“AI 健康管家”，可个性化制定减重、控糖、育儿等方案并陪伴用户达成。

rss · 36氪 \(AI与科技快讯\) · 11月23日 02:39

**「为何值得关注」** 这是国内首个上线实时视频健康咨询功能的健康 AI 应用，标志着 AI 健康助手从文本问答向多模态实时交互演进。不过，实际诊断准确性和医生联动机制的具体效果尚未披露。

**「内容角度」** 可做角度：从“AI 望闻问切”切入，对比传统在线问诊与视频 AI 看诊的差异，探讨实时视频在健康咨询场景中的可行性与边界。

**标签**: `#AI健康助手`, `#蚂蚁阿福`, `#AI应用落地`, `#多模态AI`, `#AI提效`

---

<a id="item-ai-creator-8"></a>
### [Seedeo MCP 称将 Suno、Kling、Veo 接入 ChatGPT 与 Claude 连接器](https://news.google.com/rss/articles/CBMiwAFBVV95cUxOQzNVMlNSbnRQOUhYbFRpaEt0NlFuUlM2ZHVtQXE3M3l2dHlVQnJBOTlNemYwRHE2N2o3SEFUZkxVVzQ2VU5OaG5xa2V5MDViZ2lkc09lallRZEY3MWsxcDdZMDBpTlk4dmpNN3NoN3E3dllKRDFLemxvSzM0bGdzS1h5QzdEeTd0dTdHaG44Sk9BSi1WbUlMT1RScFdocHA4UW0xb3MzMFZiN0RlZVhEOVBoMjBDdHhmZ2RzLXBZWDY?oc=5) ⭐️ 6.5/10

据 Springfield News-Leader 发布的一条简讯，Seedeo MCP 宣称把 Suno、Kling 和 Veo 接入 ChatGPT 与 Claude 的连接器。目前可核实的只有标题层面的信息：涉及三个生成式音视频工具和两个对话式 AI 平台，但接入方式、可用功能范围、是否已上线以及实际效果均未在材料中说明。受影响的主要是希望通过 MCP 在 ChatGPT 或 Claude 内调用音视频生成能力的用户与工作流搭建者，具体可用性仍待核实。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月22日 14:40

**「内容角度」** 可做角度：以“标题已宣布、细节待核实”为切口，梳理 MCP 连接器接入第三方生成工具时读者真正需要确认的几项信息——支持哪些模型版本、在 ChatGPT 与 Claude 两端是否一致、调用是官方集成还是第三方封装，并明确标注当前仅有简讯、尚无实测。

**标签**: `#MCP`, `#AI视频生成`, `#ChatGPT插件`, `#Claude`, `#AI工作流`

---

<a id="item-ai-creator-9"></a>
### [Alphr 发布 2026 年 AI 角色生成器榜单，正文内容待核实](https://news.google.com/rss/articles/CBMifEFVX3lxTE1fYVFXdldQS0hzREVhTG53OHFtbTltQTdIQWQzQlNkNHE1cTJZSDAyLTN3bzZwSU5XWm9zN1RJOUN6ZG9yaWp1WmJqY09lXzdQelRjOUlNWFNWWno3ZVRGX2pIVnRHLURTMm5xY3BtMFJlajRFTURSTHJrUDg?oc=5) ⭐️ 6.5/10

Alphr 于 2026 年 11 月 22 日发布了一篇题为“2026 年最适合创作者的 AI 角色生成器”的榜单类文章。目前可获取的材料只有标题和来源，具体收录了哪些工具、功能对比、价格与实测效果均未披露，因此无法确认榜单的评选依据和覆盖范围。该文面向使用 AI 角色生成工具进行视听创作的创作者群体。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月22日 15:00

**「内容角度」** 可做角度：以“榜单标题已出、正文细节未知”为切入点，梳理读者在评估 AI 角色生成器时真正需要核对的信息项（工具清单、版本、价格、授权与限制），并说明在正文可核实前不宜直接引用该榜单结论。

**标签**: `#AI角色生成`, `#AI视频创作`, `#创作者工具`, `#AI工具测评`, `#数字人`

---

<a id="item-ai-creator-10"></a>
### [SSBCrack 发布“2026 年 7 款最佳 Runway 替代工具”文章](https://news.google.com/rss/articles/CBMiWkFVX3lxTE9yek1SakgwWjVkZmFtTFJ5WmdqZ3NucDI3czZYX2tWVjg2Nko0cmdjUnZhVjc5aExRN2hlNDV6bGg2eGhCczFBOUlHVG9LV0V5Y2c3NWg4QzZPdw?oc=5) ⭐️ 6.5/10

SSBCrack 发布了一篇题为“2026 年 7 款最佳 Runway 替代工具”的文章，发布时间为 2026 年 11 月 22 日。目前可获取的内容仅有标题和链接，正文中的具体工具名单、功能对比、价格与实测效果均未在材料中呈现，因此无法核实其推荐依据。该文面向寻找 Runway 替代方案的 AI 视频创作者与工具选型人群。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月22日 15:55

**「内容角度」** 可做角度：以“一份只有标题的替代工具榜单能提供多少有效信息”为切口，讨论 AI 视频工具测评中名单罗列与可验证对比之间的差距，并提示读者在缺少功能参数和实测数据时不宜直接采信排名。

**标签**: `#AI视频生成`, `#Runway`, `#AI工具测评`, `#视频创作`, `#效率工具`

---

<a id="item-ai-creator-11"></a>
### [Reddit 帖称 6 天搭出跨平台 AI 智能体系统，细节待核实](https://news.google.com/rss/articles/CBMingFBVV95cUxNZkdkSFNkSVFZQW4yUFI4eG1FbjdGVkVVWEdxOERpcWFPbXFQM3pkV3hCMkxJRjJFRUtpWkFuSUpCRjItSTNuXzBZQTMzVzZsMmQ2Y09YTHFud3ViclRSZGpQbTkyWjUyZ2cybm56NTFGa1A4RjU1ZzZSUzRpcWE0b3FWSnJtcktLTVhwT1ZpNXdkSlFta25reVhTWmc0dw?oc=5) ⭐️ 6.5/10

Reddit 的 r/ClaudeAI 板块出现一条帖子，标题声称作者在 6 天内构建了一个 AI 智能体系统，可操作其 Mac、管理多个智能体、使用真实浏览器、在 AWS 服务器和 Windows 虚拟机服务器上运行，并能通过实时可打断的语音打电话给作者。目前材料中只有标题，没有正文、实现步骤、代码或效果验证，因此这些能力均属作者自述，尚未核实。

rss · Reddit - r/ClaudeAI \(长文本与生产力实操\) · 11月22日 04:13

**「内容角度」** 可做角度：以“只有标题、没有正文”为切入点，讨论这类多平台智能体自述案例中哪些能力最需要证据支撑——跨设备操作权限、多智能体协作、真实浏览器控制与实时可打断语音，并说明在缺少实现细节时读者应如何区分演示与可复现方案。

**标签**: `#AI Agent`, `#自动化工作流`, `#ClaudeAI`, `#个人效率`, `#AI实操案例`

---

---

<!-- HORIZON_TRENDING -->
## 🔥 GitHub 今日 Trending Top 3（按今日新增 star）

#### 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- ⭐ 今日 +1,716 · 总 18,069 · 🍴 1,984 · Python · MIT · 最近推送 15 小时前
- 榜单位置：第 1 位
- 简介：A Claude Code skill bundle for bug hunting and external red-team work - 82 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.
- 这是什么：面向漏洞挖掘与外部红队工作的Claude Code技能包，含83个技能、15个斜杠命令及681条披露报告模式。
- 适合谁：适合漏洞赏金与授权红队人员，让Claude Code按方法论、检测模式与报告规范辅助测试。
- 上手：在Claude Code中执行/plugin marketplace add elementalsouls/Claude-BugHunter，再/plugin install claude-bughunter@elementalsouls。

#### 2. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- ⭐ 今日 +915 · 总 207,139 · 🍴 10,824 · TypeScript · AGPL-3.0 · 最近推送 0 小时前
- 榜单位置：第 6 位
- 简介：Knowledge infrastructure to make your agents smarter. Search, scrape and access 550+ data providers through one API.
- 这是什么：让AI代理更智能的知识基础设施，可通过一个API搜索、抓取并访问550+数据提供方。
- 适合谁：适合需要把网站转为干净markdown或为AI代理提供网页数据的开发者与代理构建者。
- 上手：可cargo install firecrawl-local本地运行，或npx -y firecrawl-cli@latest scrape <URL>直接抓取。

#### 3. [obra/superpowers](https://github.com/obra/superpowers)
- ⭐ 今日 +788 · 总 324,265 · 🍴 28,763 · Shell · MIT · 最近推送 19 天前
- 榜单位置：第 2 位
- 简介：An agentic skills framework & software development methodology that works.
- 这是什么：面向编码代理的完整软件开发方法论，基于可组合技能与初始指令构建。
- 适合谁：适合使用编码代理的开发者，让代理先澄清需求、出设计、做计划再以子代理方式开发。
- 上手：README给出按不同工具（Claude Code、Codex、Cursor等）分别的安装说明，具体命令README信息不足。

> 中文摘要由 AI 根据仓库简介与 README 生成，仅供参考。
