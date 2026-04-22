# Mengdie Roundtable · Multi-Perspective Discussion Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-7B68EE?style=flat)](https://claude.com/claude-code)

> "Zhuangzi dreamed of a butterfly—multiple perspectives merging, truths emerge."

Mengdie is a Claude Code skill that orchestrates multiple perspective skills to discuss topics, producing consensus conclusions + diverse viewpoint arrays + preserved disagreements.

[**Read this in 中文**](README.md)

---

## Quick Start

### Installation (Terminal)

```bash
git clone https://github.com/EricArcha/mengdie-skill.git ~/.claude/skills/mengdie
```

Or manual:
```bash
cp -r mengdie ~/.claude/skills/
```

Restart Claude Code or type `/skills reload` to activate.

### Activation

| 中文 | English |
|------|---------|
| 「开一个梦蝶讨论」 | "start a Mengdie discussion" |
| 「开个会吧」 | "let's have a meeting" |
| 「让XX和XX讨论一下」 | "let XX and XX discuss" |
| 「梦蝶，议题是XX」 | "Mengdie, topic is XX" |

---

## Core Philosophy

Mengdie is not a debate—it's **multi-perspective symphony**.

| Debate | Mengdie |
|--------|---------|
| Win/Lose | Preserve disagreements |
| Eliminate dissent | Respect differences |
| One winner | Consensus + diversity |

### Three-Layer Conclusion Structure

1. **Consensus Conclusion**: Greatest common divisor, 1-2 sentences
2. **Diverse Viewpoint Array**: Table format, preserving important disagreements
3. **Preserved Disagreements**: Unresolved important disagreements (with each party's position summary)

## Trigger Words

Start Mengdie:
- "start a Mengdie discussion"
- "let's have a meeting"
- "let XX and XX discuss"
- "Mengdie, topic is XX"

Resume:
- "continue last discussion" → Load recent discussion records

---

## Relationship with Nuwa and Diting

| Skill | Repository | Purpose |
|-------|------------|---------|
| [Nuwa](https://github.com/alchaincyf/nuwa-skill) | Independent | Distill real people's thinking patterns |
| [Diting](https://github.com/EricArcha/diting-skill) | This project | Distill fictional characters' performance style |
| Mengdie | This project | Multi-perspective discussion orchestration |

| | Nuwa | Diting | Mengdie |
|---|---|---|---|
| Captures | HOW they think | HOW they behave | HOW they discuss |
| Source | Real people | Fictional characters | Orchestrates others |
| Output | Thinking framework | Performance script | Discussion outcomes |

## Quality Standards

| Check | Standard |
|-------|----------|
| Discussion rounds | Each participant speaks at least 3 rounds |
| Viewpoint depth | Each round has at least 3 sentences of substance |
| Moderator follow-up | At least 2 follow-up questions |
| Consensus conclusion | Reflects actual discussion, not compromise |
| Preserved disagreements | Genuinely exist, not manufactured |

---

## Directory Structure

```
mengdie/
├── SKILL.md                    # Main skill file
├── GOVERNANCE.md               # Governance index
├── README.md                   # Chinese version
├── README_en.md                # English version
├── references/                 # Reference templates
├── output/discussions/          # Discussion records
└── LICENSE                     # MIT License
```

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## License

MIT
