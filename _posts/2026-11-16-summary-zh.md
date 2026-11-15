---
layout: default
title: "Horizon Summary: 2026-11-16 (ZH)"
date: 2026-11-16
lang: zh
---

# Horizon 每日速递 - 2026-11-16

> 从原始资讯中去重并归纳合并出 7 条高价值核心情报。

---

**AI 创作者雷达**
1. [美团开源 LongCat-2.5：1.6 万亿参数，称全程用华为升腾训练](#item-ai-creator-1) ⭐️ 8.0/10
2. [华为云上线开源盘古模型 openPangu-2.1-Pro](#item-ai-creator-2) ⭐️ 7.0/10
3. [Sora 替代方案盘点仅见标题，细节待核实](#item-ai-creator-3) ⭐️ 6.5/10
4. [WorkBuddy 国际版称 Gemini 4 Carbon 面向 Pro 用户上线](#item-ai-creator-4) ⭐️ 6.5/10
5. [A2E AI 推出视频图像一体化生成器](#item-ai-creator-5) ⭐️ 6.5/10
6. [Adobe Firefly“安全 AI”定位受质疑，细节待核实](#item-ai-creator-6) ⭐️ 6.5/10
7. [Reddit 用户称用 Claude Code 搭建 AI Agent 测试框架并自审出 73 条发现](#item-ai-creator-7) ⭐️ 6.5/10

---

## AI 创作者雷达

<a id="item-ai-creator-1"></a>
### [美团开源 LongCat-2.5：1.6 万亿参数，称全程用华为升腾训练](https://the-decoder.com/meituan-releases-a-1-6-trillion-parameter-agent-model-that-never-touched-an-nvidia-gpu/) ⭐️ 8.0/10

美团 LongCat 团队在模型正式发布一周后公布了 LongCat-2.5 的权重。该模型面向可自主完成冗长、多步骤任务的智能体，尤其针对编程场景；官方称训练全程使用华为升腾加速卡，未使用英伟达 GPU。模型总参数 1.6 万亿、每 token 激活约 480 亿参数，支持文本、图像和视频输入，以 MIT 许可证发布、可商用。在 Terminal Bench v2.1 上得分 88.4，略低于 Claude Opus 5 的 89.1。

telegram · zaihuapd · 11月15日 11:08

**「为何值得关注」** 开源权重刚落地，且“全程国产芯片训练”的说法与接近头部闭源模型的编程基准成绩同时出现，构成当前讨论的焦点。需要说明的是，训练未用英伟达 GPU 目前仅为官方表述，材料未提供第三方验证；88.4 与 89.1 的差距也仅来自单一基准。

**「内容角度」** 可做角度：把“官方称全程升腾训练”与“Terminal Bench v2.1 上 88.4 对 89.1”放在一起，梳理这条开源模型在国产算力叙事与智能体编程能力两条线上的实际位置，并明确哪些是官方说法、哪些还缺独立验证。

**标签**: `#\#AI大模型`, `#\#开源模型`, `#\#AI Agent`, `#\#国产芯片`, `#\#编程提效`

---

<a id="item-ai-creator-2"></a>
### [华为云上线开源盘古模型 openPangu-2.1-Pro](https://mp.weixin.qq.com/s/8JfFmscBTDl_mPQMycD8Nw) ⭐️ 7.0/10

11 月 15 日，华为云 MaaS 模型即服务平台上线开源盘古模型 openPangu-2.1-Pro，围绕 Agent 开发、AI 编码和推理优化三大方向升级能力。材料称该模型基于 10 万余条专项数据优化 Skills 触发与工具调用，重点适配鸿蒙 ArkTS 开发、升腾算子生成，并接入智果 AgentArts、码道 CodeArts、果办 OfficeAce 等产品。定价为推理输入 0.8 元/百万 tokens、输出 3.2 元/百万 tokens、缓存命中输入 0.016 元/百万 tokens；具体实测效果与开源仓库地址尚待核实。

telegram · zaihuapd · 11月15日 16:03

**「为何值得关注」** 这是盘古系列以“开源”形式上线华为云 MaaS 平台的一次版本更新，并给出了明确的 token 定价，对关注国产大模型 Agent 与编码能力的开发者有直接参考价值。不过材料未提供开源仓库地址，实际能力与开源范围仍需进一步确认。

**「内容角度」** 可做角度：从“开源 + 华为云 MaaS 定价”切入，梳理 openPangu-2.1-Pro 在 Agent 工具调用、鸿蒙 ArkTS 与升腾算子生成上的适配点，并对照其输入 0.8 元、输出 3.2 元、缓存命中 0.016 元每百万 tokens 的价格，说明开发者实际接入前需要核实哪些信息（如开源仓库地址与实测效果）。

**标签**: `#\#盘古大模型`, `#\#AI Agent`, `#\#AI编码`, `#\#国产大模型`, `#\#AI工具实测`

---

<a id="item-ai-creator-3"></a>
### [Sora 替代方案盘点仅见标题，细节待核实](https://news.google.com/rss/articles/CBMiT0FVX3lxTFBPbkFCSURIUXA3OTF5UXlLRXRic3JXd2hpWV85c1Z2QmE0OXV1bXNfWHlGUXBaSk9iOFI4VG5BQ0hMUDZHclJWdDJ3d1hpYUk?oc=5) ⭐️ 6.5/10

Fello AI 发布了一篇题为《Best Sora Alternatives in 2026: What Replaced Each Part of Sora》的文章，发布时间为 2026 年 11 月 15 日。目前可获取的材料只有标题和来源，没有正文内容，因此文中具体列出哪些替代工具、按 Sora 的哪些功能逐项对比、结论如何，均无法确认。受影响的主要是关注 AI 视频生成工具选型的创作者。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月15日 06:05

**「内容角度」** 可做角度：先不转述结论，而是把“逐项替代 Sora”这个框架本身当作观察对象——等拿到正文后，核对它把 Sora 拆成了哪几个能力维度、每个维度对应推荐了谁，再判断这份盘点是否有可验证的依据。

**标签**: `#\#AI视频生成`, `#\#Sora替代方案`, `#\#AI工具盘点`, `#\#视频创作`, `#\#AI前沿`

---

<a id="item-ai-creator-4"></a>
### [WorkBuddy 国际版称 Gemini 4 Carbon 面向 Pro 用户上线](https://x.com/WorkBuddy_AI/status/2121671972077838506) ⭐️ 6.5/10

WorkBuddy 国际版在社交平台宣布，Gemini 4 Carbon 已上线并供 Pro 计划用户使用，定位为更深入的推理和更长任务处理。该消息目前仅为一句简讯，未给出模型参数、版本细节、官方链接或实测结果，具体规格与实际效果仍待核实。受影响的主要是使用 WorkBuddy 国际版 Pro 计划的用户。

telegram · zaihuapd · 11月15日 09:17

**「内容角度」** 可做角度：以“只有一句上线公告”为切口，梳理这条消息中可确认的信息（模型名、Pro 用户可用、推理与长任务定位）与缺失的信息（参数、版本号、实测、官方来源），提醒读者区分厂商宣传口径与可验证事实。

**标签**: `#\#Gemini`, `#\#大模型更新`, `#\#AI工具`, `#\#AI提效`, `#\#科技资讯`

---

<a id="item-ai-creator-5"></a>
### [A2E AI 推出视频图像一体化生成器](https://news.google.com/rss/articles/CBMi4AFBVV95cUxPc2Y4Ykp5eWQ1VlZHc2Rja09OYTF4Y1YzUUZpZHBBNi1mUDNtVG1IRmVpVmNsNlFCWm50cllPcmlNXzcta0Z1Rll3Q2pzN2pwZ29iRjY3SURuTmVTZC1FdXFNc010X3NLNkpobUotbGRpTzlMRW1OcFVfMWo5QkpGMWYxLUZhc2MwQno1WUFkQVFjbkM4cXJtMmd1eFZJb2RJdWtfQTRicnlCbHBEVlV6WFZWc0k5Mk90SjZEa1RSNTNLZTY3WWlLcm1GdHlIQkdta3dZM0lJR2F1QjVQYlM5Y9IB5gFBVV95cUxOOE9nalh2b2RNWnpHNlZyZ0VFeU0yMkp3YTN3Z1ZMa2t6TXExamVsTnJ6QVc1QV9IWng4OWV5Tmk5ZG5lcTNlTWRHU1ZsY1MyaFR0ZWJEaWNaN2poSUZ6ZFdFemRIM1A2SEs5alZaRFYwZHFRa1Fnc2hvUzFvZk9wbmpVeEpXN2dBc0VFdGZJcHc3dmdoWmhzcjZqS3dtTVhMOUlJZElxVENENllYN3B0NFdMZnJkSzFEdDhvNjlIRTZVUXFjSjNsbENyamJ0aWZUNHMyRWVoNHVxWWVES3pNcjlNRXBFUQ?oc=5) ⭐️ 6.5/10

据 The Manila Times 报道，A2E AI 推出一款 AI 视频生成器，宣称将视频模型与图像模型整合在同一产品中。目前可核实的信息仅限于标题层面：报道未提供具体功能、模型参数、生成效果、价格或可用地区等细节，这些均有待核实。受影响的主要是关注 AI 视频生成工具的视频创作者与内容团队。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月15日 10:28

**「内容角度」** 可做角度：以“一体化视频+图像模型”这一产品定位为线索，梳理 A2E AI 目前公开可查的信息边界——哪些是已宣布的，哪些仍缺参数与实测，并对比同类工具通常披露的信息项，帮读者判断这条发布消息的实际信息量。

**标签**: `#\#AI视频生成`, `#\#AIGC工具`, `#\#AI工具测评`, `#\#视频创作`, `#\#自媒体选题`

---

<a id="item-ai-creator-6"></a>
### [Adobe Firefly“安全 AI”定位受质疑，细节待核实](https://news.google.com/rss/articles/CBMirwFBVV95cUxNLVMyQkF3S1Q1ekNaOXRFeThmbmotX3FCakFqM2NaTHNkNTQxWXV4TXhsOW51bVJrNHFGNHMteC1oMzZLcWhrY2pYc1JuUy1LSmZWeGxTdlZCZjNTUk9yTDlWOWtNUTJMM3kyUENCcmFOMkpTOWs0MG50NGY5THY2elNVenJLZDdNc0ZGZHdmM21aUmVhVnFMMm9JemRIWnZITjZNemxJMWJtOHY4VkFZ?oc=5) ⭐️ 6.5/10

Creative Bloq 发布了一篇标题为《Adobe Firefly was supposed to be the safe AI option – so what&\#x27;s changed?》的文章，质疑 Adobe Firefly 此前被视作“安全 AI 选项”的定位是否已经发生变化。目前可获取的信息只有标题与来源，文章正文、具体变化内容、涉及的产品版本或时间节点均未提供，因此无法确认其质疑依据。可能受影响的是关注生成式 AI 工具合规性与版权风险的内容创作者。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月15日 14:00

**「内容角度」** 可做角度：以“安全 AI”这一标签为线索，梳理 Adobe Firefly 对外定位的公开表述与此次标题所指向的疑问之间的张力，并明确说明目前仅有标题、具体变化尚待原文核实，不做结论性判断。

**标签**: `#\#AdobeFirefly`, `#\#AI视频生成`, `#\#AI工具`, `#\#生成式AI`, `#\#内容创作`

---

<a id="item-ai-creator-7"></a>
### [Reddit 用户称用 Claude Code 搭建 AI Agent 测试框架并自审出 73 条发现](https://news.google.com/rss/articles/CBMinwFBVV95cUxQR01WLWE3LTZZTmhkbTZ3dmFoUUt0YzlHMVRVWENERWdGU1lnTVpSTG12Smh5bmFGVm1BbWxpSGREdGVBQWYweTVJS29jTURPX3NveHY3YXJ2dlJzdmI5QnFMdFplX3FYV0FHLUhYeHY4U0pnNTY2SndCbVdfZmFyYkoyZ0lyNnJwSHl1WVpnZ09kRnplWFhNdXFMcVE4SFk?oc=5) ⭐️ 6.5/10

Reddit 用户发帖称，自己用 Claude Code 搭建了一个 AI Agent 测试框架，并让该框架审查自身工作，产出 73 条发现，其中 4 条属于误判通过。目前材料只有标题和简讯，没有正文、实现步骤或可复现细节，框架的具体做法与效果仍待核实。受影响的主要是关注 Claude Code 与 AI Agent 测试实操的开发者。

rss · Reddit - r/ClaudeAI \(长文本与生产力实操\) · 11月15日 15:15

**「内容角度」** 可做角度：围绕“让测试框架审查自己的产出”这一做法，讨论 AI Agent 自审时 73 条发现里出现 4 条误判通过意味着什么，以及在没有公开实现细节的情况下，这类自审结果应如何被验证。

**标签**: `#\#ClaudeCode`, `#\#AIAgent`, `#\#测试框架`, `#\#AI编程`, `#\#效率工具`

📌 **同日该 AI 其他重要动态汇总**：
- **用 Claude Code 做的首个 App 收到 4.3 垃圾信息与 4.2.6 审核结果**：一位 Reddit 用户称，自己借助 Claude Code 完成了首个 App，但上架审核收到 4.3（垃圾信息）和 4.2.6 两项结果，并向社区询问回复 Apple 的提问是否对他人有效。材料仅有标题，未提供 App 类型、审核原文、回复内容及最终结果，具体细节与效果均待核实。[原题](https://news.google.com/rss/articles/CBMingFBVV95cUxQd3BoQTVYX1E2Ql9kcjNVbnlKSWJNZ0xXZlRBODBEMjhXeDBEN2h6MWJEZHpxeG9IMTBnZUF4RllKV3RlNW5pem1EOC1mYVVPdkdHVmNLZUZDN0xOdkYxTWJGekd3ZkVLUGZRM2ZmYWJYX3paUUhIMDVzRjhnaTBKMjhOME41YnJhLXl0aTJ3TUl3TUd4X0szWDlfZUtmQQ?oc=5)
- **Reddit 用户称用 Fable 5.2 与 Claude Opus 5.5 构建 3D 工作坊 Replicator**：Reddit r/ClaudeAI 出现一条帖子，标题称作者用 Fable 5.2 和 Claude Opus 5.5 构建了名为 Replicator 的 3D 工作坊。目前可获取的材料只有标题，没有正文、实现步骤、功能范围或效果说明，标题中提到的两个工具版本均无法从现有材料核实，项目实际完成度和可用性仍待确认。[原题](https://news.google.com/rss/articles/CBMiogFBVV95cUxPMlVBc2ZuSmZWdlg1a0pMV2tNQ1BPQUR4NVBMbFlzQjZBbE1vYjYzcmE4UEgwaVkwY2VhNGJOQU5sb2Rua2s4Y3lhdEhfZzkwTk1YbW1QSmUxUXFNNmRRX1MxLU1Nc2lyMWZLUzlxdGZRUzRObTdsTTBPRzBFRnR6MGNPZXl5al83Q0Q0dC1rd2dKeEJyVlJXYkZvanZnOTUwRnc?oc=5)

---

<!-- HORIZON_TRENDING -->
## 🔥 GitHub 今日 Trending Top 3（按今日新增 star）

#### 1. [GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src)
- ⭐ 今日 +1,220 · 总 7,119 · 🍴 597 · TypeScript · Apache-2.0 · 最近推送 11 小时前
- 榜单位置：第 10 位
- 简介：Keep your coding agent up to date with the latest web best practices
- 这是什么：Modern Web Guidance 的源仓库，包含编写、校准和评估该内容的代码与文档；该内容是一组嵌入编码代理的 Web 平台技能。
- 适合谁：对希望编码代理避免旧模式、采用现代 Web 平台方案的开发者有用。
- 上手：运行 npx modern-web-guidance@latest install 执行交互式安装向导。

#### 2. [dream-num/univer](https://github.com/dream-num/univer)
- ⭐ 今日 +1,041 · 总 25,586 · 🍴 2,334 · TypeScript · Apache-2.0 · 最近推送 6 小时前
- 榜单位置：第 1 位
- 简介：Build your own AI office with Univer Office SDK. Bring editing, calculation, collaboration, and file processing into your product for people and AI agents. Built on an extensible open-source core.
- 这是什么：Univer Office SDK，用于在自有产品中构建 Office 应用，提供编辑、计算、协作和文件处理，覆盖表格、文档、演示等。
- 适合谁：对想把 Office 编辑与协作能力集成进产品、面向用户和 AI 代理的开发者有用。
- 上手：README 未给出

#### 3. [backnotprop/plannotator](https://github.com/backnotprop/plannotator)
- ⭐ 今日 +860 · 总 11,815 · 🍴 1,082 · TypeScript · Apache-2.0 · 最近推送 0 小时前
- 榜单位置：第 4 位
- 简介：The workspace to stay in the loop and on top of agents - shape, decide, plan, annotate, review code, share with team, and send all feedback to agents with one click.
- 这是什么：面向 AI 编码代理的本地浏览器评审界面，可标注计划、规格、Markdown、HTML 等产物，并评审代码差异和 PR。
- 适合谁：对使用 Claude Code、Codex 等编码代理、需要标注并向代理回传反馈的开发者有用。
- 上手：运行 plannotator inbox 启动 Plannotator Inbox。

> 中文摘要由 AI 根据仓库简介与 README 生成，仅供参考。
