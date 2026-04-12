<div align="center">

# 红人营销.skill

> *"红人营销的核心不在'红人'，而是'营销'。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)

<br>

老板让你建联 100 个博主，你建联了 100 个。<br>
回复了 5 个，上线了 2 个，播放量加起来 3000。<br>
**然后老板问你：ROI 呢？**<br>

别慌。这份 Skill 浓缩了 5 年海外红人营销实战经验，<br>
从竞品分析到预算规划，从 Brief 撰写到砍价话术，<br>
**帮你少踩坑，多出爆款。**

<br>

覆盖海外红人营销全流程 9 大场景：<br>
**竞品分析 · 营销策略 · Brief 撰写 · 建联话术 · 博主筛选 · 谈判砍价 · 数据复盘 · 预算规划 · 职业发展**<br>
不只回答问题，还能直接帮你生成邮件、Brief、预算方案等产出物。

[安装](#安装) · [使用](#使用) · [效果示例](#效果示例) · [English](README_EN.md)

</div>

---

## 安装

### Claude Code

> **重要**：Claude Code 从 **git 仓库根目录** 的 `.claude/skills/` 查找 skill。请在正确的位置执行。

```bash
# 安装到当前项目（在 git 仓库根目录执行）
mkdir -p .claude/skills
git clone https://github.com/waynefu2020/influencer-marketing-skill .claude/skills/红人营销

# 或安装到全局（所有项目都能用）
git clone https://github.com/waynefu2020/influencer-marketing-skill ~/.claude/skills/红人营销
```

---

## 使用

在 Claude Code 中输入：

```
/红人营销
```

然后描述你的问题或需求，Skill 会自动识别场景并给出实战建议。

### 支持的场景

| 场景 | 说明 | 能生成产出物 |
|------|------|-------------|
| 竞品分析 | 选竞品、看产品、看达人、挖内容 | 竞品分析框架表格 |
| 营销策略 | 目标拆解、阶段规划、KOL/KOC 配比 | Campaign 方案 |
| Brief 撰写 | Brief 结构、写法、注意事项 | Brief 文档 |
| 建联话术 | 开发信、跟进邮件、回复率优化 | 中英文邮件 |
| 博主筛选 | 工具使用、数据判断、质量评估 | — |
| 谈判砍价 | 报价判断、砍价策略、合同注意事项 | 砍价话术 |
| 数据复盘 | AARRR 漏斗、投放效果分析 | 复盘报告框架 |
| 预算规划 | CPM 反推、阶段分配、投流比例 | 年度/季度预算方案 |
| 职业发展 | 选公司、能力模型、晋升路线 | — |

---

## 效果示例

**场景一：新手求助**

```
用户          ❯ 刚入行，老板让我建联博主，不知道从哪下手

红人营销.skill ❯ 别急着群发邮件，先搞清楚 3 件事：

                1. 你们产品卖给谁？什么人群？
                2. 竞品在用什么博主？什么内容形式？
                3. 你有多少预算？纯佣还是付费？

                建议先花半天做个简单竞品分析：
                去 TikTok 搜竞品名，找播放量最高的 5 个视频，
                看看这些博主粉丝多少、内容什么形式，
                基本就知道你该找什么样的博主了。

                工具推荐：先装个 Wednesday 插件（免费），
                直接在 TikTok 页面上就能看博主数据，别一上来就买工具。
```

**场景二：帮写建联邮件**

```
用户          ❯ 帮我写一封建联邮件，我们是做便携充电器的，主打轻便和快充

红人营销.skill ❯ Subject: Collab from [你的品牌] — Love your tech reviews!

                Hi [博主名字],

                I've been following your work for a while (really enjoyed your
                recent take on [博主最近一个视频主题]).

                I'm [你的名字] from [品牌名]. We just launched a portable charger
                that's 40% lighter than anything on the market — and charges at 65W.

                We're looking for a few tech creators to test it out and give honest
                feedback. No strings attached.

                If the content performs well, we'd love to put our marketing budget
                behind it (our past campaigns hit 2M+ views on TikTok).

                Interested?

                Cheers,
                [你的名字]

                💡 记得把 [占位符] 替换成实际信息。
                标题里用 Collab 不要用 Cooperation，这是行业惯例。
```

**场景三：预算规划**

```
用户          ❯ 老板给了 5 万美金预算做一个季度，怎么分配？

红人营销.skill ❯ $50,000 一个季度，按三阶段分：

                第 1 个月（摸索期）— $10,000
                  KOC 为主（80%），测试卖点和内容模板
                  目标：找到 3-5 个潜力内容方向

                第 2 个月（爆款期）— $18,000
                  加大腰部 KOL（40%），复制潜力模板
                  目标：打造 1-2 个爆款（10万+播放）

                第 3 个月（放量期）— $22,000
                  KOL 占比提高到 60%，放大曝光
                  目标：品牌词搜索量明显增长

                其中博主合作费占 80%（$40,000），
                投流加热占 20%（$10,000）——优先加热自然流量好的内容。

                💡 前期别急着花钱找大博主，先用小预算跑通内容模板，
                确认什么内容形式有效再加码，这叫内容赛马。
```

---

## 知识体系

Skill 内置 6 大知识模块，基于 5 年实战经验沉淀：

| 模块 | 核心内容 |
|------|---------|
| **竞品分析** | 选竞品 3 种方法、产品卖点挖掘、达人矩阵分析、AI 辅助竞品调研 |
| **营销策略** | CPM 反推预算、三阶段规划、KOL/KOC 配比、内容赛马策略 |
| **红人合作** | 建联四步法、邮件模板、筛选 SOP、谈判砍价 5 大策略、合同要点 |
| **内容策略** | Brief 撰写、内容形式选择、博主共创原则、内容审核流程 |
| **数据分析** | AARRR 漏斗、效果衡量指标、异常优化思路、复盘报告框架 |
| **预算规划** | 年度预算结构（60/80/20 法则）、平台分配、阶段分配、预算不足取舍 |

### 内置模板

| 模板 | 用途 |
|------|------|
| Brief 模板 | 给博主的内容合作需求单 |
| 建联邮件模板 | 首次建联、免费寄样、付费合作、二次跟进 |
| 预算方案模板 | 年度/季度预算拆解方案 |
| 竞品分析框架 | 竞品信息、达人矩阵、内容策略分析表格 |

---

## 项目结构

```
influencer-marketing-skill/
├── SKILL.md                          # Skill 入口
├── knowledge/                        # 知识库
│   ├── 01_competitor.md              #   竞品分析
│   ├── 02_strategy.md                #   营销策略
│   ├── 03_brief.md                   #   Brief 撰写
│   ├── 04_outreach.md                #   建联话术
│   ├── 05_influencer_selection.md    #   博主筛选
│   ├── 06_negotiation.md             #   谈判砍价
│   ├── 07_data_analysis.md           #   数据分析复盘
│   ├── 08_budget.md                  #   年度预算规划
│   └── 09_career.md                  #   职业发展
├── templates/                        # 产出物模板
│   ├── brief_template.md             #   Brief 模板
│   ├── outreach_email.md             #   建联邮件模板
│   ├── budget_plan.md                #   预算方案模板
│   └── competitor_analysis.md        #   竞品分析框架
├── README.md                         # 中文文档
├── README_EN.md                      # English docs
└── LICENSE
```

---

## 适用人群

- **刚入行的红人营销专员**：快速上手，避免踩坑
- **有经验的从业者**：查漏补缺，提升方法论
- **红人营销主管**：策略规划、预算方案参考
- **跨境电商/App 出海团队**：红人营销全流程指导

---

## 注意事项

- 知识库基于 TikTok、Instagram、YouTube 三大平台的实战经验
- 报价数据为行业参考范围，具体价格因品类、地区、博主个体差异而变化
- 超出知识库覆盖范围的问题，会基于经验推理并标注"推测"
- 生成产出物时会主动确认关键信息，不会瞎编数据

---

### 写在最后

> "海外红人营销重点不在'红人'，而是'营销'。消费者喜欢你的内容，才会对你的产品有认同，才会有下单的动作。"

建联话术可以用 AI 搞定，但背后最考验的是你对用户的洞察和对卖点的理解。

这个 Skill 不能替代你的判断力，但可以帮你更快地建立完整的方法论，少走弯路。

**祝大家在出海这条路上，都能做出自己的爆款。共勉！**

MIT License © [waynefu2020](https://github.com/waynefu2020)
