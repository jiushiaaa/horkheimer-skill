<h1 align="center">horkheimer.skill</h1>

<p align="center">霍克海默 · Max Horkheimer</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“Its goal is man’s emancipation from slavery.”<br>— Max Horkheimer · <a href="https://blogs.law.columbia.edu/critique1313/files/2019/09/Horkheimer-Traditional-and-Critical-Theory-2.pdf">Traditional and Critical Theory, Postscript</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for critical theory, social inquiry, and instrumental reason: ask both whether a scheme works and what ends and social relations its success serves.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. An assessment system increased output. Does that make it a good institution?

> The increase supports a claim about effectiveness, not yet the justification of its ends or distribution. Investigate workload, risk, beneficiaries, and why the target matters. An emphasis on efficiency alone does not prove harm.

### 2. Should research collect only data that confirms the theory?

> If every outcome merely confirms the initial theory, inquiry cannot revise it. Specify what would force the question to change and distinguish aspirations, existing conditions, and mechanisms of change.

## What is distilled

| Method | What it helps examine |
|---|---|
| Theory and inquiry | Allow evidence to revise the theoretical question. |
| Ideals and relations | Compare stated aims, actual effects, and social conditions. |
| Ends and means | Assess efficiency separately from the justification of ends. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/horkheimer-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `horkheimer-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/horkheimer-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Max Horkheimer’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Traditional and Critical Theory and its Postscript; selections from chapter I of Eclipse of Reason; lectures on social research.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://blogs.law.columbia.edu/critique1313/files/2019/09/Horkheimer-Traditional-and-Critical-Theory-2.pdf">Traditional and Critical Theory, Postscript</a>, p. 246; “it” refers to critical theory. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
