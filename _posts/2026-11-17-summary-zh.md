---
layout: default
title: "Horizon Summary: 2026-11-17 (ZH)"
date: 2026-11-17
lang: zh
---

# Horizon 每日速递 - 2026-11-17

> 从原始资讯中去重并归纳合并出 10 条高价值核心情报。

---

**AI 创作者雷达**
1. [腾讯混元发布 Hy4 flash：224B 总参、12B 激活，API 大幅降价](#item-ai-creator-1) ⭐️ 7.5/10
2. [LangSmith 围绕 Agent 重构产品](#item-ai-creator-2) ⭐️ 7.0/10
3. [Qwen4-Max 上线：2.4 万亿参数、API 降价，小模型后续开源](#item-ai-creator-3) ⭐️ 7.0/10
4. [豆包工作上线「工作台」，首批覆盖 21 个专业场景](#item-ai-creator-4) ⭐️ 7.0/10
5. [datasette-maplibre 0.1a0 发布：单条提示词生成的地理空间插件](#item-ai-creator-5) ⭐️ 6.5/10
6. [OpenAI 公布 ChatGPT 科研侧双动作：1800 名科学家调查 + 学术研究者计划扩至 20 万人](#item-ai-creator-6) ⭐️ 6.5/10
7. [Alphr 发布 Adobe Firefly、Runway、Kling 三款 AI 视频工具对比文章](#item-ai-creator-7) ⭐️ 6.5/10
8. [韩媒评 AI 电影《Raphael》：视觉亮眼，剧情欠新意](#item-ai-creator-8) ⭐️ 6.5/10
9. [MiniMax 2026 定价汇总文章出现，细节待核实](#item-ai-creator-9) ⭐️ 6.5/10
10. [Reddit 帖称追踪 28 个模型训练截止日期，15 个未公开](#item-ai-creator-10) ⭐️ 6.5/10

---

## AI 创作者雷达

<a id="item-ai-creator-1"></a>
### [腾讯混元发布 Hy4 flash：224B 总参、12B 激活，API 大幅降价](https://mp.weixin.qq.com/s/5yBbf-ctYziM5r0i6Y17lA) ⭐️ 7.5/10

腾讯混元发布 Hy4 flash，总参数 224B、激活 12B，支持多模态与 1M 上下文。官方称其综合效果略优于 Hy4 preview，WorkIndex 单任务成本为 Hy4 preview 的 1/13、Hy4 的 1/20。该模型已在腾讯云 TokenHub、WorkBuddy、元宝上线，并计划开源；API 定价为每百万 Token 输入 0.5 元、输出 2 元，命中缓存时输入仅 0.02 元，11 月 30 日前 WorkBuddy 限免、API 五折。

telegram · zaihuapd · 11月16日 07:17

**「为何值得关注」** 此次更新同时给出参数规模、上下文长度与具体 API 价格，并附带限时免费与折扣窗口，对关注日常任务成本的使用者有直接参考价值。效果对比与成本倍数为官方口径，尚待独立验证。

**「内容角度」** 可做角度：以官方公布的 224B 总参/12B 激活、1M 上下文和每百万 Token 输入 0.5 元、输出 2 元的定价为线索，梳理 Hy4 flash 相对 Hy4 preview 的成本变化，并标注“效果略优”“成本 1/13、1/20”均为官方说法、待实测。

**标签**: `#\#腾讯混元`, `#\#大模型更新`, `#\#API降价`, `#\#AI工具`, `#\#开源模型`

---

<a id="item-ai-creator-2"></a>
### [LangSmith 围绕 Agent 重构产品](https://www.langchain.com/blog/we-rebuilt-langsmith-around-the-agent) ⭐️ 7.0/10

LangChain 在官方博客中说明，LangSmith 已重构为以 Agent 为核心的统一平台，把构建、运行、改进和治理四个环节连接到同一个 Agent 记录上。每个记录包含负责人、全局唯一且不可变的 ID 和类型三项属性，同一 Agent 的本地、开发、预发和生产环境归入同一 ID 下。平台目前提供通用型和编码型两类 Agent，语音型在路线图中；对运行在其他平台、支持 OTLP 的 Agent，也可接入后统一注册和度量。材料为厂商博客，具体功能细节与量化效果尚未给出。

rss · LangChain Blog \(AI Agent与工作流\) · 11月16日 18:37

**「为何值得关注」** 博客称 2026 年 Agent 采用出现跃升，企业内部同时存在工程团队自建、业务部门采购和员工自选的多种 Agent，导致追踪、评估和治理分散。LangSmith 此次把 Agent 设为跨产品核心对象，正是对这一碎片化现状的产品回应；但重构后的实际效果尚无独立验证。

**「内容角度」** 可做角度：从“Agent 蔓延”这一治理难题切入，梳理 LangSmith 用统一 Agent 记录（负责人、ID、类型）把分散的追踪、评估和成本指标收拢到一处的设计逻辑，并对照其自述的通用型与编码型评估差异，说明这套数据模型解决了什么、又留下了哪些待验证的问题。

**标签**: `#\#AIAgent`, `#\#LangSmith`, `#\#Agent工作流`, `#\#AI开发工具`, `#\#效率工具`

---

<a id="item-ai-creator-3"></a>
### [Qwen4-Max 上线：2.4 万亿参数、API 降价，小模型后续开源](https://mp.weixin.qq.com/s/pJUt0xwD6H-WMyzd8TjZaQ) ⭐️ 7.0/10

阿里通义千问于 11 月 16 日正式发布新一代旗舰模型 Qwen4-Max，采用稀疏 MoE 架构，总参数 2.4 万亿，原生支持视觉理解与百万 Token 长上下文。官方称其前端编程能力在 Code Arena 盲测中位居全球前列，单任务平均费用从 26.58 元降至 11.16 元，降幅近 58%，Token 消耗减少近 50%，API 定价同步下调。团队同时预告，后续将推出规模更小的 Qwen4 系列模型并公开模型权重，但开源时间与具体规格尚未公布。

telegram · zaihuapd · 11月16日 02:52

**「为何值得关注」** 这是通义千问旗舰系列的代际更新，参数规模、长上下文与视觉能力同时提升，且单任务成本与 API 价格明显下降，对使用其 API 做编程、办公和长程任务的开发者有直接影响。开源目前只是后续计划，尚无可用的权重或免费额度。

**「内容角度」** 可做角度：对比 Qwen4-Max 与上代的单任务成本账——26.58 元降到 11.16 元、Token 消耗减半，拆解这些数字对高频调用 API 的开发者意味着什么，同时说明“后续开源小模型”仍是计划而非既成事实。

**标签**: `#\#Qwen4Max`, `#\#大模型更新`, `#\#通义千问`, `#\#AI编程`, `#\#API降价`

---

<a id="item-ai-creator-4"></a>
### [豆包工作上线「工作台」，首批覆盖 21 个专业场景](https://www.ithome.com/1/027/608.htm) ⭐️ 7.0/10

豆包工作于 11 月 16 日上线「工作台」功能，首批覆盖金融、医疗、教育等 21 个专业场景，定位为提供预置技能与工具的专业 AI 工作空间。金融投研工作台首页设有公告解读、业绩分析、市场简报、公司研究等入口，并可按需接入万得、同花顺、国泰海通等数据服务；用户也能自建个人工作台并分享。具体使用效果与操作步骤尚待核实。

telegram · zaihuapd · 11月16日 08:02

**「为何值得关注」** 这是豆包工作首次将 AI 能力按专业场景打包成「工作台」形态，并明确列出金融投研的具体入口与可接入的数据服务商，属于产品形态上的新变化；但实际使用体验与接入效果尚未得到验证。

**「内容角度」** 可做角度：梳理豆包工作「工作台」首批 21 个场景中金融投研工作台的入口设计与数据接入方式，对比其与通用对话式 AI 在专业工作流上的差异，并标注哪些能力已明确、哪些仍待实测。

**标签**: `#\#豆包`, `#\#AI工作台`, `#\#AI提效`, `#\#金融投研`, `#\#效率工具`

---

<a id="item-ai-creator-5"></a>
### [datasette-maplibre 0.1a0 发布：单条提示词生成的地理空间插件](https://simonwillison.net/2026/Nov/15/datasette-maplibre/) ⭐️ 6.5/10

Simon Willison 发布了 Datasette 地理空间插件 datasette-maplibre 0.1a0，将 MapLibre GL 与 Zsolt Ero 运营的免费矢量地图服务 OpenFreeMap 结合。作者称大部分代码由一条发给 Claude Fable 5.2 的提示词生成，该提示词要求参考 datasette-cluster-map 和 datasette-leaflet-geojson 两个插件并“跳出框架”增加功能，由此产生了 GeoJSON 形状先显示 SVG 预览、滚动进入视野后再加载 WebGL 预览等设计。插件附带可在 Datasette Lite 中通过 Pyodide 和 WebAssembly 在浏览器内运行的演示，示例数据含 171 行国家与首都信息。提示词原文完整，但生成效果的具体实现与可复现性材料未展开。

rss · Simon Willison \(AI工具与提示词实操\) · 11月15日 23:58

**「为何值得注意」** 这是 Datasette 一段时间以来首个新的地理空间插件，同时提供了一个较具体的“单条提示词构建可用插件”案例；不过材料只呈现作者自述与演示链接，未提供代码量、人工修改比例或独立验证。

**「内容角度」** 可做角度：拆解这条提示词为何要求“参考两个既有插件再跳出框架”，并对照演示中 SVG 预览按需加载 WebGL 的做法，讨论单条提示词生成插件时，哪些部分来自明确指令、哪些来自模型自由发挥。

**标签**: `#\#AI编程`, `#\#Claude`, `#\#提示词实操`, `#\#开源工具`, `#\#效率工具`

---

<a id="item-ai-creator-6"></a>
### [OpenAI 公布 ChatGPT 科研侧双动作：1800 名科学家调查 + 学术研究者计划扩至 20 万人](https://openai.com/index/science-at-the-frontier) ⭐️ 6.5/10

OpenAI 官方发布简讯，称一项调查覆盖 1800 多名科学家，关注他们在研究中使用 ChatGPT 的日常流程、自报效率以及对科学发现的预期。目前公开内容只有导语，未披露调查方法、样本构成、具体数据或可复现细节，相关结论仍需等待完整报告核实。受影响的主要是关注 AI 科研应用的从业者与工具评估者。

rss · OpenAI News \(官方动态\) · 11月16日 12:00

**「内容角度」** 可做角度：把这条简讯当作“待核实的调查预告”来处理，先梳理它承诺回答的三个问题——日常流程、自报效率、发现预期——再指出目前缺少方法说明与原始数据，提醒读者区分官方表述与可验证结论。

**标签**: `#\#ChatGPT`, `#\#AI科研`, `#\#AI提效`, `#\#OpenAI`, `#\#效率工具`

📌 **同日该 AI 其他重要动态汇总**：
- **OpenAI 扩大 ChatGPT 学术研究者计划至 20 万人**：OpenAI 宣布将“ChatGPT for Academic Researchers”计划扩展至全球 20 万名研究者，提供前沿模型的免费访问权限；据财联社转述，下一轮申请将于 11 月 23 日开放。目前公开信息仅为一句简讯，具体申请条件、使用条款与限制尚未披露，需以官方后续说明为准。 [OpenAI 扩大 ChatGPT 学术研究者计划至 20 万人](https://openai.com/index/expanding-chatgpt-for-academic-researchers)
- **OpenAI 为 ChatGPT for Healthcare 增加 computer-use agents 与插件**：Reddit r/OpenAI 的一条动态标题称，OpenAI 为 ChatGPT for Healthcare 增加了 computer-use agents 和插件，发布于 2026 年 11 月 16 日；材料中只有标题，具体功能范围、上线版本、可用地区、价格与限制均无法核实。 [OpenAI 为 ChatGPT for Healthcare 增加 computer-use agents 与插件](https://news.google.com/rss/articles/CBMimwFBVV95cUxObGdCRk4wQUItem1aaW9HNDJPNGNDSnNrSG9fc1Q0VFREQk9lakUwVWJtUHhfQ0c3cmhkUXFLejBUZ2llbERkNXNFWlNqbjk4OUdZR0VfU254THNobGVBMHF5NTEzUmJZc2JEbUNnWU10VjJkNG1jSVlIcGNjb1VNU2ducF93Zi10bFBER1pWRzVVWkh0cGRaVURyTQ?oc=5)

---

<a id="item-ai-creator-7"></a>
### [Alphr 发布 Adobe Firefly、Runway、Kling 三款 AI 视频工具对比文章](https://news.google.com/rss/articles/CBMikgFBVV95cUxOTm5NNGRLZ3hsOWoxUXFQTnBCVVMzdDR5Z0VrQ01uV2VsOFlndndaQWtUU3lLU0xyNVFCY2tiX0tPajdjSEFYbjFfbTkxTkxvRTkzOEp1Y2RRREE4UmdncktSdnY4MW1oVnJvTXFHNFAyTEdPU2Nrd1ZpYXVNZ1o1QWxVR0I0Wlp2TDhBc0FFU3hnZw?oc=5) ⭐️ 6.5/10

Alphr 发布了一篇标题为《Adobe Firefly vs Runway vs Kling: AI Video Generation for Creators》的文章，对 Adobe Firefly、Runway、Kling 三款 AI 视频生成工具进行面向创作者的对比。目前可确认的信息仅为标题、来源与发布时间（2026 年 11 月 16 日），文章的具体对比维度、测试方法、版本与结论均未在材料中呈现，尚待核实。受影响人群为关注 AI 视频生成的创作者与内容团队。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月16日 21:33

**「可做角度」** 可做角度：以“三家工具横向对比文章出现”为事实起点，梳理创作者在做 AI 视频工具选型时通常关心的维度（如生成质量、可控性、价格与授权），并明确说明本文尚未披露具体评测结论，避免替原文下判断。

**标签**: `#\#AI视频生成`, `#\#Runway`, `#\#可灵Kling`, `#\#AdobeFirefly`, `#\#工具对比`

---

<a id="item-ai-creator-8"></a>
### [韩媒评 AI 电影《Raphael》：视觉亮眼，剧情欠新意](https://news.google.com/rss/articles/CBMitAFBVV95cUxOZHVlLU8wUVRwY3VVSXI0UWJOZHIwQ1NKbm00Qlk1aDlWUU1wS2VKWEVRQXN3bHdMV2ZmNXBTekpMcjV3UTVXWFJ1ZzFvVW9wbTdxeHg3TTNMZmo1ZHlLVGU1SUZOWU5FSkROSWFzUlZoYlJkUm84WU13Ulh1ZmowZmNXcG4zMk42Qk5kR2Q0Zlg4Z3lQbWNZZFVlOWRaWEVVUkowZjVSYy1BSFBFaVU4VnhpZlrSAbQBQVVfeXFMTmR1ZS1PMFFUcGN1VUlyNFFiTmRyMENTSm5tNEJZNWg5VlFNcEtlSlhFUUFzd2x3TFdmZjVwU3pKTHI1d1E1V1hSdWcxb1VvcG03cXh4N00zTGZqNWR5S1RlNUlGTllORUpETklhc1JWaGJSZFJvOFlNd1JYdWZqMGZjV3BuMzJONkJOZEdkNGZYOGd5UG1jWWRVZTlkWlhFVVJKMGY1UmMtQUhQRWlVOFZ4aWZa?oc=5) ⭐️ 6.5/10

《韩国时报》刊发评论，评价 AI 电影《Raphael》“视觉上令人印象深刻，但剧情缺乏新意”。目前可核实的信息仅限评论标题与媒体来源，影片的具体制作方式、所用工具、上映或发布时间、片长及评价基准均未在材料中披露，相关细节有待核实。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月16日 08:18

**「可做角度」** 可做角度：以这篇评论为引子，梳理“AI 电影被专业媒体评价时，视觉与叙事被分开打分”这一现象，并说明目前只有评论标题、缺少制作细节，避免把单篇影评当作对 AI 电影整体水平的定论。

**标签**: `#\#AI电影`, `#\#AI视频生成`, `#\#AI短剧`, `#\#生成式视频`, `#\#影视评论`

---

<a id="item-ai-creator-9"></a>
### [MiniMax 2026 定价汇总文章出现，细节待核实](https://news.google.com/rss/articles/CBMiTEFVX3lxTE9SM2pLLTlfNUFmNklubnp4OFBPcWJmNFJWSnZNamlzSjlIUFdmTTFsc0cyVER1R3p4c1hmWUtPZnJuX2RtMXZFcGN3WG0?oc=5) ⭐️ 6.5/10

Fello AI 发布了一篇题为《MiniMax Pricing 2026: Hailuo, H3, API &amp; M Plan》的文章，从标题看是汇总 MiniMax 在 2026 年的定价信息，涉及 Hailuo（海螺）、H3、API 与 M Plan 四类内容。目前仅有标题与来源信息，正文中的具体价格、套餐额度、版本参数与生效日期均未提供，无法确认其准确性与时效性。受影响人群主要是关注 MiniMax 视频生成与 API 成本的开发者和内容创作者。

rss · Runway &amp; AI视频动态 \(短剧与生成式视频\) · 11月16日 20:53

**「内容角度」** 可做角度：以“一篇只有标题的定价汇总”为切口，说明目前能确认的只有文章覆盖 Hailuo、H3、API、M Plan 四个条目，价格与限制均待核实，提醒读者不要依据标题转述具体数字。

**标签**: `#\#AI视频生成`, `#\#MiniMax`, `#\#海螺AI`, `#\#API定价`, `#\#AI工具测评`

---

<a id="item-ai-creator-10"></a>
### [Reddit 帖称追踪 28 个模型训练截止日期，15 个未公开](https://news.google.com/rss/articles/CBMinwFBVV95cUxNS3lHcnhxUlV0MTJRR2hOM1JvcHVFMUZtNlA2M0FrT0JOYU1sQUsweVgtX0ZyRGQ0Zmd6NHpKM0VZbVRpcXRuZmZkTS10Z3BKMkh3ME1EQUJPZWdBaTRacGlabjNrZGxFTHEtUEpvbUNGbmlVQ0I0TFB0emJ4MEgwWFRzM0dvTXVZajY4R3R1M2NSUERXNFhDMFRXb1ZrbTA?oc=5) ⭐️ 6.5/10

一条来自 Reddit r/OpenAI 的标题帖声称，作者追踪了 28 个当前模型的训练数据截止日期，其中 15 个模型没有公开任何截止日期；帖子还称 Gemini 4 Carbon 于上周发布，但其训练截止日期已落后 8 个月。目前材料只有标题，没有正文、数据来源、统计口径或核实方法，上述数字与“落后 8 个月”的对比基线均无法验证。受影响的是关注模型知识时效与信息透明度的开发者和用户。

rss · Reddit - r/OpenAI \(官方动态与用户反馈\) · 11月16日 13:07

**「内容角度」** 可做角度：以“模型训练截止日期公开情况”为线索，梳理这条帖子提出的问题——多数模型不披露截止日期时，用户如何判断模型知识的新旧；同时明确标注该帖仅有标题、数据未经核实，不引用其具体数字作为结论。

**标签**: `#\#AI模型对比`, `#\#训练数据截止`, `#\#AI资讯`, `#\#信息差`, `#\#大模型`

---

---

<!-- HORIZON_TRENDING -->
## 🔥 GitHub 今日 Trending Top 3（按今日新增 star）

#### 1. [dream-num/univer](https://github.com/dream-num/univer)
- ⭐ 今日 +1,878 · 总 27,753 · 🍴 2,524 · TypeScript · Apache-2.0 · 最近推送 6 小时前
- 榜单位置：第 3 位
- 简介：Build your own AI office with Univer Office SDK. Bring editing, calculation, collaboration, and file processing into your product for people and AI agents. Built on an extensible open-source core.
- 这是什么：Univer Office SDK，用于在自有产品中构建办公应用，覆盖表格、文档、演示、表格、画布与 PDF。
- 适合谁：面向希望把办公编辑、计算、协作与文件处理集成进产品、供人和 AI 代理使用的开发者。
- 上手：README 给出 Quick start 入口，但未给出具体命令步骤。

#### 2. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- ⭐ 今日 +1,057 · 总 7,422 · 🍴 1,145 · Python · MIT · 最近推送 0 小时前
- 榜单位置：第 5 位
- 简介：A Claude Code skill bundle for bug hunting and external red-team work - 82 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.
- 这是什么：面向漏洞挖掘与外部红队工作的 Claude Code 技能包，含 83 个技能、15 个斜杠命令与 681 条披露报告模式。
- 适合谁：适合在授权红队与漏洞赏金场景中工作的安全研究人员，帮助按主题自动加载技能并保持范围合规。
- 上手：在 Claude Code 中执行 /plugin marketplace add elementalsouls/Claude-BugHunter，再执行 /plugin install claude-bughunter@elementalsouls。

#### 3. [NVIDIA/SkillEvaluator](https://github.com/NVIDIA/SkillEvaluator)
- ⭐ 今日 +953 · 总 2,647 · 🍴 358 · Python · Apache-2.0 · 最近推送 0 小时前
- 榜单位置：第 10 位
- 简介：Multi-tier framework for evaluating AI agent skills and plugins with quality gates, semantic overlap detection, synthetic evaluation dataset generation, and live agent evaluation that measures how skills affect agent behavior.
- 这是什么：评估 AI 代理技能与插件的多层级框架，含质量门、语义重叠检测、合成评估数据集生成与实时代理评估。
- 适合谁：适合需要检查代理技能质量并衡量技能对任务结果影响的开发者，可接入 CLI、CI 或代理。
- 上手：pip install skillevaluator，然后运行 skillevaluator validate ./my-skill --tiers 1。

> 中文摘要由 AI 根据仓库简介与 README 生成，仅供参考。
