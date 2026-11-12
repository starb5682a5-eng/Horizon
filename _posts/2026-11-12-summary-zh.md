---
layout: default
title: "Horizon Summary: 2026-11-12 (ZH)"
date: 2026-11-12
lang: zh
---

# Horizon 每日速递 - 2026-11-12

> 从原始资讯中去重并归纳合并出 11 条高价值核心情报。

---

**AI 创作者雷达**
1. [Peter Yang 用可复用 AI 技能串联 ChatGPT、Claude Code 与 GroqBot 管理一人业务](#item-ai-creator-1) ⭐️ 7.0/10
2. [LangChain 披露 GTM Agent 12 周生成 1540 份销售物料](#item-ai-creator-2) ⭐️ 7.0/10
3. [谷歌发布 Gemini Decisions API：多模态决策模型定价与 GPT-6 Luna 相同](#item-ai-creator-3) ⭐️ 7.0/10
4. [Claude API 新增按消息动态调整 effort 等级](#item-ai-creator-4) ⭐️ 7.0/10
5. [AWS 推出官方本地服务模拟器 aws-emulator](#item-ai-creator-5) ⭐️ 6.5/10
6. [Knightvision 将 AI 广告工作室迁至新域名并接入 Claude 与 ChatGPT](#item-ai-creator-6) ⭐️ 6.5/10
7. [字节跳动据报拟推 AI Agent 对标 Meta Muse](#item-ai-creator-7) ⭐️ 6.5/10
8. [AI agent 声称发现未记录玛雅遗址，作者更新称该遗址此前已被发现](#item-ai-creator-8) ⭐️ 6.5/10
9. [Runway 发布 Praxis-1：从视频理解世界并控制机器人](#item-ai-creator-9) ⭐️ 6.5/10
10. [Reddit 用户称测试 7 个 GPT Image 2.6 GIF 提示词](#item-ai-creator-10) ⭐️ 6.5/10
11. [首部 AI 院线电影票房遇冷：千万成本与 180 万票房的落差](#item-ai-creator-11) ⭐️ 6.5/10

---

## AI 创作者雷达

<a id="item-ai-creator-1"></a>
### [Peter Yang 用可复用 AI 技能串联 ChatGPT、Claude Code 与 GroqBot 管理一人业务](https://www.youtube.com/watch?v=pvl3z_GyU2Y) ⭐️ 7.0/10

Matt Wolfe 发布了一段访谈视频，介绍 Peter Yang 如何用个人 AI 系统管理自己的一人业务：系统包含“AI 幕僚长”、帮助他聚焦目标的个人顾问，以及用于播客调研、视频剪辑、内容创作和日常任务的自动化工作流。视频称这些流程通过可复用的 AI 技能连接 ChatGPT、Claude Code 和 GroqBot，并演示了如何搭建类似工作流、如何用“技能编辑器”持续改进技能。材料未披露具体版本、价格、开源代码或免费额度，实际效果与可复制性尚待验证。

rss · YouTube - Matt Wolfe \(AI工具全网测评\) · 11月11日 16:00

**「为何值得关注」** 这条内容把 AI Agent 从单点工具演示推进到“一人公司”的整套运营流程，并给出可跟随搭建的演示，对关注 AI 工作流落地的创作者有参考价值。但视频目前只是访谈与演示，尚无独立评测或量化收益数据。

**「内容角度」** 可做角度：拆解 Peter Yang 这套“AI 幕僚长 + 个人顾问 + 定时机器人”的分工结构，重点讲清可复用技能如何在 ChatGPT、Claude Code 和 GroqBot 之间流转，以及他在哪些环节保留人工判断。

**标签**: `#\#AI Agent`, `#\#一人公司`, `#\#自动化工作流`, `#\#Claude Code`, `#\#效率工具`

---

<a id="item-ai-creator-2"></a>
### [LangChain 披露 GTM Agent 12 周生成 1540 份销售物料](https://www.langchain.com/blog/gtm-agent-high-quality-sales-artifacts) ⭐️ 7.0/10

LangChain 博客介绍其内部 GTM Agent：过去 12 周生成 1540 份销售物料（账户计划、价值证明文档、提案演示、上线计划等），每周超过 100 份，其中发给客户的物料合计节省 337 小时人工。厂商自述称，发送过该类物料的交易推进到后续阶段的比例为 47%，匹配的未发送交易为 16%；46% 的物料在 14 天内伴随一次客户通话。文章强调质量主要来自业务上下文（销售流程、客户通话记录、品牌规范、阶段门槛）而非提示词调优，并称可在 Deep Agents 上复刻，Managed Deep Agents 已内置沙箱、技能与记忆。上述效果数据均为厂商自述，尚无独立验证。

rss · LangChain Blog \(AI Agent与工作流\) · 11月12日 03:34

**「为何值得关注」** 文章把“上下文优先于提示词调优”落到具体工程细节：品牌规范以代码形式进入沙箱镜像、渲染后自检、以及“一次审查无实质缺陷即发布”的停止规则，使单页文档生成从 18 分钟降到 7 分钟。这些是可复用的方法描述，但 47% 对 16% 的转化差异属于厂商自述的匹配对比，不能视为因果结论。

**「内容角度」** 可做角度：拆解 LangChain 所说的“质量来自上下文而非提示词”，逐项对照它列出的流程知识、客户上下文、品牌规范三类输入，以及沙箱自检加停止规则如何同时影响质量与延迟，并明确标注效果数字为厂商自述。

**标签**: `#\#Agent工作流`, `#\#AI销售提效`, `#\#DeepAgents`, `#\#提示词工程`, `#\#一人公司`

---

<a id="item-ai-creator-3"></a>
### [谷歌发布 Gemini Decisions API：多模态决策模型定价与 GPT-6 Luna 相同](https://simonwillison.net/2026/Nov/11/gemini-decisions-api/) ⭐️ 7.0/10

谷歌发布 Gemini Decisions API，基于新模型 Gemini Decision 1，支持 yes/no、choice、rubric-scoring 三类决策题型，并覆盖文本、图像、音频、视频和 PDF 多模态输入。定价为每百万输入 token 10 美分、输出免费，与 GPT-6 Luna 决策模型相同，但高于 Jev 的每百万 4.2 美分。作者用一段机器人视频做了 yes/no 测试，Gemini 返回的是概率值（如机器人 0.923、龙 0.0498），而非 Jev 和 OpenAI 那样的 1.0/0.0；材料未给出效果结论，实际表现待核实。

rss · Simon Willison \(AI工具与提示词实操\) · 11月11日 22:03

**「为何值得关注」** 决策模型这一品类此前已有 Jev 和 OpenAI 入局，谷歌此次以多模态覆盖作为差异点加入；但材料只展示了单次视频测试的返回格式，尚未证实其在真实场景中的准确率与稳定性。

**「内容角度」** 可做角度：对比三家决策模型在同一个视频 yes/no 问题上的输出差异——Jev 和 OpenAI 给 1.0/0.0，Gemini 给概率值，讨论这种“不那么自信”的输出对下游判断逻辑意味着什么。

**标签**: `#\#Gemini`, `#\#AI决策模型`, `#\#API定价对比`, `#\#多模态AI`, `#\#AI工具实操`

---

<a id="item-ai-creator-4"></a>
### [Claude API 新增按消息动态调整 effort 等级](https://platform.claude.com/docs/en/build-with-claude/effort-per-message) ⭐️ 7.0/10

Anthropic 为 Claude API 推出 Beta 功能，允许在对话中途按消息调整后续回答的 effort 等级：在消息中插入一条空内容的 system 消息并设置 output\_config.effort，无需改动顶层配置，提示缓存仍可命中。新等级从下一条带新输入的用户消息起生效。该功能需携带 beta 头 mid-conversation-output-config-2026-07-01，材料称支持 Fable 5.2、Opus 5.5、Sonnet 5.5、Haiku 5.5 等模型及 Amazon Bedrock、Google Cloud、Azure 等平台，具体版本与头信息需以官方文档核实。

telegram · zaihuapd · 11月12日 00:58

**「为何值得关注」** 此前 effort 等级通常需在顶层配置中设定，此次变化让开发者能在同一会话内按任务阶段切换努力等级，同时保留提示缓存命中，对长对话与成本敏感场景有实际意义。材料未给出性能或成本的具体量化影响。

**「内容角度」** 可做角度：从“插入空内容 system 消息 + output\_config.effort”这一实现细节出发，演示如何在长对话中按阶段切换 effort 并验证提示缓存仍命中，同时说明 beta 头、生效时机与支持范围。

**标签**: `#\#ClaudeAPI`, `#\#大模型更新`, `#\#AI开发`, `#\#提示缓存`, `#\#API技巧`

📌 **同日该 AI 其他重要动态汇总**：
- **Reddit 用户称用 Claude 做出开源逐音符作曲 skill**：一位 Reddit 用户（r/ClaudeAI）发帖称，自己借助 Claude 制作了开源 skill「music-skill」，目标是让 AI 逐音符作曲。帖子称用 5 个模型各生成一次、共得到 7 首作品，每首只给一个提示、一次生成、未做剪辑。目前材料只有标题，没有仓库链接、实现步骤、参数或试听信息，实际效果与可复现性均待核实。 [原题](https://news.google.com/rss/articles/CBMiowFBVV95cUxONDExMng3Y25Fenc0NHVteFF3MXNoNkhoMDRrVmNheUZPODZWTHBVb3IxWVlndDJpcXdTYUVNU2RJVGlPWkF5djNqR29KTlhSMXFrR2wtV0V3NGJNekVBdjl3QWRUZ0o5dGRvYmwzanNzS2h3WXpjV1RSUklKbUY4U2Q2X3NmTDg3eWRiVVVheTM4RElyVjh3bXlUOFRrclBTSjVZ?oc=5)
- **Reddit 用户称用 Claude Code 自建 Mac 任务队列 Untether，免费 MIT 开源**：Reddit r/ClaudeAI 出现一条帖子，作者称用 Claude Code 自建了 Mac 端任务队列工具 Untether：agent 在 worktree 中并行工作，经过评审与测试后自动合并，用户可在手机上远程查看进度。帖子标注该工具免费、以 MIT 协议开源。目前材料只有标题，没有正文细节，具体实现方式、实际效果与可用性均待核实。 [原题](https://news.google.com/rss/articles/CBMinwFBVV95cUxQbXBiS0g5M3hwaDBfekxZN20tbDJYQm9lcGZPbkRUbHM2Ny11YjBodk4xTDgtWm1mRjR1dFRQQzVrQ0RBQVhKNFF2cEZTUjZENFBqU0hYSnFUMlZPdkpLYko0SU9wY25VbjBDTWU0c25qeWtfN2E3TmtSLXlFUklUbWxQLUYtX3ZlVkNrTlloMC15UklsMi1tcTZLdUVWUTQ?oc=5)

---

<a id="item-ai-creator-5"></a>
### [AWS 推出官方本地服务模拟器 aws-emulator](https://simonwillison.net/2026/Nov/11/aws-emulator/) ⭐️ 6.5/10

AWS 发布了官方本地服务模拟器 aws-emulator，目标是让开发者无需申请付费 API key，就能在本地对 AWS 多项服务运行测试。该项目用 Rust 编写，据 Simon Willison 转述，项目前三周由大量 AI 智能体协作产生了 29,684 次提交；Swaminathan Sivasubramanian 在 Werner Vogels 博客的客座文章中介绍了它的由来。目前 macOS 和 Windows 上运行仍需 Docker，作者希望未来能改为单个二进制文件，以便在其他语言和平台的测试套件中直接使用。

rss · Simon Willison \(AI工具与提示词实操\) · 11月11日 21:18

**「为何值得注意」** 这是 AWS 官方推出的本地模拟器，直接回应了本地测试需要付费 API key 的痛点；同时它以“大量智能体在三周内完成近 3 万次提交”的方式开发，为 AI 智能体参与工程协作提供了一个具体案例。不过材料只给出简短导语，具体工作流、覆盖的服务范围和实际测试效果尚未展开。

**「内容角度」** 可做角度：以 aws-emulator 为样本，梳理“智能体大规模提交代码”这一开发模式的可验证细节与待核实之处——哪些信息来自官方博客、哪些只是转述，以及 Docker 依赖和单二进制诉求对测试场景的实际限制。

**标签**: `#\#AI编程`, `#\#Agent工作流`, `#\#AWS`, `#\#开源工具`, `#\#AI提效`

---

<a id="item-ai-creator-6"></a>
### [Knightvision 将 AI 广告工作室迁至新域名并接入 Claude 与 ChatGPT](https://news.google.com/rss/articles/CBMi6gFBVV95cUxQSm1EdVQ1RC05bEpPeEhHUDZ3aEVQdUZJanFJcGFrUTdJX0c5cjMtREM3OWZyb1FQQUpUejBGYVFLS2wwQTlhTUNaMVRaNXBYdHNMUXdNWE52bU85VGhIcXZfTEgxUk52UWlwbmZncEk2ZlZaWnVGX3NqMlM2Mk95UGN4ZlZFMHJLbUNleUxDdGxQTzlkakJyTHNEbnFPcU9NU2xjZVhkT3F3SFlfT0QzcWt3RTR2QnZwWGt1OUxvVFl1UndGREJTUjJMU2tkQlBKR1BNWHZteV9MRHZObzhqOXlBZzBmVHVCa3c?oc=5) ⭐️ 6.5/10

据 StreetInsider 的一则简讯，Knightvision 将其 AI 广告工作室迁移至 knightvision.ai，并称把广告创作功能接入 Claude 与 ChatGPT。目前仅有标题信息，未见正文说明集成方式、可用范围、是否收费或具体效果，相关细节仍待核实。受影响的主要是使用 AI 工具制作广告素材的营销与内容团队。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月11日 13:07

**「可做角度」** 可做角度：以“AI 广告工具开始嵌入通用聊天入口”为线索，梳理这条简讯中已确认的两点变化——域名迁移与接入 Claude、ChatGPT，并明确标注集成形态、定价与效果均未披露，避免把厂商说法当作已验证能力。

**标签**: `#\#AI广告`, `#\#Claude`, `#\#ChatGPT`, `#\#AI视频`, `#\#AI工具集成`

---

<a id="item-ai-creator-7"></a>
### [字节跳动据报拟推 AI Agent 对标 Meta Muse](https://news.google.com/rss/articles/CBMi4AFBVV95cUxNSVlLbDAwMnp2cUhSYTB2M0RYd0dKNkJpRENIYU93UVpqZWlWdW5fczE1RWFwcXdCbU1LVzJmSms0ZktwZVhHOG1FNnF3Q2J2dGdyVzlqM0RJQVFRelJjX0hGVzFPdXNnOGZVTW91MGxhOHRRRHdmc3RpSEdNalF5Q2Yxa2U1bmdzY1BuLVBKM1ZjVmM1UHFzallvbGpKdklsUDloU04zOHh4Q21DS3lFR2tkNk9STS1HbGIyWWJrdnRzVXdma0FGUC1KVTduQXNLc0lIV0xZdm41M1I3QzllaA?oc=5) ⭐️ 6.5/10

据 TradingView 转载的一则报道，字节跳动计划推出与 Meta 的 Muse 相竞争的 AI Agent，并可能在数周内发布。该报道目前仅有标题，未披露产品名称、具体功能、发布时间、定价或可用范围等可验证细节，相关计划仍待核实。若消息属实，受影响的主要是关注 AI Agent 产品动态的开发者和企业用户。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月11日 14:08

**「为何值得注意」** 目前可确认的仅是“有报道称字节跳动计划在数周内推出对标 Meta Muse 的 AI Agent”这一说法，尚无官方确认或产品细节；其实际能力与市场影响均未得到证实。

**「内容角度」** 可做角度：以“只有标题的竞争传闻”为切口，梳理这条报道明确说了什么、缺失了哪些关键信息（功能、时间、形态），并说明在官方信息出现前不宜把它当作已确定的产品发布。

**标签**: `#\#AI Agent`, `#\#字节跳动`, `#\#AI资讯`, `#\#大模型动态`, `#\#科技快讯`

---

<a id="item-ai-creator-8"></a>
### [AI agent 声称发现未记录玛雅遗址，作者更新称该遗址此前已被发现](https://pietromiotti.com/latest/maya-site) ⭐️ 6.5/10

Hacker News 上出现一篇题为“My AI agents found an unmapped Maya site?”的帖子，作者称其 AI agent 发现了未记录的玛雅遗址。但材料中没有原文正文，只有标题与评论。作者在评论中更新称，该遗址此前已被发现，并提到它出现在某处记录中（评论被截断）。评论者 LordOmlette 也指出该遗址更早被发现，并给出 Bluesky 链接，称墨西哥政府可能没有正确记录。因此，“AI agent 首次发现遗址”这一说法目前不成立，实际是 AI 工具指向了一处已有记录的遗址。

hackernews · eyvindn · 11月11日 12:05 · [社区讨论](https://news.ycombinator.com/item?id=50452455)

**「为何值得注意」** 这条讨论值得注意的地方在于：它把 AI agent 用于 LiDAR 考古筛查的可行性，与“发现是否为新”的验证问题放在了一起。作者已承认遗址此前已被发现，但 AI 工作流本身是否有效、能否复现，材料中都没有说明。

**「内容角度」** 可做角度：以作者本人“遗址此前已被发现”的更新为切口，讨论 AI agent 在考古发现中的角色边界——它能加速筛查候选地点，但“是否为新发现”仍需依赖既有记录与考古专家核实，而不是由 agent 的结论直接认定。

**「社区讨论」** 评论整体对 AI 辅助 LiDAR 考古持积极态度，有人分享英国 LiDAR 地图多年来的实际发现，也有人提醒考古学家的人力有限，发现速度可能超过核实与保护能力。另有评论者对 AI agent 的结论持保留态度，认为需要专家考古学家验证，并担心受访者面对 Google 工程师及其 48 个 agent 时不敢质疑。

**标签**: `#\#AI考古`, `#\#AI Agent`, `#\#LiDAR`, `#\#AI应用案例`, `#\#科技人文`

---

<a id="item-ai-creator-9"></a>
### [Runway 发布 Praxis-1：从视频理解世界并控制机器人](https://news.google.com/rss/articles/CBMiYEFVX3lxTE1COG9ROXpJQy1LcmwyUE5mcUc5LU1ua1NqRW0tUmNZVXE3X3BpZWVNdmVScHZ3VWRiYVZqSV9EVmExb1lWNUt6ZkVzbzdIdFhEcTEtS3NRc09pYkV4NGJWMA?oc=5) ⭐️ 6.5/10

据 GIGAZINE 报道，以视频生成见长的 Runway 公布了一款名为 Praxis-1 的模型，称其能从视频中理解世界并用于控制机器人。目前可核实的信息仅限于这一标题级描述，报道未给出模型参数、训练数据、机器人平台、演示效果或发布时间等细节，实际能力与落地范围均待确认。潜在关注者是具身智能与机器人研究者、以及关注视频模型向物理世界延伸的从业者。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月12日 04:45

**「为何值得注意」** 值得注意的变化是 Runway 从视频生成跨向“视频理解＋机器人控制”这一方向；但这一转向目前只有厂商层面的公布，尚无第三方验证或技术细节支撑，因此不宜据此判断其性能或行业影响。

**「内容角度」** 可做角度：把这条消息当作“待核实线索”处理，梳理视频生成公司切入具身智能时通常需要交代的关键信息（数据来源、动作输出形式、评测方式），并明确指出 Runway 此次公布中缺失了哪些环节。

**标签**: `#\#Runway`, `#\#AI视频`, `#\#具身智能`, `#\#AI前沿`, `#\#机器人`

---

<a id="item-ai-creator-10"></a>
### [Reddit 用户称测试 7 个 GPT Image 2.6 GIF 提示词](https://news.google.com/rss/articles/CBMioAFBVV95cUxPQ2h3bEowYnN3NFhlMTFBV1VRSUNZY18yMmtySE5qeWJRcU83Xy1MbTczaDRoTHQ0Q1liTGVRUld4OFhtNXlIV0JxUUR2OFhHYnpzNmZ6MERhRUVYT3U4bFJSTzZDczFKeG1kSkd5b3lVcVAwMVlPd3h4cTg4R2JQMkh3NDhJbGQya0tYb3NZZVI3a1ZfSTM1UEo0WW9DTzE5?oc=5) ⭐️ 6.5/10

Reddit r/ChatGPT 出现一条帖子，标题称作者在 GPT Image 2.6 上测试了 7 个 GIF 提示词，并附上每个提示词对应的原始照片。标题把该模型描述为 ChatGPT 新 GIF 功能背后的模型。目前材料只有标题，没有正文、具体提示词、操作步骤或生成效果，因此这些测试内容与模型版本说法均待核实。

rss · Reddit - r/ChatGPT \(热门Prompt与趣味用法\) · 11月12日 01:45

**「内容角度」** 可做角度：以“只有标题、没有正文”为切入点，说明这条帖子目前能确认的只是有人声称做了 7 组图生 GIF 提示词测试，并讨论在缺少提示词和结果的情况下，如何判断这类分享的可参考性。

**标签**: `#\#GPTImage`, `#\#AI绘图`, `#\#GIF生成`, `#\#提示词`, `#\#ChatGPT`

---

<a id="item-ai-creator-11"></a>
### [首部 AI 院线电影票房遇冷：千万成本与 180 万票房的落差](https://www.huxiu.com/article/4905038.html?f=rss) ⭐️ 6.5/10

国内首部运用 AI 技术制作并取得公映许可证的院线电影《三星堆：未来往事》上映 21 天累计票房 180.2 万元，11 月 11 日单日票房仅 0.39 万元。影片 10 月 23 日至 25 日首映三日单日票房分别为 30.07 万、46.44 万和 37.96 万元，随后断崖式下跌。制片人披露制作成本为千万元级别，团队近百人、打磨两年、生成 120 余万张底图；博纳方面称此次未把票房设为第一目标，而是摸索 AI 制作路径。

rss · 虎嗅网 \(商业科技与AI创投\) · 11月12日 08:55

**「为何值得关注」** 这是国内首部拿到公映许可证的 AI 院线电影，其票房表现首次为“AI 能否进入院线长片”提供了可验证的市场反馈。同时，11 月 10 日金鸡百花电影节首次设立电影 AI 单元，展映 20 部 AI 相关作品，说明行业投入仍在加码，而商业化回报尚未被验证。

**「内容角度」** 可做角度：把“成本降了、票房没起来”作为切口，梳理这部影片中 AI 承担生成执行、真人负责创意判断的分工，对照豆瓣差评里“表情失真、声画不贴”与“台词剧情混乱”两类问题，讨论 AI 院线电影当前卡在技术能力还是创作环节。

**标签**: `#\#AI电影`, `#\#AI视听创作`, `#\#AI短剧`, `#\#行业观察`, `#\#内容创作`

---

---

<!-- HORIZON_TRENDING -->
## 🔥 GitHub 今日 Trending Top 3（按今日新增 star）

#### 1. [meta/astryx](https://github.com/meta/astryx)
- ⭐ 今日 +2,776 · 总 25,720 · 🍴 1,999 · TypeScript · MIT · 最近推送 0 小时前
- 榜单位置：第 1 位
- 简介：An open source design system that's fully customizable and agent ready
- 这是什么：Meta开源的设计系统，基于React 19+和StyleX，含150+无障碍组件、主题与CLI，目前处于Beta。
- 适合谁：适合需要可定制、可组合组件库的React开发者，以及希望人与AI助手使用同一套工具构建界面的团队。
- 上手：安装@astryxdesign/core、主题包和@stylexjs/stylex，并安装@astryxdesign/cli，需React 19以上。

#### 2. [we-promise/sure](https://github.com/we-promise/sure)
- ⭐ 今日 +1,078 · 总 13,315 · 🍴 983 · Ruby · AGPL-3.0 · 最近推送 1 小时前
- 榜单位置：第 7 位
- 简介：The personal finance app for everyone (by everyone)
- 这是什么：个人财务应用，是已停止开发的Maybe Finance项目的社区维护分支，采用Ruby和AGPL-3.0许可。
- 适合谁：适合想自行托管个人财务管理工具的用户，可通过浏览器、桌面端、移动端、API客户端和LLM代理访问。
- 上手：按docs/hosting/docker.md使用Docker自托管。

#### 3. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- ⭐ 今日 +787 · 总 116,243 · 🍴 12,178 · JavaScript · MIT · 最近推送 11 天前
- 榜单位置：第 5 位
- 简介：Production-grade engineering skills for AI coding agents.
- 这是什么：面向AI编码代理的生产级工程技能集，将工作流、质量关卡和最佳实践打包为技能。
- 适合谁：适合使用Claude Code、Cursor、Codex等AI编码代理的开发者，让代理在开发各阶段遵循统一流程。
- 上手：运行npx skills add addyosmani/agent-skills安装全部25个技能，或加--list浏览。

> 中文摘要由 AI 根据仓库简介与 README 生成，仅供参考。
