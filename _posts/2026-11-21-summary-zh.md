---
layout: default
title: "Horizon Summary: 2026-11-21 (ZH)"
date: 2026-11-21
lang: zh
---

# Horizon 每日速递 - 2026-11-21

> 从原始资讯中去重并归纳合并出 10 条高价值核心情报。

---

**AI 创作者雷达**
1. [Anthropic 数学家称与 Claude 合作证明黎曼猜想](#item-ai-creator-1) ⭐️ 7.5/10
2. [豆包工作下调模型倍率，称八成办公任务可免费完成](#item-ai-creator-2) ⭐️ 7.0/10
3. [Gemini 上线 GIF 生成功能](#item-ai-creator-3) ⭐️ 7.0/10
4. [Cursor 拟停用中国开源权重模型](#item-ai-creator-4) ⭐️ 6.5/10
5. [可灵图像 4.0 据称主打原生 8K 与扩展提示词](#item-ai-creator-5) ⭐️ 6.5/10
6. [Agnes 智能体框架宣称提速 14 倍并开源 Harness，细节待核实](#item-ai-creator-6) ⭐️ 6.5/10
7. [Reddit 帖称将 AI 记忆迁至本地纯文本文件](#item-ai-creator-7) ⭐️ 6.5/10
8. [Reddit 帖称 OpenAI 发布 GPT-6.2 Astra 与 Sol，细节待核实](#item-ai-creator-8) ⭐️ 6.5/10
9. [Claude 做的 Windows 动态壁纸称 GPU 功耗仅 +0.7W](#item-ai-creator-9) ⭐️ 6.5/10
10. [Pixazo 接入 Kling Image 4.0 等三个 API](#item-ai-creator-10) ⭐️ 6.5/10

---

## AI 创作者雷达

<a id="item-ai-creator-1"></a>
### [Anthropic 数学家称与 Claude 合作证明黎曼猜想](https://www.36kr.com/newsflashes/4078894434915207) ⭐️ 7.5/10

Anthropic 数学家 Levent Alpöge 发文称，他与 Claude 合作发现了黎曼猜想的一个证明，并称相关方法可推广至广义黎曼猜想。他表示团队已用 Lean 证明助手对论证做了形式化验证并公开代码，证明涉及 Stepanov 方法、傅里叶分析和迭代 theta 提升等数论工具。该声明目前仅来自其个人发文，证明尚未经同行评议，篇幅庞大、有待整理和简化，具体细节仍待核实。

rss · 36氪 \(AI与科技快讯\) · 11月21日 02:25

**「为何值得关注」** 黎曼猜想是数学界长期未解的核心问题，此次声明若成立将影响深远；但当前可确认的只是“已形式化验证并公开代码”这一说法，同行评议与独立复核尚未发生，因此值得注意的是一次高关注度的公开声明，而非已被确认的数学结论。

**「内容角度」** 可做角度：梳理这条声明的证据链——个人发文、Lean 形式化验证、公开代码分别能证明什么、不能证明什么，并说明“形式化验证通过”与“数学界公认证明成立”之间的距离。

**标签**: `#\#AI科研`, `#\#Claude`, `#\#数学证明`, `#\#AI前沿`, `#\#开源代码`

---

<a id="item-ai-creator-2"></a>
### [豆包工作下调模型倍率，称八成办公任务可免费完成](https://mp.weixin.qq.com/s/nOSgci0nY2cGe06paOozfA) ⭐️ 7.0/10

据自媒体“大厂日爆”转述，豆包工作下调了多款模型的额度消耗倍率，其中 DeepSeek V4.1 Flash、豆包 2.1 Lite 降至 0.01，简单对话和低消耗任务不再收费。该转述还称，按实测数据超八成日常办公任务可免费完成，一次 3D 建模约 0.23 元、写动态网页约 0.06 元；同时推出签到领额度、新用户 30 天体验，并接入 Kimi K3.1 Pro、GLM 5.3 等第三方模型。上述倍率、模型版本与“八成免费”的结论均来自单一自媒体转述，官方细节尚待核实。

telegram · zaihuapd · 11月20日 10:17

**「为何值得关注」** 此次调整若属实，意味着豆包工作把部分低消耗办公场景的额度成本压到接近免费，并叠加签到与新用户体验额度，直接影响日常用 AI 办公的成本预期。但“八成任务免费”目前只是转述中的实测说法，并非官方口径。

**「内容角度」** 可做角度：以“倍率降到 0.01 之后，哪些办公任务真的不花钱”为线索，逐项复现简单对话、写动态网页、3D 建模等场景的实际额度消耗，并对照官方说明核实模型版本与免费范围，把转述数据与自测结果分开呈现。

**标签**: `#\#豆包`, `#\#AI办公`, `#\#免费额度`, `#\#AI工具实测`, `#\#效率工具`

---

<a id="item-ai-creator-3"></a>
### [Gemini 上线 GIF 生成功能](https://x.com/GeminiApp/status/2123813017855103449) ⭐️ 7.0/10

Gemini 上线 GIF 生成功能，由视频模型 Gemini Omni 1.2 Flash 驱动，可生成循环动图和搞笑表情包。该功能面向所有 Google AI 订阅用户开放，并在美国、日本、韩国、澳大利亚、加拿大、英国、德国和法国免费提供。用户可在主聊天框输入提示词，或在图像与视频工具中选择 GIF 并描述需求。

telegram · zaihuapd · 11月21日 01:09

**「为何值得关注」** 这是 Gemini 在图像与视频生成工具中新增的 GIF 入口，把动态图生成直接放进聊天与创作流程；免费范围目前限于上述八个国家，其他地区的可用性材料未说明。

**「内容角度」** 可做角度：梳理 Gemini 这次 GIF 功能的实际入口与使用路径——聊天框提示词和图像/视频工具两条方式分别怎么用，并说明订阅用户与八个免费国家之间的权限差异。

**标签**: `#\#Gemini`, `#\#AI视频生成`, `#\#GIF制作`, `#\#AI表情包`, `#\#AI工具更新`

---

<a id="item-ai-creator-4"></a>
### [Cursor 拟停用中国开源权重模型](https://www.cnbc.com/2026/11/20/cursor-chinese-ai-models-geopolitical-risk.html) ⭐️ 6.5/10

据 CNBC 报道，AI 编程平台 Cursor 表示因“地缘政治风险”正考虑逐步停用中国开发的开源权重模型，其 Composer 2 编程模型基于月之暗面 Kimi K2.5 构建。相关表态出现在美国众议院国土安全委员会与美中特别委员会的一份报告中，该报告建议推出“美国国家开源权重计划”，并在禁止 DeepSeek 进入联邦系统的行政令基础上，进一步禁止联邦系统使用中国开发的 AI 模型。目前仅有简讯，具体执行时间、涉及模型范围与对用户的实际影响均待核实；标题中“SpaceX 旗下”的归属表述在材料内文中未获佐证。

telegram · zaihuapd · 11月20日 16:13

**「为何值得关注」** 这是美国国会报告层面的政策建议与 Cursor 的公开表态叠加出现，指向 AI 编程工具底层模型选型可能受地缘政治因素影响；但报告建议是否落地、Cursor 是否真正停用，目前均未证实。

**「内容角度」** 可做角度：梳理“政策建议—工具厂商表态—底层模型依赖”这条链条，以 Cursor 的 Composer 2 基于 Kimi K2.5 为具体切口，说明一个编程工具更换模型来源时，用户可能感知到的变化与仍待确认的信息。

**标签**: `#\#Cursor`, `#\#AI编程工具`, `#\#KimiK2`, `#\#AI政策`, `#\#开源模型`

---

<a id="item-ai-creator-5"></a>
### [可灵图像 4.0 据称主打原生 8K 与扩展提示词](https://news.google.com/rss/articles/CBMingFBVV95cUxOYm1tY1MxUjRKUG8zUDYyUVh1WDI3LXphQWZHNWRvaGo1ZVBFVmFOblB2SDd0dzNMWF9TTFRydVNEV1ZVanVIMlVtZkJzMHZFa1pMLXNzZ2l4VHpQRzFlRWxkazBqN21ZYzlYNzVwV0pRTWloa3FNblpod2JtTE90UHY1Mms3QXFPa2tCMzQ1ZHZzNXBwWVRoVHZhaWZ5QQ?oc=5) ⭐️ 6.5/10

据 Foro3D 报道，可灵（Kling）图像模型推出 4.0 版本，主打原生 8K 输出与扩展提示词能力。目前仅有标题级信息，报道未给出具体参数、上线时间、价格或可用范围，实际效果与“原生 8K”的具体含义仍待核实。受影响的主要是使用可灵进行 AI 图像生成的创作者。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月20日 17:58

**「内容角度」** 可做角度：以“原生 8K 到底意味着什么”为切口，梳理标题中两个卖点——原生 8K 与扩展提示词——在图像生成流程中可能对应的环节，并明确标注官方细节尚未公布，避免把宣传口径当作实测结论。

**标签**: `#\#可灵Kling`, `#\#AI图像生成`, `#\#AI视频工具`, `#\#8K生成`, `#\#AI创作工具`

📌 **同日该 AI 其他重要动态汇总**：
- **WeMM-Video-35B-A3B 与 Kling 4.0 对比文章仅有标题**：OrcaRouter 于 2026 年 11 月 20 日发布标题为《WeMM-Video-35B-A3B vs Kling 4.0: A Reader Against a Renderer》的文章，指向两个 AI 视频模型的对比；目前只有标题与来源，没有正文摘要、参数、实测效果或实现细节，对比维度与结论均无法核实。[原题](https://news.google.com/rss/articles/CBMib0FVX3lxTE0ybnpWVFlfVGM0aGM3bndWVHZPWW1mVXM1ZUl4RlNxZHAtRV82V0MzbzFuWUIxRGJjQmwtZU9KdFMwdFJEZThOeDY1b3I5Tzd3N1J4dlk5RkFmZ0o0cFBxWDNhMHp4QUd3OWZaZS1aMA?oc=5)
- **WeMM-Video-2B 与 Kling 4.0 Flash 对比帖仅有标题**：OrcaRouter 发布标题为“WeMM-Video-2B vs Kling 4.0 Flash: Two Different Meters”的内容，指向两款 AI 视频模型对比；目前只有标题和来源，没有正文摘要、参数、版本细节或实测结果，具体对比维度与结论均无法核实。[原题](https://news.google.com/rss/articles/CBMicEFVX3lxTE5La3lvYlBjcUswcGFjZEhENE14Q1FFczR3UmpkckY4WFVkbDdIWmVwellsRFl0Vy1zWmNDVHNOVmF1TWFpRmd0bUQ1OWxPc3lBMlUwdjdmWGF1ZnNyRTFXM0ZMX1FTdlB3QU5WZVFIRmU?oc=5)

---

<a id="item-ai-creator-6"></a>
### [Agnes 智能体框架宣称提速 14 倍并开源 Harness，细节待核实](https://www.qbitai.com/2026/11/511582.html) ⭐️ 6.5/10

量子位报道了一个名为 Agnes 的智能体框架，标题称其采用“双系统决策+双层自进化”，效率最高提速 14 倍、成本降至 1/27。正文仅有一句“已开源 Agnes Harness”，没有给出实现细节、测试基线、参数配置或复现方式，因此上述性能数字目前只是报道标题中的宣称，尚无法核实。可能受影响的是关注 AI Agent 框架选型与开源工具链的开发者。

rss · 量子位 QbitAI \(国内AI前沿与应用\) · 11月20日 05:24

**「可做角度」** 可做角度：以“宣称 14 倍提速、成本 1/27，但正文只确认开源了 Harness”为切口，梳理这条消息中哪些是可验证事实（开源动作）、哪些是待核实宣称（性能与成本数字），并说明读者若要评估该框架还需补齐哪些信息。

**标签**: `#\#AIAgent`, `#\#开源项目`, `#\#智能体框架`, `#\#效率工具`, `#\#AI前沿`

---

<a id="item-ai-creator-7"></a>
### [Reddit 帖称将 AI 记忆迁至本地纯文本文件](https://news.google.com/rss/articles/CBMinAFBVV95cUxNd1pzRWZYMEtmLTRLbU5ZOG9mSUtiaS03OHRrb3ViOTYxUkpLbEtkRUYyQ0JlSlptekRsVk8xNHd2YkdRX2x2dEIwZWZLLW5uRTNiaEJJR19fMi1Wd1BNN1ptdUw0S0t0OE1TS2FIRENxRU5Odml6anZzS0VXa2F4X280cEdVMU5uMlhFc21MWTZWc0FUS0J1dy1lcjQ?oc=5) ⭐️ 6.5/10

Reddit r/ChatGPT 出现一条帖子，标题称作者在经历 2100 多次 AI 会话后，不再信任各平台内置记忆，把全部记忆迁移到本地纯文本文件，并声称该做法适用于 ChatGPT、Claude 或 Gemini。目前材料只有标题与链接，没有正文、文件结构、操作步骤或实际效果说明，因此迁移方式与可用性均待核实。受影响的是关注 AI 记忆与个人知识管理的用户。

rss · Reddit - r/ChatGPT \(热门Prompt与趣味用法\) · 11月20日 04:14

**「内容角度」** 可做角度：以“平台内置记忆与本地纯文本记忆的取舍”为线索，先说明这条帖子只给出主张、缺少可验证细节，再讨论跨 ChatGPT/Claude/Gemini 使用同一份本地文本时，哪些信息需要人工维护、哪些环节仍依赖平台，避免把标题当成已验证方案。

**标签**: `#\#AI记忆`, `#\#本地知识库`, `#\#ChatGPT`, `#\#Claude`, `#\#效率工具`

---

<a id="item-ai-creator-8"></a>
### [Reddit 帖称 OpenAI 发布 GPT-6.2 Astra 与 Sol，细节待核实](https://news.google.com/rss/articles/CBMikgFBVV95cUxOeWRzTjEyWVNZN0Vsc2wyRWc2TWwzdHJqRktBeXdJMnZsTHl1OVJEUTV6NjVUQmREZkJNRTJPQlYwOWZhWW1oeVNUbTBUOG5rQzRobm1EMXFzeWE4Z2s4YUZxRk14MWlBUVFxSEQ0Nk9YMU9TNmVORlZ2Tksya3c0VE9nOVFuQWtyb3FqTEVzSkEzdw?oc=5) ⭐️ 6.5/10

一条来自 Reddit r/OpenAI 的帖子标题声称 OpenAI 发布了“GPT-6.2 Astra and Sol”。材料中只有这一行标题，没有正文、模型规格、功能说明或官方确认，发布时间为 2026 年 11 月 20 日。因此目前能确认的只是“出现了这样一条标题”，发布本身与具体内容均待核实。

rss · Reddit - r/OpenAI \(官方动态与用户反馈\) · 11月20日 06:30

**「为何值得注意」** 该标题指向大模型版本更新这一核心话题，若属实会涉及 OpenAI 的产品线变化；但现有材料未提供任何官方来源或技术细节，尚不能判断其真实性，也无法评估影响范围。

**「内容角度」** 可做角度：以“一条只有标题的发布传闻”为切口，梳理判断此类 OpenAI 版本消息真伪的核查路径——查官方博客与文档、看模型列表与 API 变更记录，并说明在缺少正文与官方确认时为何不宜直接当作发布事实传播。

**标签**: `#\#大模型更新`, `#\#OpenAI`, `#\#AI资讯`, `#\#待核实`, `#\#AI前沿`

---

<a id="item-ai-creator-9"></a>
### [Claude 做的 Windows 动态壁纸称 GPU 功耗仅 +0.7W](https://news.google.com/rss/articles/CBMioAFBVV95cUxQeFJuUWU2TnhxYWFsaWVmTXI4WDZBQzJiNVV3NkZDb0JOc3pKNm42OVZkMkp3N1dFNWQyaVRIUVpROTQwXzE4SG51Rm5ZbHFpeHJ0QlFBZGJaUmlJeXBqRVRLYmJ3MnZ4RWVLZi1QYkZ2X1MwX0F2dHI4aWxZLXRHaFZPZ1gycXBZbXNKRnhUTXlRcGpONkpEbmd0dTdNdTFa?oc=5) ⭐️ 6.5/10

Reddit 用户发帖称，自己用 Claude 做了一个 Windows 动态壁纸，运行时 GPU 功耗增加约 0.7W，而某款流行动态壁纸应用为 +23.1W。帖子只给出标题和这组对比数字，没有说明测试方法、硬件配置、壁纸实现方式，也没有提供代码或仓库链接。受影响的是关注 Windows 桌面美化与功耗的普通用户，但该对比目前无法独立核实。

rss · Reddit - r/ClaudeAI \(长文本与生产力实操\) · 11月20日 04:27

**「内容角度」** 可做角度：把“AI 写代码”的叙事落到可验证的功耗测量上——先追问这 0.7W 与 23.1W 是怎么测的、在什么硬件和壁纸内容下成立，再讨论用 Claude 生成 Windows 动态壁纸在实现上可能省掉哪些常驻渲染开销。

**标签**: `#\#Claude`, `#\#AI零代码开发`, `#\#效率工具`, `#\#Windows技巧`, `#\#AI实操`

---

<a id="item-ai-creator-10"></a>
### [Pixazo 接入 Kling Image 4.0 等三个 API](https://news.google.com/rss/articles/CBMioAFBVV95cUxOZzZqaFhQc2c4dC1pWE5wOUtWTzFIRU81Q2VQQjBmTVVMWVpLS2UxUDBqWGZqNUVJVkdlUkFnRUpkSUNIX2QzTlhOQWpTZzJrR09tSmo5NXZoOURzX0lMb3FPdG43ZTFDT3R3ZmhOZG5zb2g0X09YTXZfdzhESVJ5RGoySDhLWW1kaHZRcmNxeFZpZS1URUZZWXFPNDhudlFS?oc=5) ⭐️ 6.5/10

Pixazo 平台宣布接入 Kling Image 4.0、MAI Image 2.7 与 Tripo3D H3.1 三个 API，来源为 openPR.com 的新闻稿标题，发布时间为 2026 年 11 月 20 日。目前仅有标题信息，三个模型的具体功能参数、调用方式、定价与可用范围均未披露，实际能力与上线状态有待核实。受影响的主要是使用 Pixazo 做图像与 3D 生成的开发者及内容创作者。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月20日 14:58

**「内容角度」** 可做角度：以“平台聚合多模型 API”为线索，梳理 Pixazo 此次新增的三个模型分别属于图像与 3D 生成哪一类，并明确标注目前只有标题、参数与定价未知，把可核实的信息与待确认项分开呈现。

**标签**: `#\#AI视频生成`, `#\#API集成`, `#\#可灵Kling`, `#\#3D生成`, `#\#AI工具动态`

---

<!-- HORIZON_TRENDING -->
## 🔥 GitHub 今日 Trending Top 3（按今日新增 star）

#### 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- ⭐ 今日 +1,622 · 总 14,479 · 🍴 1,710 · Python · MIT · 最近推送 12 小时前
- 榜单位置：第 1 位
- 简介：A Claude Code skill bundle for bug hunting and external red-team work - 82 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.
- 这是什么：面向漏洞挖掘与外部红队工作的 Claude Code 技能包，含 83 个技能、15 个斜杠命令和 681 条公开报告模式。
- 适合谁：适合漏洞赏金与授权红队人员，让 Claude Code 按方法论、检测模式与报告规范辅助测试。
- 上手：在 Claude Code 内执行 /plugin marketplace add elementalsouls/Claude-BugHunter 再 /plugin install claude-bughunter@elementalsouls。

#### 2. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- ⭐ 今日 +1,241 · 总 205,393 · 🍴 10,742 · TypeScript · AGPL-3.0 · 最近推送 0 小时前
- 榜单位置：第 6 位
- 简介：Knowledge infrastructure to make your agents smarter. Search, scrape and access 550+ data providers through one API.
- 这是什么：为 AI 智能体提供知识基础设施，可将网站转为干净 markdown，并提供搜索与数据访问。
- 适合谁：适合需要给 AI 智能体接入网页抓取、爬取、站点映射与搜索能力的开发者。
- 上手：可 cargo install firecrawl-local 本地运行，或用 npx -y firecrawl-cli@latest scrape 抓取页面。

#### 3. [XiaoYouChR/Ghost-Downloader-3](https://github.com/XiaoYouChR/Ghost-Downloader-3)
- ⭐ 今日 +1,082 · 总 13,823 · 🍴 842 · Python · GPL-3.0 · 最近推送 20 小时前
- 榜单位置：第 15 位
- 简介：The only downloader you need. 下载器的集大成者。
- 这是什么：跨平台下载器，支持 HTTP、BT/磁力、FTP、M3U8、MPEG-DASH、eD2k 及视频站点下载。
- 适合谁：适合需要统一管理多种协议下载、弱网下载及视频抓取的用户。
- 上手：README 未给出

> 中文摘要由 AI 根据仓库简介与 README 生成，仅供参考。
