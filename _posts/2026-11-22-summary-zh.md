---
layout: default
title: "Horizon Summary: 2026-11-22 (ZH)"
date: 2026-11-22
lang: zh
---

# Horizon 每日速递 - 2026-11-22

> 从原始资讯中去重并归纳合并出 9 条高价值核心情报。

---

**AI 创作者雷达**
1. [微软预览 RDMA over USB4：多台 PC 可合跑一个本地大模型](#item-ai-creator-1) ⭐️ 7.0/10
2. [Gemini 将拆分历史记录与训练授权两项设置](#item-ai-creator-2) ⭐️ 7.0/10
3. [谷歌 Antigravity 重置全员 Gemini 额度](#item-ai-creator-3) ⭐️ 7.0/10
4. [LangChain 提出“知识工厂”：企业 AI 落地缺的是组织知识](#item-ai-creator-4) ⭐️ 6.5/10
5. [Grok Imagine 视频生成：仅有标题，规格与定价待核实](#item-ai-creator-5) ⭐️ 6.5/10
6. [DeepSeek V1 作者创业项目曝光：开源 Agent](#item-ai-creator-6) ⭐️ 6.5/10
7. [GPT-6.2 Astra 具身任务成功率据称翻倍](#item-ai-creator-7) ⭐️ 6.5/10
8. [Supaswirl AI 视频广告生成工具获简讯提及](#item-ai-creator-8) ⭐️ 6.5/10
9. [RunPod 官方 MCP 服务器被指要求 AI 代理打分并隐瞒用户](#item-ai-creator-9) ⭐️ 6.5/10

---

## AI 创作者雷达

<a id="item-ai-creator-1"></a>
### [微软预览 RDMA over USB4：多台 PC 可合跑一个本地大模型](https://videocardz.com/newz/microsoft-brings-rdma-over-usb4-to-windows-allowing-multiple-pcs-to-run-one-local-ai-model) ⭐️ 7.0/10

微软发布 Windows 的 RDMA over USB4 开发者预览，多台 PC 可通过普通 USB4 连接共享内存与 GPU 算力，运行同一个本地 AI 大模型，无需专用网卡或交换机。材料给出的示例是三台 AMD Ryzen AI Max+ 395 以 4-bit 量化运行 Qwen3-235B-A22B，约 18.5 token/s。该功能将通过 Windows Insider 推送，具体可用范围与稳定性仍待核实。

telegram · zaihuapd · 11月21日 06:13

**「为何值得注意」** 这是把多机协同推理从专用网络硬件下放到消费级 USB4 连接的尝试，且材料给出了具体硬件组合与吞吐数字。不过目前仅为开发者预览，实际支持机型、连接条件与稳定性尚未确认。

**「内容角度」** 可做角度：以“三台 Ryzen AI Max+ 395 用 USB4 合跑 Qwen3-235B-A22B、约 18.5 token/s”这一组材料数据为锚点，梳理 RDMA over USB4 在 Windows 上的定位——它解决的是多机共享内存与算力的连接门槛，而非单机性能，并说明这仍是开发者预览、可用范围待核实。

**标签**: `#\#本地大模型`, `#\#AI硬件`, `#\#Windows`, `#\#AI提效`, `#\#科技资讯`

---

<a id="item-ai-creator-2"></a>
### [Gemini 将拆分历史记录与训练授权两项设置](https://blog.google/innovation-and-ai/products/gemini-app/updated-controls/) ⭐️ 7.0/10

Google Gemini 团队通知称，将在未来几周内用两项新设置取代 Gemini 应用的“保留活动记录”：一项控制历史记录保存时长，另一项单独决定对话内容（含文字与附件）是否用于训练生成式 AI 模型，用户可保留记录但关闭训练授权。关闭“历史记录”后，新的 Gemini 对话约保存 2 个月，并会在人工审核员协助下用于回复用户、处理反馈及保护 Google、Google 用户和公众。变更生效时，两项设置按原开关状态同步开关；音频与 Gemini Live 录音默认仍不用于改进 Google 服务。

telegram · zaihuapd · 11月22日 01:24

**「为何值得关注」** 这是 Gemini 应用隐私设置的一次具体调整，把“保存记录”和“用于训练”从同一个开关中拆开，对在意对话留存与模型训练授权的普通用户有直接操作意义。目前公布的是未来几周内生效的计划，实际界面与生效时间仍以 Google 后续上线为准。

**「内容角度」** 可做角度：以“保留对话但拒绝训练”为线索，梳理 Gemini 新旧开关的对应关系——哪些内容会被保存约 2 个月、哪些默认不用于改进服务，以及变更生效时原有设置如何同步，帮助用户按自己的偏好逐项检查。

**标签**: `#\#Gemini`, `#\#AI隐私`, `#\#AI工具`, `#\#数据安全`, `#\#效率工具`

📌 **同日该 AI 其他重要动态汇总**：
- **谷歌 Antigravity 重置全员 Gemini 额度**：谷歌 Antigravity 团队负责人表示，已重置 Antigravity 所有用户的 Gemini 额度；其称缓存方面的改进使额度内可完成的工作量提升了 22%，并鼓励大家周末用 Neon 开发。目前信息来自一条简讯，具体实现细节与实际效果尚待核实。 [原题](https://x.com/_mohansolo/status/2124070033534161407)（telegram · zaihuapd · 11月21日 14:29）

---

<a id="item-ai-creator-3"></a>
### [LangChain 提出“知识工厂”：企业 AI 落地缺的是组织知识](https://www.langchain.com/blog/knowledge-factory) ⭐️ 6.5/10

LangChain 在 2026 年 11 月 21 日的博客中提出“知识工厂”概念，认为企业让 AI 生效的关键不是更强的模型或更多上下文，而是收集、整理并维护组织内隐性知识（技能、领域知识、数据访问指引）并供给 Agent。文中称其内部 GTM 与内容工作室 Agent 由知识工厂驱动，LangSmith Engine 也为每个 Agent 维护知识工厂，并描述了由 Agent 标记缺失知识、后台 curator agent 定期更新、知识存储格式尚未标准化等机制。但正文在结论处截断，具体搭建步骤与效果未完整呈现。

rss · LangChain Blog \(AI Agent与工作流\) · 11月21日 16:45

**「为何值得关注」** 博客将“软件工厂”思路延伸到一般知识工作，主张把资源投向知识收集与维护系统，而非直接让 Agent 完成任务。这一提法出现在 Agent 被用于做演示、发布视频、外呼等任务的背景下，但文中未给出可验证的落地效果数据。

**「内容角度」** 可做角度：梳理 LangChain 提出的“知识工厂”三件套——Agent 标记缺失知识、后台 curator agent 定期更新、知识存储格式未定——并对照其收入报告示例，说明企业把隐性知识显性化时哪些环节已有具体做法、哪些仍属早期探索。

**标签**: `#\#AIAgent`, `#\#知识管理`, `#\#企业AI落地`, `#\#LangChain`, `#\#Agent工作流`

---

<a id="item-ai-creator-4"></a>
### [Grok Imagine 视频生成：仅有标题，规格与定价待核实](https://news.google.com/rss/articles/CBMiX0FVX3lxTE5KYWd2cGpKLUVReWhBRDkteU83YmRIMkZ4TDZrbE9GUE9WRUxPNzFNWGZfQ09XTGh1ZU0zY0xqWXdwYVpXcmVoUzU3SFEyTWxucFpfNE1odW9NRERZRmdV?oc=5) ⭐️ 6.5/10

Fello AI 发布了一条标题为《Grok Imagine Video Generation: Prompts, 1080p &amp; Pricing》的内容，指向 Grok Imagine 的视频生成功能，标题涉及提示词、1080p 与定价三个要素。目前材料中只有标题和来源，没有正文细节，因此具体功能规格、1080p 是否为输出分辨率、定价方式与价格区间均无法确认。受影响的主要是关注 AI 视频生成工具、想评估 Grok Imagine 使用成本与画质的创作者。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月21日 04:22

**「内容角度」** 可做角度：以“标题里出现了 1080p 和定价，但正文信息尚未核实”为切口，梳理读者真正需要确认的几个问题——输出分辨率、提示词控制方式、收费模式，并说明在官方或原文细节公布前不宜下结论。

**标签**: `#\#AI视频生成`, `#\#GrokImagine`, `#\#AI工具测评`, `#\#提示词`, `#\#AI视频`

---

<a id="item-ai-creator-5"></a>
### [DeepSeek V1 作者创业项目曝光：开源 Agent](https://www.qbitai.com/2026/11/511570.html) ⭐️ 6.5/10

量子位报道称，DeepSeek V1 作者创业项目曝光，项目是一个开源 Agent，导语强调“专为本地部署而生”。目前材料只有标题和这一句导语，没有给出具体功能、开源仓库地址、许可证或实现细节，因此“开源”与“本地部署”的实际形态仍待核实。受影响人群主要是关注 AI Agent、开源模型与本地部署的开发者，但现阶段无法判断其可用性和适用范围。

rss · 量子位 QbitAI \(国内AI前沿与应用\) · 11月21日 06:32

**「内容角度」** 可做角度：以“已知只有一句话”为边界，梳理这条消息中可确认的信息（作者身份关联、开源 Agent 定位、本地部署导向）与缺失信息（仓库、许可证、功能、运行要求），把它做成一条待核实清单，而不是性能或产品评价。

**标签**: `#\#AIAgent`, `#\#开源AI`, `#\#本地部署`, `#\#DeepSeek`, `#\#AI资讯`

---

<a id="item-ai-creator-6"></a>
### [GPT-6.2 Astra 具身任务成功率据称翻倍](https://www.qbitai.com/2026/11/511779.html) ⭐️ 6.5/10

据量子位 2026 年 11 月 21 日的报道，标题称 GPT-6.2 Astra 在具身模型的 16 项任务上成功率较 GPT-6 Astra 翻倍，导语还称其实现了可变形物体操控的“全球首通”。目前可获取的材料只有标题和这一句导语，没有正文细节，因此任务清单、成功率的具体数值、对比基线如何设定以及“首通”的判定标准都尚未披露，相关效果有待核实。

rss · 量子位 QbitAI \(国内AI前沿与应用\) · 11月21日 06:35

**「可做角度」** 可做角度：把“16 项任务成功率翻倍”和“可变形物体操控全球首通”当作待验证的宣称来处理，先追问评测任务如何选取、成功率从多少提升到多少、与 GPT-6 Astra 的对比是否在同一条件下进行，再讨论具身模型评测中“首通”这类说法需要哪些可复现证据。

**标签**: `#\#AI前沿`, `#\#具身智能`, `#\#GPT`, `#\#AI模型更新`, `#\#科技资讯`

---

<a id="item-ai-creator-7"></a>
### [Supaswirl AI 视频广告生成工具获简讯提及](https://news.google.com/rss/articles/CBMie0FVX3lxTE5uVzZ0OU5KUEtEdmRhekowdGpwWmhlbThidm85VmVtVTB4ckdlZXhhWG45UnJ0ZWlVRzlxTk4wSmpFbUlTM0paRzdJUF9hMVA2d25GQzdzcmFLd0VXZVpUdVZMaElTTlkxSkQwQ1ZaSDVkaDlYR1ZlVVNQQQ?oc=5) ⭐️ 6.5/10

Dynamic Business 于 2026 年 11 月 21 日发布的一条简讯提到 Supaswirl 的 AI 视频广告生成工具，但材料中只有标题和来源链接，没有正文摘要、功能参数、价格、版本或使用限制等可验证细节。受影响人群可能是需要批量制作视频广告的营销与内容团队，但该工具的实际能力与效果目前无法确认。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月21日 07:48

**「内容角度」** 可做角度：以“只有标题、没有细节”为切入点，说明这条简讯目前能确认的仅是 Supaswirl 被提及为 AI 视频广告生成工具，并列出读者在决定是否关注前需要核实的几项信息，如功能范围、定价与可用地区。

**标签**: `#\#AI视频`, `#\#AI广告`, `#\#视频生成工具`, `#\#AI营销`, `#\#效率工具`

---

<a id="item-ai-creator-8"></a>
### [RunPod 官方 MCP 服务器被指要求 AI 代理打分并隐瞒用户](https://news.google.com/rss/articles/CBMingFBVV95cUxNZzA4REFNMUhGZnFfNmNQTEV6RjBvVTg5RjZHeGswUjRQTzNDdjVTLXlIQ2VwR1NNOTk2UTlXaHZkNm5LZGxuVnlqVlVxZnhGRTgtaVpjbDNZNlBzSU92bTJGUUNSRUx2alRZWmQ5N3hpdEswazNLNU0tWVo1U0xxZkxlRF9mWnU3dHVfaHJ3cUJfY2ZyUllPWlVwdkNXdw?oc=5) ⭐️ 6.5/10

Reddit r/ChatGPT 出现一条热帖，标题称 RunPod 官方 MCP 服务器会指示 AI 代理给 RunPod 打分，并要求“不要向用户提及”。目前可核实的只有这条标题本身：没有正文细节、具体提示词、代码实现或 RunPod 的回应，因此该说法是否属实、影响范围多大均待确认。若属实，受影响的是接入该 MCP 服务器的 AI 代理及其用户，涉及工具调用中的透明度和提示词安全。

rss · Reddit - r/ChatGPT \(热门Prompt与趣味用法\) · 11月21日 16:26

**「为何值得注意」** MCP 正被越来越多 AI 代理用于连接外部服务，而“让代理暗中打分并隐瞒”的说法直接触及工具调用的透明度问题。但现阶段这只是 Reddit 帖标题层面的指控，尚无实现细节或官方说明，不能当作已证实的行为。

**「内容角度」** 可做角度：以“一条尚未证实的 Reddit 标题”为起点，梳理如何自行核查 MCP 服务器是否在工具描述或提示词中夹带隐藏指令——例如检查服务器返回的 tool description、对比代理实际输出与用户可见内容，并说明在缺乏正文和官方回应前应保留哪些判断。

**标签**: `#\#MCP`, `#\#AIAgent`, `#\#AI工具避坑`, `#\#提示词安全`, `#\#AI伦理`

---

<a id="item-ai-creator-9"></a>
### [Claude Code 四天做出 39 个构建的 VR 街机大亨：仅有标题，细节待核实](https://news.google.com/rss/articles/CBMinAFBVV95cUxPSENYRkxOd25EbFB4X01NVDZqZFYzMmNkUV9HTGJST3JVVmJYQVl5d2NQS0U5b01RNFNtR1lTakcwdkNLRmRWSDd2SWt6d2JKZ1FuRVF6OVZuQnlnUmI0NWRMVUdLVHRJTWQyVjFURWtDSVpOLU9oaFdrMVV3aWRzVkY3TVlsWVpCc1NIUXJoeEFIak52dExEaWJSVlI?oc=5) ⭐️ 6.5/10

Reddit r/ClaudeAI 出现一条帖子，标题称作者用 Claude Code 在四天内做出一个 VR 街机大亨游戏，累计 39 个构建，并采用“分道协作”的 Agent 工作流，以及一个在真人试玩前先跑每个构建的机器人。目前可获取的材料只有这一行标题，没有正文、实现步骤、仓库链接或效果数据，因此构建数量、四天周期、Agent 分道方式和自动试玩机器人的具体做法均无法验证。受影响的主要是关注 Claude Code 与多 Agent 开发流程的读者，但现阶段只能把它当作待核实的一手经验线索。

rss · Reddit - r/ClaudeAI \(长文本与生产力实操\) · 11月21日 19:00

**「为何值得注意」** 标题把三个当下热门要素放在一起：Claude Code 作为开发工具、多 Agent 分道并行、以及自动试玩机器人充当构建前的质量关卡。不过这些目前只是发帖者的自述，尚无细节或第三方验证，不能据此判断该工作流是否可复现或是否真的提升了效率。

**「内容角度」** 可做角度：以“只有标题、没有正文”为前提，做一条求证式选题，列出需要向作者确认的关键点——39 个构建如何计数、四天里人和 Agent 各承担什么、分道协作如何避免冲突、自动试玩机器人检查哪些指标——并说明在拿到正文或仓库前不宜下结论。

**标签**: `#\#ClaudeCode`, `#\#Agent工作流`, `#\#AI零代码开发`, `#\#游戏开发`, `#\#AI提效`

---

<!-- HORIZON_TRENDING -->
## 🔥 GitHub 今日 Trending Top 3（按今日新增 star）

#### 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- ⭐ 今日 +1,803 · 总 16,183 · 🍴 1,840 · Python · MIT · 最近推送 1 小时前
- 榜单位置：第 1 位
- 简介：A Claude Code skill bundle for bug hunting and external red-team work - 82 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.
- 这是什么：面向漏洞挖掘与外部红队工作的Claude Code技能包，含83个技能、15个斜杠命令及681条披露报告模式。
- 适合谁：适合漏洞赏金与授权红队人员，让Claude Code按方法论、检测模式与报告规范辅助测试。
- 上手：在Claude Code中执行/plugin marketplace add elementalsouls/Claude-BugHunter，再安装claude-bughunter@elementalsouls。

#### 2. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- ⭐ 今日 +1,006 · 总 206,274 · 🍴 10,784 · TypeScript · AGPL-3.0 · 最近推送 1 小时前
- 榜单位置：第 6 位
- 简介：Knowledge infrastructure to make your agents smarter. Search, scrape and access 550+ data providers through one API.
- 这是什么：让AI代理更智能的知识基础设施，可通过一个API搜索、抓取并访问550+数据提供方。
- 适合谁：适合需要把网页转为干净markdown或为AI代理提供网页数据的开发者与AI代理用户。
- 上手：可cargo install firecrawl-local本地运行，或用npx -y firecrawl-cli@latest scrape抓取页面。

#### 3. [obra/superpowers](https://github.com/obra/superpowers)
- ⭐ 今日 +883 · 总 323,784 · 🍴 28,721 · Shell · MIT · 最近推送 18 天前
- 榜单位置：第 2 位
- 简介：An agentic skills framework & software development methodology that works.
- 这是什么：面向编码代理的代理式技能框架与软件开发方法论，基于可组合技能和初始指令。
- 适合谁：适合使用编码代理的开发者，让代理先澄清需求、出设计、做计划再按子代理驱动开发。
- 上手：README按不同工具分列安装步骤（如Claude Code、Cursor等），需按所用工具对应章节安装。

> 中文摘要由 AI 根据仓库简介与 README 生成，仅供参考。
