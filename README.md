# ZoeyDesignSkills · Design Research

<p align="center">
  <b>我自己的设计研究笔记本。</b>
</p>

<p align="center">
  用来整理我在工作里慢慢攒下来的研究方法、分析框架，以及一些自己琢磨出来的小经验。
</p>

<p align="center">
  <img alt="status" src="https://img.shields.io/badge/status-持续更新-6aa84f">
  <img alt="focus" src="https://img.shields.io/badge/focus-设计研究-3d85c6">
  <img alt="owner" src="https://img.shields.io/badge/by-Zoey-8e7cc3">
  <img alt="language" src="https://img.shields.io/badge/language-中文-orange">
</p>

---

## 这是个什么仓库

简单说，这是我自己的设计研究笔记本。

工作这些年，我发现自己用过、想过、试过的研究方法其实不少，但它们大多散在 PPT、文档、聊天记录和脑子里。  
所以我开了这个仓库，慢慢把它们写下来、整理成自己看得懂、以后还能再用的形式。

里面会陆续放进：

- 一些研究方法和分析思路
- 我自己总结的判断标准、检查清单
- 一些可以直接套用的模板
- 顺便也写了一些可以喂给 AI 用的版本

主题大概会围绕这些：用户研究、竞品研究、市场研究、用户观察、设计策略，以及一些洞察怎么提的思考。

---

## 我为什么写它

工作里很多研究内容做完就过去了——汇报完、上线完，就再也没人翻了。  
但其实里面的"方法"和"思路"是值得留下来的，比当时那份具体的项目结论更耐用。

所以我更想记录的不是"我做过什么项目"，而是：

- 我当时是怎么定义这个问题的
- 我是怎么拆它的
- 我是怎么从一堆信息里挑出真正有用的判断的
- 下次遇到类似问题，我能不能更快、更准一点

写给自己看，顺便也整理给将来的自己看。

---

## 我自己的几个偏好

- 能复用的，比一次性的好
- 有结构的，比随手记的好
- 能帮我做判断的，比单纯描述现象的好
- 写明白一点，未来 AI 也能帮我跑

---

## 现在已经写了的

| Skill | 主题 | 入口文件 |
|---|---|---|
| 竞品分析 Design Skill | 竞品研究、设计决策、策略输出 | [竞品分析DesignSkill.md](./竞品分析DesignSkill.md) |

---

## 仓库长这样

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

## 一个 Skill 里通常有什么

我希望这里的每个 skill 都不是一篇孤零零的文档，而是一小套用起来顺手的资料：

| 文件 / 目录 | 用来做什么 |
|---|---|
| 主 Skill 文件 | 方法本身怎么用 |
| `skill.meta.json` | 一些元信息，方便检索 |
| `prompt.md` | 一些常用的 prompt |
| `checklist.md` | 自查清单 |
| `SYSTEM_PROMPT.md` | 给 AI 用的版本 |
| `TASK_ROUTER.md` | 不同任务怎么分流 |
| `SKILL_CARD.md` | 一页纸看懂这个 skill |
| `templates/` | 可以直接套用的模板 |
| `examples/` | 一些例子 |

主要给自己用，顺便也方便丢给 AI 跑。

---

## 当前主要在写：竞品分析

第一个写进来的是竞品分析。  
原因很简单——大家都在做竞品，但很多时候做完就停在了"看看别人怎么做"，没真正帮上设计决策。

我自己也踩过这个坑，所以想把这套方法整理清楚，至少自己以后再做的时候能更省心。

它大概在回答这些问题：

- 这次到底为什么要做竞品
- 哪些竞品值得看，哪些其实可以不看
- 看竞品应该看什么、不该看什么
- 怎么从一堆做法里抽出真正有用的判断
- 我们自己现在到底在哪个位置
- 最后这份分析，能不能真的指导设计

相关文件：

- [主文档](./竞品分析DesignSkill.md)
- [Prompt Pack](./prompt.md)
- [Checklist](./checklist.md)
- [System Prompt](./SYSTEM_PROMPT.md)
- [Task Router](./TASK_ROUTER.md)
- [Skill Card](./SKILL_CARD.md)
- [Templates](./templates/)
- [Examples](./examples/)

---

## 怎么用

随便看就行。但如果想稍微有点目的：

**想了解某个方法**：直接读主文档，配着 checklist 和 templates 看。  
**手上有真实项目**：套模板用，用清单查一遍，省时间。  
**想接到 AI 流程里**：从 `SKILL_CARD.md` 开始看，再用 `SYSTEM_PROMPT.md` 跑。

---

## 之后还想写的

慢慢来，没有时间表。可能会有：

- 用户研究怎么做
- 用户访谈和观察的一些经验
- 市场研究和趋势怎么看
- 洞察是怎么从信息里冒出来的
- 设计策略相关的思考
- 一些常见的"看起来在做研究，其实没什么用"的坑

写到哪算哪。

---

## 一点说明

这个仓库主要写给我自己。但如果你刚好路过、刚好觉得有点用，那也挺好。

它不是一份成品，更像是我一边工作、一边整理、一边修改的笔记。所以你看到的东西可能这周和下周不太一样——这是正常的，研究本身就是这么个过程。

---

## Topics

```text
design-research
user-research
competitive-analysis
market-research
ux-research
design-strategy
research-methods
```

---

## 快速入口

- [竞品分析DesignSkill.md](./竞品分析DesignSkill.md)
- [templates/](./templates/)
- [examples/](./examples/)
- [SYSTEM_PROMPT.md](./SYSTEM_PROMPT.md) · [TASK_ROUTER.md](./TASK_ROUTER.md) · [SKILL_CARD.md](./SKILL_CARD.md)
