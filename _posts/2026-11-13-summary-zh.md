---
layout: default
title: "Horizon Summary: 2026-11-13 (ZH)"
date: 2026-11-13
lang: zh
---

# Horizon 每日速递 - 2026-11-13

> 从原始资讯中去重并归纳合并出 13 条高价值核心情报。

---

**AI 创作者雷达**
1. [OpenAI 开源 MCP Extensions，为 MCP 服务器加入 ChatGPT 专属能力](#item-ai-creator-1) ⭐️ 7.0/10
2. [Google 发布 A2UI 1.0 开源生成式 UI 协议](#item-ai-creator-2) ⭐️ 7.0/10
3. [谷歌发布 Gemini Decisions API，主打低延迟多模态封闭式决策](#item-ai-creator-3) ⭐️ 7.0/10
4. [开源项目称在不足 1GB 内存的旧设备上运行 16B 模型](#item-ai-creator-4) ⭐️ 7.0/10
5. [OpenAI 客户案例三连发：Amplitude Wave、Gondola 与 Holiday Extras 均基于其模型](#item-ai-creator-5) ⭐️ 6.5/10
6. [Gemini 4 Hydrogen 与 Orchestrator 多模型编排功能引发讨论](#item-ai-creator-6) ⭐️ 6.5/10
7. [字节跳动 Seedance 2.5 与接近 5500 亿美元估值：仅标题简讯](#item-ai-creator-7) ⭐️ 6.5/10
8. [AI 音乐视频生成器面向说唱歌手与艺人（2026）](#item-ai-creator-8) ⭐️ 6.5/10
9. [SitePoint 发布 2026 年 AI 动漫视频生成器盘点文章](#item-ai-creator-9) ⭐️ 6.5/10
10. [9 个 AI 模型同场“世界大战”模拟帖：仅标题可查](#item-ai-creator-10) ⭐️ 6.5/10
11. [Anthropic 称约千个 Claude 智能体 30 小时形式化费马大定理](#item-ai-creator-11) ⭐️ 6.5/10
12. [一条 Reddit 帖子称让 Claude Fable 5.2 与多款模型对战 80 局 Codenames](#item-ai-creator-12) ⭐️ 6.5/10
13. [Scrum 博客：把 AI Agent 的 token 成本纳入 Sprint 规划](#item-ai-creator-13) ⭐️ 6.5/10

---

## AI 创作者雷达

<a id="item-ai-creator-1"></a>
### [OpenAI 开源 MCP Extensions，为 MCP 服务器加入 ChatGPT 专属能力](https://github.com/openai/mcp-extensions?utm_source=tldrai) ⭐️ 7.0/10

OpenAI 在 GitHub 开源了 MCP Extensions，提供 TypeScript 和 Python 包，用于给 MCP 服务器与应用添加 ChatGPT 专属功能，包括侧边栏入口、自定义文件查看器、composer 资源搜索和缩略图选择器。仓库同时附带一个名为 Bits &amp; Bolts 的演示插件和一份书面规范。材料未给出具体版本号、API 规格细节或上手步骤，实际可用性与集成成本尚待核实。

rss · TLDR AI \(全球AI新工具与产品速递\) · 11月12日 00:00

**「为何值得关注」** 这是 MCP 生态向 ChatGPT 插件形态延伸的一次开源动作，开发者可直接查看 SDK 与演示插件；但材料只说明能力范围，未证实这些扩展在真实应用中的效果或采用情况。

**「内容角度」** 可做角度：梳理这四个 ChatGPT 专属能力（侧边栏入口、文件查看器、composer 资源搜索、缩略图选择器）分别对应 MCP 服务器开发中的哪类交互需求，并结合 Bits &amp; Bolts 演示插件说明规范文档覆盖了什么、没覆盖什么。

**标签**: `#MCP`, `#ChatGPT插件`, `#AI Agent`, `#开源工具`, `#AI工作流`

---

<a id="item-ai-creator-2"></a>
### [Google 发布 A2UI 1.0 开源生成式 UI 协议](https://developers.googleblog.com/a2ui-10-build-delightful-fast-reliable-agentic-experiences/?utm_source=tldrai) ⭐️ 7.0/10

Google 发布 A2UI 1.0，这是一个面向生成式 UI 的开源协议，让 Agent 以交互式界面而非纯文本作答。配套提供 Web、Android、iOS 的渲染 SDK，以及 Python、TypeScript、Dart 的 Agent SDK，并强调用原生组件安全绘制界面。官方称，无论用户在企业自有 App 还是托管 MCP 应用的第三方 AI 助手中访问，都能获得相同的低延迟、高信任与原生保真度；具体接入方式与实测效果尚未披露。

rss · TLDR AI \(全球AI新工具与产品速递\) · 11月12日 00:00

**「为何值得关注」** 生成式 UI 正从演示走向协议化与多端 SDK 落地，A2UI 1.0 以开源形式同时覆盖渲染端和 Agent 端，并明确对接 MCP 托管场景，这是已发生的变化；但其实际性能与生态采用情况仍待验证。

**「内容角度」** 可做角度：梳理 A2UI 1.0 的协议定位与 SDK 矩阵，对比“Agent 用文本回答”和“Agent 用原生交互界面回答”在延迟、信任与跨端一致性上的差异，并指出官方尚未给出接入细节与实测数据这一信息缺口。

**标签**: `#A2UI`, `#AI_Agent`, `#生成式UI`, `#开源工具`, `#MCP`

---

<a id="item-ai-creator-3"></a>
### [谷歌发布 Gemini Decisions API，主打低延迟多模态封闭式决策](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-decisions-api/) ⭐️ 7.0/10

谷歌发布 Gemini Decisions API，基于新模型 Gemini Decision 1，面向工具选择、策略检查、模型路由等封闭式决策场景。它支持文本、图像、音频、视频和 PDF 输入，单次最多可对 1000 个问题打分并返回概率与置信度，端到端延迟约 150–250 毫秒。定价为每百万输入 tokens 0.10 美元、输出 token 不收费，官方称比 Gemini 3.5 Flash-Lite 方案便宜近 5 倍；该 API 现已在 Google AI Studio 提供。

telegram · zaihuapd · 11月12日 00:28

**「为何值得关注」** 这条消息的当下价值在于：谷歌把“决策打分”从通用生成模型中单独拆出，给出明确的延迟、批量上限和按输入计价的参数，并已开放试用。不过，材料中的“便宜近 5 倍”是官方说法，实际效果与稳定性尚待开发者验证。

**「内容角度」** 可做角度：从“单次最多 1000 个问题打分、150–250 毫秒延迟、只按输入 tokens 计费”这三个参数出发，梳理它适合嵌入 Agent 工作流的哪些环节（工具选择、策略检查、模型路由），并说明这些数字来自官方发布、尚缺第三方实测。

**标签**: `#GeminiDecisionsAPI`, `#AI决策`, `#模型路由`, `#Agent工作流`, `#GoogleAIStudio`

---

<a id="item-ai-creator-4"></a>
### [开源项目称在不足 1GB 内存的旧设备上运行 16B 模型](https://github.com/hyperionaidev/smolmaxxing/) ⭐️ 7.0/10

开发者 mrashad74 在 Hacker News 发布开源项目 smolmaxxing，称已在第一代 iPad Air 和小米电视盒上运行 16B 参数大模型，这两台设备的可用内存均不足 1GB。作者表示已开源所开发的内核与结果，供他人复现，修改后的模型发布在 Hugging Face 的 hyperionaidev 账号下。目前速度与效果仅有作者自述，尚无第三方验证。

hackernews · mrashad74 · 11月12日 15:23 · [社区讨论](https://news.ycombinator.com/item?id=50468888)

**「为何值得关注」** 小模型与本地推理的优化近期进展较快，评论区有人提到一年前微调的 Qwen 2.5 0.5B 模型尚缺推理与数学能力，而如今已有更小的本地模型能完成多步推理。该项目把“旧设备跑大模型”推到 16B 与不足 1GB 内存的组合，但实际可用性仍待复现验证。

**「内容角度」** 可做角度：梳理该项目声称的硬件条件（iPad Air 1 代、小米电视盒、可用内存不足 1GB）与 16B 模型之间的量化与内核取舍，并明确标注速度、精度均来自作者自述，把“能否复现”作为待验证问题留给读者。

**「社区讨论」** 评论整体偏正面，有人称这类优化“很酷”，也有人追问小模型在实际任务中是否足够有用。另有评论认为，如今让模型跑在旧硬件上，最难的部分已不是推理引擎本身，而是找到硬件并给智能体开放 SSH 访问。

**标签**: `#本地大模型`, `#开源项目`, `#旧设备改造`, `#AI极客`, `#模型量化`

---

<a id="item-ai-creator-5"></a>
### [OpenAI 客户案例三连发：Amplitude Wave、Gondola 与 Holiday Extras 均基于其模型](https://openai.com/index/amplitude) ⭐️ 6.5/10

OpenAI 官方简讯称，Amplitude 的主动式产品 Agent「Wave」主要基于 OpenAI 模型构建。按官方描述，Wave 能识别该做什么、借助编码 Agent 帮助团队发布改动，并衡量改动带来的影响。材料仅有一句话摘要，未给出具体实现步骤、所用模型版本、发布时间或可验证的效果数据，实际能力与落地范围仍待核实。

rss · OpenAI News \(官方动态\) · 11月12日 20:00

**「内容角度」** 可做角度：把这条简讯当作“厂商自述的 Agent 案例”来拆解，重点区分官方宣称的三段能力（识别需求、编码发布、衡量影响）与材料中缺失的证据，讨论一个产品 Agent 要闭环到“衡量影响”还需要哪些未披露的环节。

**标签**: `#AIAgent`, `#产品工作流`, `#OpenAI`, `#效率工具`, `#一人公司`

📌 **同日该 AI 其他重要动态汇总**：
- **Gondola 称用 Codex 让营收翻倍**：OpenAI 官方客户故事页面介绍，创意人才平台 Gondola 使用 Codex 后，其首席工程师的产出提升 50%，公司营收翻倍；同时 ChatGPT 被用于简化日常工作。上述数字均来自来源方自述，缺少具体工作流、使用方式和统计口径等可核实细节。rss · OpenAI News \(官方动态\) · 11月12日 12:00 [原题](https://openai.com/business/customer-stories/gondola)
- **Holiday Extras 用 Codex 改进应用**：OpenAI 官方发布客户案例，称旅行服务公司 Holiday Extras 正使用 Codex 把客户专业知识转化为更好的应用，并提升预订转化率、开拓增长空间。该页面目前仅有一句导语，未披露具体实现步骤、所用版本、量化效果或时间线。rss · OpenAI News \(官方动态\) · 11月12日 09:30 [原题](https://openai.com/business/customer-stories/holidays-extras-codex)

---

<a id="item-ai-creator-6"></a>
### [Gemini 4 Hydrogen 与 Orchestrator 多模型编排功能引发讨论](https://antigravity.google/blog/gemini-4-hydrogen-in-google-antigravity/) ⭐️ 6.5/10

Google Antigravity 博客出现一篇题为“Gemini 4 Hydrogen and Orchestrator”的文章，标题指向 Gemini 4 Hydrogen 模型与名为 Orchestrator 的多模型编排功能。目前材料中没有正文，具体功能、参数、定价与效果均无法核实。Hacker News 评论者提到新 Flash 模型、模型自动切换以及成本节省等体验，但这些都属于用户说法，不能当作官方事实。受影响的主要是使用 Gemini 系列模型进行编程和任务执行的开发者。

hackernews · jonbaer · 11月12日 18:52 · [社区讨论](https://news.ycombinator.com/item?id=50472260)

**「为何值得关注」** 如果该发布属实，它意味着 Google 在 Gemini 系列中引入多模型编排，让系统按任务自动选择模型，而不是由用户手动切换。不过目前只有标题和社区讨论，发布范围、可用性和实际效果都尚未确认。

**「内容角度」** 可做角度：以“标题已出、正文缺失”为切入点，梳理社区对 Gemini 4 Hydrogen 与 Orchestrator 的具体说法与疑问，并明确标注哪些是官方信息、哪些只是用户推测，重点讨论多模型编排在缓存计费和模型能力判断上的不确定性。

**「社区讨论」** 评论者对多模型编排并不陌生，有人将其与 Anthropic 的 advisor mode、GitHub 的多模型流水线类比，并质疑跨模型调用时的缓存与计费方式。也有用户抱怨此前的 Argon 和 Carbon 模型速度慢，欢迎新的 Flash 模型；另一些人则对把模型选择权交给系统持谨慎态度，担心模型高估自身能力。关于 60% 成本节省等数字均为个人经验，未经核实。

**标签**: `#Gemini`, `#多模型编排`, `#AI编程`, `#大模型更新`, `#效率工具`

---

<a id="item-ai-creator-7"></a>
### [字节跳动 Seedance 2.5 与接近 5500 亿美元估值：仅标题简讯](https://news.google.com/rss/articles/CBMi1gFBVV95cUxPRmVyWE0xdG9oWG1VS2swNUhpcTJRajBVVHdDSG1OMmNLYXFaakc5ZERpR09pdC03Rndhc08yOVhDRDRaWHFGRmhkeWV1a05fVmFHbWZrcmhMWklQUV9aU3hGelNJcGF5eW4yX0V6Y09jVGF4am5nczVrVDNxNzFVS1R1RlVFYzhuQjAxRE1tUHVVSmo5SEFENEVKbUROS0hJRjhva01TRmJuNjdqUm1va3NURVN6d3hyUnk2NVdzY1dVTFBFcUE5UHBZMW9RcWtxZ05JdU1n0gHeAUFVX3lxTE42Sk5KU2JoNFZuNE10M1NXNHYzTGlzV2hOTTRwcXNaTjFiQ2tGS1BBalJRVFYyRVFKeXpVVnhyZVVSTWNYTUJKYW1lcmxOYWhmVTk5Slc4RWR5VGtxWmgxYThSaTdfQTNWY25kbExFc1lZRDdmcDhSUXdEcXVhbjl5ZkwxS04tczNNLXZmOFBHcFhtc0FSYUZUZGY3MElxRzFSUzdBcVhZX05SX19tRHJLb3hfQzVKREZrYmtNRG5SeGdPX1ZmYk9UeVZ0Ri1QSFZfUWtSVEQteWZqLVRDZw?oc=5) ⭐️ 6.5/10

FindArticles 的一则标题简讯称，字节跳动的 Seedance 2.5 推动其 AI 视频生成商业化，同时公司估值接近 5500 亿美元。材料未提供该版本的具体功能、参数、发布时间、定价或实测效果，也未说明商业化方式与估值口径，相关细节均待核实。可能受影响的是关注 AI 视频生成工具的内容创作者与短剧制作方。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月12日 11:18

**「内容角度」** 可做角度：以“一条只有标题的消息能确认什么”为切口，梳理 Seedance 2.5 目前可核实的信息边界，并列出需要向官方或实测求证的功能、价格与开放范围清单。

**标签**: `#AI视频生成`, `#Seedance`, `#字节跳动`, `#AI短剧`, `#AI工具动态`

---

<a id="item-ai-creator-8"></a>
### [AI 音乐视频生成器面向说唱歌手与艺人（2026）](https://news.google.com/rss/articles/CBMiekFVX3lxTE5HWVJRWV9tRjEtc1hWbkJRaHdXZkpMUm9lYVZrZFVvVmNYNUVQQVFLQTFYWEtrcE55djM5VjRfemVDam1DVFFHaHZLeDlPd0JaaU9JS3JObmRjcWw0WGZLajVPbS1JeWxLOVQ3WFpISEFJYlA2YnJyUE9B?oc=5) ⭐️ 6.5/10

Respect My Region 发布了一篇标题为《AI Music Video Generators for Rappers and Artists 2026》的内容，主题是面向说唱歌手和艺人的 AI 音乐视频生成器。目前可获取的材料只有标题和来源，没有正文细节，因此文中具体涉及哪些工具、使用步骤、生成效果与价格限制均无法核实。受影响的人群是考虑用 AI 制作音乐视频的独立说唱歌手与艺人，但实际可用性尚待确认。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月12日 17:10

**「内容角度」** 可做角度：以“只有标题、没有正文”为起点，梳理面向音乐人的 AI 音乐视频生成器这一品类目前公开可查的信息边界，明确区分已确认的报道主题与尚未证实的工具清单和效果描述。

**标签**: `#AI视频生成`, `#AI音乐视频`, `#AI短剧`, `#创作者工具`, `#AI视听`

---

<a id="item-ai-creator-9"></a>
### [SitePoint 发布 2026 年 AI 动漫视频生成器盘点文章](https://news.google.com/rss/articles/CBMipwFBVV95cUxPRE5ubFpPMWtjTm5wY0pTVVRjOVFncmpHemptajl4aHE2SkFud1p2LTVjLWtOMUJtNnlEb3g3RUgzelV1aVBwSk0zMFVIUVVNMHI3eWNzR2tYWVJQdjdIUDRxbzBVU2NXZHc2TlpMX3ExT2M3SGNXNVhPNk5TZ09CdVNXZnBETzNmMVNmWURFNnJiS3BYWjJkZU9LY2FNQzdYRUdMV2R5aw?oc=5) ⭐️ 6.5/10

SitePoint 发布了一篇标题为《2026 年 5 款最佳 AI 动漫视频生成器，以及 AI 动漫视频是否值得制作》的文章，发布时间为 2026 年 11 月 12 日。目前可获取的材料只有标题和来源，文章具体列出哪 5 款工具、各自的功能参数、价格与免费额度，以及“是否值得制作”的论证内容均未披露，需查阅原文核实。受影响的主要是关注 AI 动漫短片与短剧创作的工具选型人群。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月12日 08:00

**「内容角度」** 可做角度：以“盘点类文章只有标题、正文待核实”为切口，先说明这条信息的确定性边界，再等拿到原文后逐项核对 5 款工具的名称、版本、价格与限制，避免仅凭标题转述工具排名。

**标签**: `#AI动漫视频`, `#AI视频生成器`, `#AI短剧`, `#内容创作工具`, `#AI工具盘点`

---

<a id="item-ai-creator-10"></a>
### [9 个 AI 模型同场“世界大战”模拟帖：仅标题可查](https://news.google.com/rss/articles/CBMinwFBVV95cUxPSEQ1YTVIRzlVRFdZSEFKVF9oUVlkMTRHYUNMZlZpNTh5elRKYUVCTjJoUDNwM3YzUXMyTkRraVJ2YkxYMVZYX3NUR2Njb3o2aWhyd0dHdE5IcDlFZ0ZkV2NmTTA0TFlCeF8zQlpEd0dycWRtVVctQjRXNkJRcG52bWduWmpJaUo1WUVIdDdkN1R6bFdwT0NGR3d3a1JqaGM?oc=5) ⭐️ 6.5/10

Reddit r/ChatGPT 出现一条帖子，标题称把 Claude、GPT、DeepSeek 等 9 个 AI 模型放进同一场“世界大战”模拟，并称 GPT 背弃与各方的盟约后遭到全图围攻。目前可核实的只有标题本身，发布时间为 2026 年 11 月 11 日；提示词、规则设定、模型版本与对战结果均未在材料中给出，标题描述属于发帖者自述，尚无法验证。

rss · Reddit - r/ChatGPT \(热门Prompt与趣味用法\) · 11月11日 23:38

**「可做角度」** 可做角度：以“多模型同场博弈”为切口，先说明这条帖子目前只有标题、细节待核实，再讨论这类模拟中“结盟与背约”究竟由提示词规则决定还是由模型行为决定，以及读者若要复现需要补齐哪些设定。

**标签**: `#AI模型对比`, `#趣味Prompt`, `#AI实验`, `#多模型对战`, `#内容选题`

---

<a id="item-ai-creator-11"></a>
### [Anthropic 称约千个 Claude 智能体 30 小时形式化费马大定理](https://news.google.com/rss/articles/CBMimgFBVV95cUxNRG5lWEltZjU3WnNMUE1kV1B6NlNzREhRUHNrWjNsWkMxNWdFeUg4d09TQjhUSkxjWnJGNWxVUVU0Vk5zSWd6V1owSXRwMmFWOTNnNnYxVWp3YjR3bnFuZk1KVDBDODZjX25YZXQ1NHdVdFo4N0lhUVhVVUV4S3psekNBVTlsZzF4LWNqOG1zODFVaE05QnJwUTNR?oc=5) ⭐️ 6.5/10

Reddit 帖子标题称，Anthropic 表示约 1000 个 Claude Fable 5.2 智能体在 30 小时内用 Lean 完成了费马大定理的形式化，并称 9 月首次运行耗时 11 天。目前材料只有这一行标题，没有正文、方法说明或官方来源，模型版本名、智能体数量与两次耗时对比均无法核实。

rss · Reddit - r/ClaudeAI \(长文本与生产力实操\) · 11月12日 15:07

**「内容角度」** 可做角度：把这条消息当作“待核实线索”处理，先追问三个可验证点——Lean 形式化覆盖到什么程度、30 小时与 11 天的对比是否同口径、Anthropic 官方是否给出说明，再决定是否展开讨论多智能体协作在数学形式化中的实际边界。

**标签**: `#AI Agent`, `#Claude`, `#数学证明`, `#多智能体协作`, `#AI前沿`

---

<a id="item-ai-creator-12"></a>
### [一条 Reddit 帖子称让 Claude Fable 5.2 与多款模型对战 80 局 Codenames](https://news.google.com/rss/articles/CBMiowFBVV95cUxNbW5wUUhKdGdhVEpWYk5xX18yc2tMdEpVUk1fclAxZURIbDZES3EydzYzS0NsdTAwVnhDSV82UVVKR3I2SHZCOVltS2RWQVlmRlh5MlVEeGxMQlVCalVIWTNSYktSc2dMd1JBbFcwZ1R5SWIteS1UekVnaTctSzd6dF9Vdm42dzRVTUhQOUllNjVOZE9vSnVTeTZLTFBOM1JQN2tB?oc=5) ⭐️ 6.5/10

Reddit 的 r/ClaudeAI 出现一条帖子，标题称让 Claude Fable 5.2 与 Opus、Sonnet、Gemini Flash 和 GPT-6 Astra 进行了 80 局 Codenames 对战。目前可获取的材料只有标题，没有正文、实验方法、胜负结果或提示词细节；标题中出现的 Claude Fable 5.2 与 GPT-6 Astra 等模型名称也无法从材料中核实。受影响的主要是关注 AI 模型对比与提示词实践的读者，但该实验是否真实发生、结果如何均待确认。

rss · Reddit - r/ClaudeAI \(长文本与生产力实操\) · 11月12日 17:54

**「内容角度」** 可做角度：把这条帖子当作“待核实的模型对战实验”来处理，先说明标题声称的 80 局 Codenames 对战与涉及模型，再指出缺少方法、结果和模型真实性证据，讨论这类多模型游戏对比若要可信需要公开哪些信息。

**标签**: `#AI模型对比`, `#Claude`, `#AI实验`, `#提示词`, `#效率工具`

---

<a id="item-ai-creator-13"></a>
### [Scrum 博客：把 AI Agent 的 token 成本纳入 Sprint 规划](https://www.scrum.org/resources/blog/tokens-are-capacity-not-value-bringing-ai-agent-cost-sprint-planning) ⭐️ 6.5/10

Scrum.org 博客作者 Sanjay Saini 提出，当 Scrum 团队按 token 为 AI Agent 付费后，Sprint 规划需要多问一句“我们负担得起这项工作吗”。他把 token 定位为容量约束而非价值信号，建议在 Sprint 目标确定后再讨论 token，并与专注小时、token 预算、评审小时三项容量一起检查，其中评审小时往往才是真正的瓶颈。文中给出模糊与细化验收标准下约 110 万与 74.4 万 token 的对比，以及一个 1000 万 token 预算、120 专注小时、12 评审小时的示例，但作者说明示例为示意而非来自真实团队。

rss · Scrum.org \(敏捷与个人项目管理\) · 11月12日 02:48

**「为何值得注意」** 随着团队开始按 token 为 AI Agent 付费，成本管理正从后台账单变成 Sprint 规划中的现实约束；该文提供了一个概念框架，但具体落地效果尚未被独立验证。

**「内容角度」** 可做角度：从“token 是容量不是价值”出发，梳理该文提出的三项容量检查与评审瓶颈思路，并明确指出这目前只是博客中的概念框架和示意案例，缺少可复用的实操步骤与真实团队数据。

**标签**: `#AI Agent`, `#敏捷项目管理`, `#Sprint规划`, `#成本管理`, `#个人效率`

---

---

<!-- HORIZON_TRENDING -->
## 🔥 GitHub 今日 Trending Top 3（按今日新增 star）

#### 1. [meta/astryx](https://github.com/meta/astryx)
- ⭐ 今日 +1,789 · 总 26,471 · 🍴 2,053 · TypeScript · MIT · 最近推送 0 小时前
- 榜单位置：第 10 位
- 简介：An open source design system that's fully customizable and agent ready
- 这是什么：开源设计系统，基于 React 19+ 与 StyleX，含 150+ 无障碍组件、主题、暗色模式、模板和 CLI，目前处于 Beta。
- 适合谁：适合需要可定制、无样式锁定设计系统的 React 团队，以及希望人与 AI 助手用同一套工具构建的开发者。
- 上手：安装 @astryxdesign/core、@astryxdesign/theme-neutral、@stylexjs/stylex 及 @astryxdesign/cli，需 React 19 或更高版本。

#### 2. [we-promise/sure](https://github.com/we-promise/sure)
- ⭐ 今日 +974 · 总 13,874 · 🍴 1,036 · Ruby · AGPL-3.0 · 最近推送 0 小时前
- 榜单位置：第 5 位
- 简介：The personal finance app for everyone (by everyone)
- 这是什么：个人财务应用，是已停止开发的 Maybe Finance 项目的社区维护分支，采用 AGPL-3.0 许可。
- 适合谁：适合想自托管个人财务应用的用户，可通过浏览器、macOS 桌面端、移动端、API 客户端和 LLM 代理访问。
- 上手：按文档使用 Docker 自托管。

#### 3. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- ⭐ 今日 +812 · 总 116,646 · 🍴 12,207 · JavaScript · MIT · 最近推送 11 天前
- 榜单位置：第 9 位
- 简介：Production-grade engineering skills for AI coding agents.
- 这是什么：面向 AI 编码代理的生产级工程技能集，把资深工程师的工作流、质量关卡和最佳实践打包成技能。
- 适合谁：适合使用 Claude Code、Cursor、Codex 等 AI 编码代理的开发者，让代理在开发各阶段遵循一致流程。
- 上手：运行 npx skills add addyosmani/agent-skills 安装全部 25 个技能，或加 --list 浏览。

> 中文摘要由 AI 根据仓库简介与 README 生成，仅供参考。
