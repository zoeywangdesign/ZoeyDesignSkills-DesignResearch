# ZoeyDesignSkills · Design Research

<p align="center">
  <b>一个持续沉淀设计研究方法、技能与洞察的个人仓库。</b>
</p>

<p align="center">
  这里不是单纯存放研究文档的地方，而是我用来长期积累 research skills、方法论框架、分析模板、判断标准与 AI 可复用能力的设计研究系统。
</p>

<p align="center">
  <img alt="status" src="https://img.shields.io/badge/status-持续更新-6aa84f">
  <img alt="focus" src="https://img.shields.io/badge/focus-设计研究-3d85c6">
  <img alt="owner" src="https://img.shields.io/badge/by-Zoey-8e7cc3">
  <img alt="language" src="https://img.shields.io/badge/language-中文-orange">
  <img alt="updated" src="https://img.shields.io/badge/updated-2026--05--18-blue">
</p>

---

## 这是一个什么仓库

**ZoeyDesignSkills · Design Research** 是我的个人设计研究技能库。  
我希望它不只是一个文档仓库，而是一套可以持续生长、持续复用、持续迭代的 **Research Skill System**。

这个仓库会逐步沉淀我在设计研究相关工作中的：

- **Research Skills**：可复用的方法、流程、框架与分析路径
- **Research Insights**：被提炼过的认知、判断、启发与经验
- **Design Research Assets**：Prompt、模板、清单、案例、AI 调用文件
- **Strategy Support**：帮助设计、产品、策略、研究协同决策的方法工具

未来这里会持续扩展的主题包括：

- 用户研究
- 竞品研究
- 市场研究
- 用户观察方法
- 设计策略
- 洞察提炼
- 研究综合与输出方法

---

## 为什么我要做这个仓库

在实际工作里，很多研究材料都会散落在：

- PPT
- 会议记录
- 截图
- 飞书文档
- 临时分析页
- 一次性的项目产出

这些内容通常有信息，但不一定有结构；有结论，但不一定可复用；有参考价值，但不一定能持续转化为能力。

所以我想做这个仓库，把零散经验整理成一套更长期的方法资产。  
与其只保存“这次项目做了什么”，我更想保存：

- 我是如何定义一个研究问题的
- 我如何拆解一个复杂问题
- 我如何把调研结果转化为判断与策略
- 我如何把研究能力沉淀成别人也能使用、AI 也能调用的 skill package

---

## 这个仓库的核心原则

- **复用优先，而不是一次性产出优先**
- **方法优先，而不是资料堆积优先**
- **结构优先，而不是零散记录优先**
- **决策支持优先，而不是描述现象优先**
- **既给人看，也给 AI 用**
- **持续生长，逐步迭代**

---

## 当前已收录的 Skill

| Skill | 主题焦点 | 类型 | 入口文件 |
|---|---|---|---|
| 竞品分析 Design Skill | 竞品研究、设计决策支持、策略输出 | Design Research / Strategy / UX | [竞品分析DesignSkill.md](./竞品分析DesignSkill.md) |

---

## 当前仓库结构

```text
ZoeyDesignSkills-DesignResearch/
├── README.md
├── LICENSE
├── 竞品分析DesignSkill.md
├── skill.meta.json
├── prompt.md
├── checklist.md
├── SYSTEM_PROMPT.md
├── TASK_ROUTER.md
├── SKILL_CARD.md
├── templates/
│   ├── task-definition-template.md
│   ├── competitor-selection-template.md
│   ├── deconstruction-template.md
│   └── strategy-output-template.md
└── examples/
    ├── example-input.md
    └── example-output.md
```

---

## 我希望每个 Skill 长成什么样

我希望这里的每一个 research skill，最终都不是一篇孤立文档，而是一套完整的可复用 skill package，通常包括：

| 文件 / 目录 | 作用 |
|---|---|
| `README.md` | 仓库首页与总览 |
| `*.md` 主 Skill 文件 | 方法论主文档 |
| `skill.meta.json` | 机器可读的元信息 |
| `prompt.md` | 可直接复用的 Prompt 集 |
| `checklist.md` | 评审与检查清单 |
| `SYSTEM_PROMPT.md` | 给 AI / Agent 直接调用的系统提示 |
| `TASK_ROUTER.md` | 任务分流逻辑 |
| `SKILL_CARD.md` | 面向人阅读的技能卡片 |
| `templates/` | 开箱即用模板 |
| `examples/` | 输入输出示例 |

这样设计的目的很明确：  
它既要适合我自己沉淀知识，也要适合团队共用，还要能被未来的 AI 工作流直接调用。

---

## 当前重点 Skill

### 竞品分析 Design Skill

这是一套把“竞品调研”从截图拼盘、页面对比、零散参考，升级为**支持设计决策的结构化分析方法**的 skill。

**它主要解决的问题：**
- 如何明确竞品分析到底在解决什么问题
- 如何筛选真正有参考价值的竞品
- 如何从体验目标出发拆解竞品
- 如何从具体做法中归纳典型方案
- 如何判断自身所处位置
- 如何把竞品分析最终转化为设计策略

**相关文件：**
- [主文档](./竞品分析DesignSkill.md)
- [Prompt Pack](./prompt.md)
- [Checklist](./checklist.md)
- [System Prompt](./SYSTEM_PROMPT.md)
- [Task Router](./TASK_ROUTER.md)
- [Skill Card](./SKILL_CARD.md)
- [Templates](./templates/)
- [Examples](./examples/)

---

## 你可以怎么使用这个仓库

### 1. 当作方法知识库来看
如果你想快速理解一个研究主题或方法：
- 先看主 Skill 文档
- 再看 Checklist 和 Templates
- 最后用 Examples 理解理想输入输出

### 2. 当作真实项目工具箱来用
如果你正在做实际项目：
- 用模板定义问题
- 用清单检查分析是否完整
- 用 Prompt 帮助自己做提炼、重组、评审和输出

### 3. 当作 AI Skill 库来用
如果你希望把这些方法接到 AI / Agent 工作流里：
- 先读 `SKILL_CARD.md`
- 再通过 `TASK_ROUTER.md` 判断任务类型
- 用 `SYSTEM_PROMPT.md` 作为主技能提示
- 用模板和示例稳定输出结构

---

## 未来会继续写进来的内容

这个仓库未来不会只停留在竞品分析。  
我会陆续把更多设计研究相关能力写进来，例如：

- 用户研究方法
- 用户访谈与观察方法
- 市场研究与趋势扫描方法
- 洞察提炼与综合方法
- 设计策略框架
- 常见反模式与误区库
- 输出结构规范
- 可被 AI 调用的 research skill packages

---

## 这个仓库的个人风格

这个仓库对我来说，不只是一个“存资料的地方”，更像是：

- 我如何思考研究问题的外显化
- 我如何积累方法论的过程记录
- 我如何把经验整理成结构化能力
- 我如何让自己的 research practice 变得更可迁移、更可复用

如果说作品集更多展示“我做过什么”，  
那这个仓库更想展示的是：

> **我如何思考、如何研究、如何判断，以及如何把这些能力沉淀成长期资产。**

---

## 推荐 GitHub Topics

```text
design-research
user-research
competitive-analysis
market-research
ux-research
design-strategy
research-methods
knowledge-base
prompt-engineering
ai-skills
```

---

## 快速入口

- **当前主 Skill**：[竞品分析DesignSkill.md](./竞品分析DesignSkill.md)
- **模板目录**：[templates/](./templates/)
- **示例目录**：[examples/](./examples/)
- **AI 调用文件**：[SYSTEM_PROMPT.md](./SYSTEM_PROMPT.md) · [TASK_ROUTER.md](./TASK_ROUTER.md) · [SKILL_CARD.md](./SKILL_CARD.md)

---

## Maintainer Note

这个仓库会持续更新。  
随着更多 research skills 和 insights 被整理出来，这里会逐步从“一个技能仓库”长成“一个个人设计研究方法系统”。

如果你在 GitHub 上看到这里，我更希望你把它理解成：

> 一个仍在成长中的、关于设计研究方法与判断力的长期项目。  
> 而不只是一个静态的文档存档库。