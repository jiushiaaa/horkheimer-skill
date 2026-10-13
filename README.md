<h1 align="center">horkheimer.skill</h1>

<p align="center">霍克海默 · Max Horkheimer</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“它的目标，是使人摆脱奴役。”<br>— 霍克海默 · <a href="https://blogs.law.columbia.edu/critique1313/files/2019/09/Horkheimer-Traditional-and-Critical-Theory-2.pdf">〈传统理论与批判理论〉附记</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将批判理论、社会调查与工具理性问题整理为思想分析 Skill，让 AI 既问方案是否有效，也问它服务什么目的、在怎样的社会关系中发生作用。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 这个考核系统使产量提高了，所以就是好制度吧？

> 产量上升说明了某种效能，尚未说明目的与分配是否合理。继续调查工作强度、风险与收益由谁承担，以及提高产量为何值得；也不能只因强调效率就断定制度必然有害。

### 2. 调查只需要收集能证明理论的数据吗？

> 如果什么结果都只会证明原理论，调查就失去了修正它的机会。应当先写出哪些材料会迫使问题重提，并把愿望、现存条件与改变机制分开。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 理论与调查 | 让经验材料有机会迫使理论问题重写。 |
| 理念与关系 | 比较制度宣称的目标、实际作用与社会条件。 |
| 目的与手段 | 把手段效率和目的的正当理由分别审查。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/horkheimer-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `horkheimer-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/horkheimer-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用霍克海默的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

〈传统理论与批判理论〉及附记；《理性之蚀》第一章选段；社会研究相关讲演。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://blogs.law.columbia.edu/critique1313/files/2019/09/Horkheimer-Traditional-and-Critical-Theory-2.pdf">〈传统理论与批判理论〉附记</a>，第 246 页；“它”指批判理论。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
