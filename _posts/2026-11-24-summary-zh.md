---
layout: default
title: "Horizon Summary: 2026-11-24 (ZH)"
date: 2026-11-24
lang: zh
---

# Horizon 每日速递 - 2026-11-24

> 从 399 条内容中筛选出 13 条重要资讯。

---

**AI 创作者雷达**
1. [Z.ai 发布 GLM-5.4：首个循环 Transformer 模型](#item-ai-creator-1) ⭐️ 7.0/10
2. [豆包个人助理「小豆」开启邀请制公测](#item-ai-creator-2) ⭐️ 7.0/10
3. [datasette-charts 0.2a0 接入 Datasette Agent，可对话生成图表](#item-ai-creator-3) ⭐️ 6.5/10
4. [NariQ 发布 Qwen3.8-27B 低比特量化版本](#item-ai-creator-4) ⭐️ 6.5/10
5. [Wizstar 集成 Kling 4.0 并上线提示词库](#item-ai-creator-5) ⭐️ 6.5/10
6. [ChatGPT 聊天页上线 GPT-6.2 Sol，向付费用户推送](#item-ai-creator-6) ⭐️ 6.5/10
7. [可灵 AI 发布 Kling Image 4.0：主打照片级真实感与原生 8K](#item-ai-creator-7) ⭐️ 6.5/10
8. [Seedeo 称将 Suno 音乐与 AI 视频工具接入 ChatGPT 和 Claude](#item-ai-creator-8) ⭐️ 6.5/10
9. [Sora 2 被指关停：仅有标题，细节待核实](#item-ai-creator-9) ⭐️ 6.5/10
10. [端侧大模型实测报道信息不足，关键细节待核实](#item-ai-creator-10) ⭐️ 6.5/10
11. [用户把项目上下文迁到本地纯文本文件，跨 ChatGPT、Claude 和 Gemini 使用](#item-ai-creator-11) ⭐️ 6.5/10
12. [多模型实时辩论帖：仅标题可查，细节待核实](#item-ai-creator-12) ⭐️ 6.5/10
13. [OpenAI 据称推出 MedChemBench，GPT-6 Astra 得分 83.8%](#item-ai-creator-13) ⭐️ 6.5/10

---

## AI 创作者雷达

<a id="item-ai-creator-1"></a>
### [Z.ai 发布 GLM-5.4：首个循环 Transformer 模型](https://simonwillison.net/2026/Nov/23/glm-54/) ⭐️ 7.0/10

中国 AI 实验室 Z.ai 发布 GLM-5.4，这是其首个采用循环 Transformer 架构的模型。按官方描述，一组权重共享层在一次前向传播中运行多次迭代，在不增加参数量的前提下加深网络。该模型目前未开放权重，也无法通过常规 API 套餐访问，需订阅 Coding Plan 才能调用；作者实测其生成的“骑自行车鹈鹕”图与 GLM-5.3 质量相近，并指出 5.3、5.4 的风格已明显不同于 5.1、5.2。

rss · Simon Willison \(AI工具与提示词实操\) · 11月23日 23:40

**「为何值得关注」** 这是作者一周内第二次看到循环 Transformer 的发布，此前 Thinking Machines Lab 于 11 月 20 日发布的 Inkling 2 Mini 也采用类似架构，称其中间层对每个 token 运行三次。两家实验室接连押注同一架构方向，但 GLM-5.4 的实际性能提升目前尚无独立评测支撑。

**「内容角度」** 可做角度：从“循环 Transformer 一周内两次出现”切入，梳理权重共享迭代这一架构思路，并对照 GLM-5.4 与 Inkling 2 Mini 的公开描述，同时说明目前只有官方说法、缺少可验证的实测数据。

**「社区讨论」** 有评论赞赏智谱公开技术细节的做法，认为循环 Transformer 是顺理成章的方向；也有用户抱怨部分中国模型“马拉松式思考”，在简单任务上反复自我怀疑、完成时间明显更长。这些属于个人体验，不代表普遍结论。

**标签**: `#\#GLM5.4`, `#\#大模型更新`, `#\#循环Transformer`, `#\#AI编程`, `#\#AI前沿`

---

<a id="item-ai-creator-2"></a>
### [豆包个人助理「小豆」开启邀请制公测](https://mp.weixin.qq.com/s/4JBJszozOuJ5Ve5Ca3lHHA) ⭐️ 7.0/10

豆包发文宣布，AI 个人助理产品「小豆」开启公测，公测期间采用邀请制，用户凭邀请码体验，并获赠一定量免费额度。小豆被描述为字节对标 Meta Muse 的个人助理（Personal Agent）独立产品，官方称其能力与体验会逐步在豆包 App 上线。目前公开信息仅为简讯，具体功能、版本号与使用步骤尚未披露。

telegram · zaihuapd · 11月24日 02:41

**「为何值得关注」** 这是字节在个人助理（Personal Agent）方向推出独立产品并进入公测阶段的新动作，且以邀请制加免费额度的方式开放体验；但实际能力与体验细节仍待核实。

**「内容角度」** 可做角度：梳理「小豆」目前可确认的信息边界——邀请制、免费额度、对标 Meta Muse 的定位，以及官方所称将逐步在豆包 App 上线，区分已公布事实与尚未披露的功能细节。

**标签**: `#\#AI个人助理`, `#\#豆包小豆`, `#\#AIAgent`, `#\#免费额度`, `#\#AI工具实测`

---

<a id="item-ai-creator-3"></a>
### [datasette-charts 0.2a0 接入 Datasette Agent，可对话生成图表](https://simonwillison.net/2026/Nov/24/datasette-charts/) ⭐️ 6.5/10

Simon Willison 发布 datasette-charts 0.2a0，新增与 Datasette Agent 的集成：用户可在对话中请求图表，插件会调用同一套图表建议与生成工具直接产出。演示视频在 agent.datasette.io 录制，该站点支持用 GitHub 登录试用。演示中用户输入“\#stats”打开表搜索框，选中 sqlite-utils 下载数据后得到内嵌图表，点击“Open in the chart builder”可在面板中打开图表并切换为 datasette 的图表，随后询问 Agent 时它能识别面板内容变化并描述新图表。

rss · Simon Willison \(AI工具与提示词实操\) · 11月24日 04:24

**「为何值得注意」** 该插件前一天才首次发布，次日即补上 Agent 集成，变化集中在“对话直接生成图表”这一交互上。材料只说明集成已上线并提供试用入口，未给出性能、准确率或适用范围方面的验证。

**「内容角度」** 可做角度：以演示视频中的完整操作链为线索，梳理“对话请求图表—内嵌展示—在图表构建器中切换数据—Agent 识别面板变化”这一流程，说明插件与 Agent 共享图表生成工具后，人机协作的边界落在哪里。

**标签**: `#\#AI Agent`, `#\#数据可视化`, `#\#Datasette`, `#\#开源工具`, `#\#自动化工作流`

---

<a id="item-ai-creator-4"></a>
### [NariQ 发布 Qwen3.8-27B 低比特量化版本](https://huggingface.co/nari-labs/Qwen3.8-27B-NariQ-GGUF) ⭐️ 6.5/10

NariQ 在 Hugging Face 发布 Qwen3.8-27B 的 3-bit 及以下量化版本（3-bit、2.5-bit、2-bit），声称在智能体、数学、多语言推理与图像理解任务上接近 BF16 质量，并称这是首个在长程智能体任务上保持 BF16 水平表现的 3-bit 及以下量化。作者给出 DeepSWE、Terminal-Bench 2.1、AIME 25+26、MSGM、RealWorldQA 的 BF16 与各量化档位对比，以及 RTX PRO 6000 上 4K/16K/64K 上下文的解码速度，并与 Unsloth UD-IQ3\_XXS 对照。运行需使用其 llama.cpp 分支；评论提到 M3 Pro（18 GB）上 3.0bpw 约 3.8 tok/s、2.0bpw 约 4.9 tok/s，远慢于 CUDA。

hackernews · toebee · 11月23日 13:42 · [社区讨论](https://news.ycombinator.com/item?id=50611402)

**「为何值得注意」** 低比特量化正把 27B 级模型推向 16 GB 内存的普通设备，而 NariQ 这次把长程智能体任务纳入对比，回应了“量化只在基准数据集上好看”的常见质疑。不过其基准是否反映真实使用效果、以及 2-bit 档位在 DeepSWE 上明显下滑（28.6 对 BF16 的 39.8），仍需独立验证。

**「内容角度」** 可做角度：以 NariQ 公布的 BF16/3-bit/2.5-bit/2-bit 四档基准为线索，梳理“比特数降到多少开始明显掉点”——重点看 2-bit 在 DeepSWE 上的下滑与 2.5-bit 的相对稳定，并说明这些数字来自作者自测、运行依赖其 llama.cpp 分支，尚非独立复现。

**「社区讨论」** 有评论肯定该项目做了多类长程任务和“held out”检查，认为比常见的高算力 QAT 量化更可信；也有人质疑收益可能来自测试框架差异而非模型本身，并追问文件变小时究竟丢失了什么信息。另有用户报告 Mac 上速度远低于 CUDA，并希望与 Bonsai 2 27B 对比。

**标签**: `#\#本地大模型`, `#\#模型量化`, `#\#Qwen`, `#\#AI工具`, `#\#开源模型`

---

<a id="item-ai-creator-5"></a>
### [Wizstar 集成 Kling 4.0 并上线提示词库](https://news.google.com/rss/articles/CBMi8wFBVV95cUxNMlpwSTFreTctNFBmWnRZTmpLZHNGaWRhM0NVZU4yWm1qc0paMmdpQVNnUUNONVEzNnNtbTdzUzBYb2ZKcXRqRTh5UzZrVWxCanJ0Z005cDNJdU5JYVJfT2VzWjYtS3dYV1Z0YkVHWGRPZjhxXzRpbzZCZWFlaDNHRy1EUmMwX1RGQkxVOWZXV0tjdUpFWVJmQTdpZjNFcVd0UThaMzFZenNZZHp3alpFMURtbU5rdU8xeEYtU0ItT2MySFdscnplMFVUQWpHSUgwVjVvZjM0NkZ1TENpMnhQRXUzWUlkdHp4WFVseDh0NFFjLUk?oc=5) ⭐️ 6.5/10

据 The Des Moines Register 转载的简讯，Wizstar 宣布集成 Kling 4.0，并上线一个提示词库（Prompt Gallery），以扩展其 AI 视频创作能力。目前可确认的信息仅限标题层面：集成对象为 Kling 4.0，新增功能为提示词库；具体功能范围、可用地区、价格与生成效果均未在材料中说明，需以官方发布为准。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月23日 16:01

**「内容角度」** 可做角度：以“集成第三方模型 + 提示词库”这一组合为线索，梳理 AI 视频工具正从单一模型能力竞争转向工作流与素材复用层面的比拼，并明确标注 Wizstar 此次更新的细节尚未公开、效果待验证。

**标签**: `#\#AI视频生成`, `#\#Kling`, `#\#提示词库`, `#\#AI工具更新`, `#\#短视频创作`

---

<a id="item-ai-creator-6"></a>
### [ChatGPT 聊天页上线 GPT-6.2 Sol，向付费用户推送](https://x.com/ChatGPT/status/2124942186425069836) ⭐️ 6.5/10

ChatGPT 官方账号 11 月 23 日宣布，在 Chat 标签页上线 GPT-6.2 Sol 版本，主打日常对话场景，当天起向 Plus、Pro、Business 和 Enterprise 用户推送。官方称新版本在复杂指令处理、联网检索、照片细节识别（如标签文字、路牌符号）、按价格或位置缩小在线选项范围，以及判断何时主动给出后续建议方面有所改进。上述能力描述均来自官方发布，未经独立验证，版本规格、额度与 API 变化等细节尚未披露。

telegram · zaihuapd · 11月24日 00:44

**「为何值得注意」** 这是 ChatGPT 聊天页的一次版本更新，且直接面向付费用户推送，属于已发生的变化；但功能改进目前只有官方口径，实际体验与影响尚待独立验证。

**「内容角度」** 可做角度：梳理官方公布的几项改进（复杂指令、联网检索、图片细节识别、按价格或位置筛选、主动建议），并说明这些均为官方宣传、缺少独立验证，提醒读者关注实际使用中的差异。

**标签**: `#\#ChatGPT更新`, `#\#大模型动态`, `#\#AI提效`, `#\#AI工具测评`, `#\#自媒体选题`

---

<a id="item-ai-creator-7"></a>
### [可灵 AI 发布 Kling Image 4.0：主打照片级真实感与原生 8K](https://news.google.com/rss/articles/CBMiqwFBVV95cUxQQlpTZUg4akVlRjQ5WmFOZ2ItQWxJM1Q5SjZqWVoxUXBXam5WT242cXRER2pmc01FRXBCakljUklQT1phTUdTdTI0QUlIN3BzaWxvSDN1RnZwR0Nfandzajk2Q2hkNlh5MnFMa0FBdUNlOERUSzNsNnVxaFZDQkJqUXdLbDRhS28zbjB3QUVKenRJb2owV1B0d0FKQll2eDlLdXhSenpSdmtzUFk?oc=5) ⭐️ 6.5/10

TMCnet 报道称，可灵 AI（Kling AI）发布图像模型 Kling Image 4.0，主打照片级真实感与原生 8K 生成。目前可获取的信息仅为标题与简讯，具体功能参数、上线时间、价格与实测效果均未披露，需以官方发布信息为准。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月23日 16:02

**「内容角度」** 可做角度：以“原生 8K”为切口，梳理图像生成模型从分辨率堆料转向真实感与可用性的趋势，并明确区分官方宣称与待验证的实测表现。

**标签**: `#\#可灵AI`, `#\#AI图像生成`, `#\#AI视听创作`, `#\#8K生成`, `#\#AI工具更新`

---

<a id="item-ai-creator-8"></a>
### [Seedeo 称将 Suno 音乐与 AI 视频工具接入 ChatGPT 和 Claude](https://news.google.com/rss/articles/CBMingFBVV95cUxQN1ZnQ1dfajgtYkVOY3J3NXhhTUI0VWdUTTlhZUpqUFhmM0pSR3dPakRDaGFEVjkyRlpGTEtQTUhRMFVaclhSQmRfSkVJX0ZYY2V0Q2FJUlNKNF9aOW83Z1NqcWRFd0R4RGNiVUpUeVFiN0ZnM1ZxNzB0Z3hfZExnSDZXcEdvX2IzSS1CYklBYTVXVnNuNnptWTJmaGsyUQ?oc=5) ⭐️ 6.5/10

据 famemagazine.co.uk 报道，Seedeo 宣称把 Suno 音乐与 AI 视频工具接入 ChatGPT 和 Claude。目前可核实的只有这一标题信息，报道未给出具体功能、接入方式、可用范围或实际效果，相关说法仍属 Seedeo 单方面宣称，尚待核实。可能受影响的是希望在对话式 AI 中直接调用音乐与视频生成能力的创作者。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月23日 10:59

**「内容角度」** 可做角度：以“宣称接入”与“可验证细节缺失”之间的落差为线索，梳理这类第三方工具接入 ChatGPT、Claude 时通常需要说明的功能边界与验证方式，并明确标注目前仅有标题信息。

**标签**: `#\#AI视频`, `#\#Suno音乐`, `#\#ChatGPT插件`, `#\#AI工具集成`, `#\#AI视听创作`

---

<a id="item-ai-creator-9"></a>
### [Sora 2 被指关停：仅有标题，细节待核实](https://news.google.com/rss/articles/CBMiqAFBVV95cUxPdElKRTBvbGhnTWxuOU8tSFU0bWk3ZVJ1QmxuUTZ6bVdIcGRRMV84ZzJNN3E3elMxM1hkVk1JWmw4c3pud2J6dXVRTHJVYXd2RFpMYnhlVGZZSkRGM0cweXBieHU5UHpTb3JETVRwYzduSnNGQ3VHeXBaR0V0eldxYWd3NjQzZ3JGWUtsa1h4WDE4ekdjWUM2Z21mbE94MFdpZUFrSnFVcmI?oc=5) ⭐️ 6.5/10

LBB 的一篇报道标题称 Sora 2 已关停，并讨论模型下线对 AI 创意工作的影响。目前材料中只有标题，没有正文细节、关停日期、官方确认或具体原因，受影响范围和实际后果均无法核实。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月23日 09:33

**「内容角度」** 可做角度：以“标题称关停、正文与官方信息缺失”为切入点，梳理一条 AI 视频工具下线消息在缺乏确认时如何被传播，并列出读者需要核实的关键信息（官方公告、生效时间、用户数据与作品处置）。

**标签**: `#\#Sora2`, `#\#AI视频生成`, `#\#AI创作工具`, `#\#行业动态`

---

<a id="item-ai-creator-10"></a>
### [端侧大模型实测报道信息不足，关键细节待核实](https://www.qbitai.com/2026/11/512195.html) ⭐️ 6.5/10

量子位发布一篇实测类报道，标题称国产端侧大模型以 1450 亿参数在笔记本上运行，速度达每秒 80+ Token，并支持断网 Vibe Coding、零 Token 成本。但正文目前仅有一句导语，未给出模型名称、量化方案、硬件配置与实测步骤，上述参数与速度尚无法核实。受影响的是关注本地部署与 AI 编程的开发者，实际可用性有待原文补充。

rss · 量子位 QbitAI \(国内AI前沿与应用\) · 11月23日 11:01

**「内容角度」** 可做角度：以“标题给出的 1450 亿参数、80+ Token/s 与正文仅一句导语”的落差为切口，讨论端侧大模型实测报道应披露哪些最低信息（模型、量化、硬件、测试方法），并说明在细节缺失前不宜把速度数字当作结论。

**标签**: `#\#端侧大模型`, `#\#本地部署`, `#\#VibeCoding`, `#\#AI编程`, `#\#效率工具`

---

<a id="item-ai-creator-11"></a>
### [用户把项目上下文迁到本地纯文本文件，跨 ChatGPT、Claude 和 Gemini 使用](https://news.google.com/rss/articles/CBMioAFBVV95cUxPc2toZVlWRGtOdWM3QlVOQkwyRkRtTlVmTXJ6Sy0wLUpIUFVlVDFQaGlxVjRFM01HZ3diaXc5ZFN3VFo4REZnZFg5UzRsamhYaEJleGpnZ0luOTZBMXZ2MWdMTnBQamdCQi1uTHZfUVBua2JadU4wQkFOMGhHa08wYTBCYUF0VS1WUDk4QWdJdGQ3VzJHVjc0UW1fV3U2ZXFx?oc=5) ⭐️ 6.5/10

一条来自 r/ChatGPT 的 Reddit 帖子标题称，一位累计进行 2,100 多次 AI 会话的用户，把全部项目上下文迁移到本地纯文本文件中，并称这些文件可在 ChatGPT、Claude 和 Gemini 中使用。帖子同时抛出问题：是信任内置记忆，还是自己保存文件。目前只有标题，文件结构、提示词写法和实际效果均未在材料中给出，无法核实。

rss · Reddit - r/ClaudeAI \(长文本与生产力实操\) · 11月23日 12:00

**「为何值得注意」** 该帖把“内置记忆”与“自持本地文件”放在同一场景下对比，涉及跨多个主流聊天工具复用同一份上下文这一实际需求；但材料未提供任何效果验证或可复现细节。

**「内容角度」** 可做角度：以这条只有标题、缺少细节的帖子为引子，讨论“把项目上下文写成纯文本文件、再分别喂给不同聊天工具”这一做法的可行边界——哪些信息适合外置、跨工具复用时哪些部分需要重写，并明确说明原帖未公开文件结构与效果。

**标签**: `#\#AI记忆管理`, `#\#本地文件工作流`, `#\#ChatGPT`, `#\#Claude`, `#\#效率工具`

---

<a id="item-ai-creator-12"></a>
### [多模型实时辩论帖：仅标题可查，细节待核实](https://news.google.com/rss/articles/CBMingFBVV95cUxOOThjandOZTF5dENNT2Y3aUwwN2xXazRneVFaclF0eU5vQ0lIVVVrZ1ZBTjdnX1QzWXBtckJOaTBGc0hqeUROTzJGSFY5MVNyMjBuRXAxRWhqSU9Nako5djhMU1VVakpaa3E0TzhyR2dsd2drQmhoUlVvMkJVUldoVFRfdnBDaXQ3RWlMSnJZbnpJZ0syYXh1SlBGTFBiUQ?oc=5) ⭐️ 6.5/10

Reddit r/ChatGPT 出现一条帖子，标题称让 GPT-6.2 Sol 与 Claude Opus 5.5 实时互相辩论，并由 Gemini Pro 担任裁判，向读者提问“你觉得谁赢了”。目前可获取的材料只有标题和同一内容的另一条链接，没有正文、提示词、辩论流程或最终判定结果；标题中出现的模型版本名称也无法从材料中核实。受影响的主要是关注多模型对比与提示词玩法的读者，他们暂时无法据此复现或判断效果。

rss · Reddit - r/ChatGPT \(热门Prompt与趣味用法\) · 11月23日 18:22

**「内容角度」** 可做角度：把“多模型辩论+第三方裁判”当作一种提示词玩法来拆解，先说明这条帖子目前只有标题、版本名与结果均未证实，再讨论这种玩法需要交代哪些要素（辩题、轮次、裁判标准、是否同屏实时）才算可复现的实测。

**标签**: `#\#AI提示词`, `#\#多模型对比`, `#\#AI辩论`, `#\#趣味玩法`, `#\#大模型实测`

---

<a id="item-ai-creator-13"></a>
### [OpenAI 据称推出 MedChemBench，GPT-6 Astra 得分 83.8%](https://news.google.com/rss/articles/CBMimgFBVV95cUxPN2JUZ2U0T2thcWhybzJFaFptTW0wVnBxZ0NCZ21DaE1KaW8tdXYtVi1wbUI0NUY4LWFtX0NQVW10bkYyYWdiaUhDbVhTS2pzZmFpOXpxYVpaRFg3TEp4TnBkQVVJWXhWSG1Pay1KR2ZZRUJucU5WeS0xNEZjNjdicmNodFctd3Q5VWxIeDFoTTVMWm45WURyaUtn?oc=5) ⭐️ 6.5/10

据 Reddit r/OpenAI 的一条简讯，OpenAI 据称推出了名为 MedChemBench 的基准，用于测试 AI 在真实药物化学决策上的表现，并称 GPT-6 Astra 在该基准上取得 83.8% 的成绩。目前材料只有标题，没有正文，因此评测方法、样本构成、对比基线以及 83.8% 的具体含义都尚未核实。受影响的主要是关注 AI 医疗应用与大模型评测的读者。

rss · Reddit - r/OpenAI \(官方动态与用户反馈\) · 11月23日 15:03

**「内容角度」** 可做角度：先不急着转述 83.8% 这个数字，而是把它当作一个待核实的信号，梳理一个药物化学基准要回答哪些问题——题目来自真实决策还是简化题、由谁标注、分数如何计算——再判断这个成绩能说明什么。

**标签**: `#\#AI基准测试`, `#\#OpenAI`, `#\#AI医疗`, `#\#大模型评测`, `#\#AI前沿`

---

---

<!-- HORIZON_TRENDING -->
## 🔥 GitHub 今日 Trending Top 3（按今日新增 star）

#### 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- ⭐ 今日 +2,029 · 总 20,191 · 🍴 2,127 · Python · MIT · 最近推送 2 小时前
- 榜单位置：第 1 位
- 简介：A Claude Code skill bundle for bug hunting and external red-team work - 84 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.
- 这是什么：面向漏洞挖掘与外部红队工作的 Claude Code 技能包，含 84 个技能、15 个斜杠命令、681 条披露报告模式。
- 适合谁：适合漏洞赏金猎人与红队人员，用于按主题自动加载检测模式、链式模板与报告规范。
- 上手：在 Claude Code 内执行 /plugin marketplace add elementalsouls/Claude-BugHunter 后安装插件。

#### 2. [XiaoYouChR/Ghost-Downloader-3](https://github.com/XiaoYouChR/Ghost-Downloader-3)
- ⭐ 今日 +1,087 · 总 16,633 · 🍴 1,003 · Python · GPL-3.0 · 最近推送 4 小时前
- 榜单位置：第 15 位
- 简介：The only downloader you need. 下载器的集大成者。
- 这是什么：跨平台下载管理器，支持 HTTP、BT/磁力、FTP、M3U8、MPEG-DASH、eD2k 等协议。
- 适合谁：适合需要统一管理多协议下载、视频站点下载与浏览器接管下载的用户。
- 上手：README 未给出

#### 3. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- ⭐ 今日 +924 · 总 208,159 · 🍴 10,875 · TypeScript · AGPL-3.0 · 最近推送 3 小时前
- 榜单位置：第 6 位
- 简介：Knowledge infrastructure to make your agents smarter. Search, scrape and access 550+ data providers through one API.
- 这是什么：将网站转为干净 markdown 的知识基础设施，提供本地版、云服务与自托管服务器及 SDK。
- 适合谁：适合需要为 AI 代理提供网页抓取、爬取、站点映射与搜索能力的开发者。
- 上手：cargo install firecrawl-local 安装本地版，或用 npx firecrawl-cli 抓取页面。

> 中文摘要由 AI 根据仓库简介与 README 生成，仅供参考。
