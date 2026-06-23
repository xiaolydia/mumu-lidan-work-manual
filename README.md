# mumu-lidan-work-manual

这是一个从《李诞工作手册（全新修订版）》中提炼出来的非官方 Agent Skill。

它不是读书笔记，也不是原书摘录，而是把书里的内容工作方法整理成一套可被 AI 助手调用的实践工具，用来帮助你做：

- 自媒体定位和个人 IP 设计；
- 内容创作、视频选题、脚本修改；
- 直播、读信、陪伴型内容设计；
- 脱口秀/口播/短视频逐字稿；
- 镜头表达、情绪表达、节奏和风格；
- 读稿会、选题会、创意会；
- pitch、前采、客户/嘉宾沟通；
- 内容团队的专业协作。

本仓库不包含原书 PDF、扫描件、原文章节或长篇摘录。版权归原作者和出版社所有。

## 适合谁用

如果你希望 AI 助手不只是泛泛地帮你“写内容”，而是像一个内容负责人一样帮你判断、拆解、改稿、设计流程，这个 skill 会比较适合。

典型使用者：

- 正在做个人 IP 的创作者；
- 正在做 AI 博主、知识博主、内容博主的人；
- 想把选题变成短视频/公众号/小红书内容的人；
- 需要写口播稿、直播稿、视频脚本的人；
- 需要开读稿会、选题会、创意会的内容团队；
- 需要向客户、老板、嘉宾 pitch 创意的人。

## 安装方法

### Codex / 本地 skills

把仓库克隆到 Codex skills 目录：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/xiaolydia/mumu-lidan-work-manual.git ~/.codex/skills/mumu-lidan-work-manual
```

然后重启 Codex，或刷新 skill 列表。

### Amp / agents skills

如果你的 Agent 从 `~/.config/agents/skills` 读取 skills，可以这样安装：

```bash
mkdir -p ~/.config/agents/skills
git clone https://github.com/xiaolydia/mumu-lidan-work-manual.git ~/.config/agents/skills/mumu-lidan-work-manual
```

### 手动安装

也可以直接把整个文件夹复制到兼容的 skills 目录。目录结构保持这样：

```text
mumu-lidan-work-manual/
  SKILL.md
  README.md
  chapters/
  patterns.md
  cheatsheet.md
  glossary.md
  source-notes.md
```

## 怎么使用

在提示词里直接点名这个 skill：

```text
用 mumu-lidan-work-manual 帮我分析我的 AI 博主定位。
```

AI 助手应该按这个流程工作：

1. 先读 `SKILL.md`；
2. 判断你的问题属于哪个主题；
3. 如果需要深入，再读对应章节；
4. 给出具体诊断、取舍判断和下一步动作；
5. 不复述原书，不生成长篇原文摘录。

## 常用提示词

### 个人 IP 定位

```text
用 mumu-lidan-work-manual 帮我分析个人 IP 定位。
我想做 AI 博主，但不想变成普通 AI 工具号。
请帮我梳理发心、目标用户、人设、内容支柱和选题方向。
```

### 视频选题规划

```text
用 mumu-lidan-work-manual，把这些零散笔记整理成 30 天视频选题计划。
优先选择能体现个人判断、长期风格和真实用户价值的题目。
```

### 脚本修改

```text
用 mumu-lidan-work-manual 的“逐字稿”和“删到不能再删”原则，
帮我把这条短视频脚本改得更口语、更具体、更有情绪。
```

### 直播/陪伴型内容

```text
用 mumu-lidan-work-manual 帮我设计一个 AI 博主直播栏目。
我希望它有用、有陪伴感，但不要像强销售的公开课。
```

### 读稿会/选题会

```text
用 mumu-lidan-work-manual 帮我设计一个内容团队读稿会流程。
需要包括：会前带什么、怎么提意见、谁拍板、会后怎么行动。
```

### pitch 和前采

```text
用 mumu-lidan-work-manual 帮我把这个内容创意 pitch 给客户。
请给我几个备选方案、可能反对意见，以及前采时更好的提问方式。
```

## 主题地图

| 需求 | 该读哪个文件 |
|---|---|
| 自媒体发心、账号定位、直播陪伴感、数据焦虑 | `chapters/01-self-media-mindset.md` |
| 人设、真诚表达、暴露自己、恶评、情绪冷却 | `chapters/02-authenticity-and-exposure.md` |
| 创作节奏、把内容当工作、用真实项目练习 | `chapters/03-work-and-creative-rhythm.md` |
| 逐字稿、删字、主题边界、故事承载价值观 | `chapters/04-writing-and-ideas.md` |
| 镜头/舞台表达、情绪连接、节奏、风格 | `chapters/05-performance-and-style.md` |
| 节目设计、短内容结构、五分钟作品、当众成长 | `chapters/06-program-and-short-work.md` |
| 读稿会、创意会、pitch、前采 | `chapters/07-meetings-pitch-and-preinterview.md` |
| 职业困惑、难而正确的事、专业性、跨岗位学习 | `chapters/08-career-and-professionalism.md` |

辅助文件：

- `patterns.md`：可复用工作模式。
- `cheatsheet.md`：快速检查清单。
- `glossary.md`：核心概念词典。
- `source-notes.md`：来源说明、公开发布说明和边界。

## 推荐的 Agent 回答方式

使用这个 skill 时，AI 助手不应该只总结观点，而应该像一个内容负责人一样：

- 先判断用户真正卡在哪里；
- 区分“创作者模式”和“传播者模式”；
- 避免先捏一个虚假的人设；
- 找到用户真实发心和可持续内容节奏；
- 把抽象建议变成脚本、选题、会议规则、内容计划；
- 保留书里强调的实践感，但不复制原书长段文字。

## 回答示例

不好的回答：

> 你要真诚，坚持输出优质内容。

更好的回答：

> 你现在这组选题太工具导向了。这样发出去，用户记住的是工具，不是你。建议把系列重心改成一个人的真实问题：“我收藏了很多 AI 工具，但还是做不完真实工作。”每个工具只作为工作流里的一个步骤出现。第一批可以先做这三个选题……

## 公开使用说明

这个 skill 是非官方整理，不代表原作者或出版社立场。

原书版权属于原权利人。本仓库只包含经过提炼和重组的工作方法，用于个人学习和 Agent 行为设计，不替代原书。

如果你觉得这些方法有帮助，请通过正规渠道阅读原书。
