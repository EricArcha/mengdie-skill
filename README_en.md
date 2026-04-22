# Mengdie · Multi-Perspective Discussion Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-7B68EE?style=flat)](https://claude.com/claude-code)

> "Zhuangzi dreamed of a butterfly—a symbol of multiple perspectives merging and debated."

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

### Activation

Restart Claude Code or type `/skills reload`, then:

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

---

## Relationship with Nuwa and Diting

| Skill | Purpose | Project |
|-------|---------|---------|
| [Nuwa](https://github.com/alchaincyf/nuwa-skill) | Distill real people's thinking patterns | Independent |
| [Diting](https://github.com/EricArcha/diting-skill) | Distill fictional characters' performance style | This project |
| Mengdie | Multi-perspective discussion orchestration | This project |

| | Nuwa | Diting | Mengdie |
|---|---|---|---|
| Captures | HOW they think | HOW they behave | HOW they discuss |
| Source | Real people | Fictional characters | Orchestrates others |
| Output | Thinking framework | Performance script | Discussion outcomes |

---

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
│   ├── round-table-template.md
│   ├── moderation-protocol.md
│   └── conclusion-format.md
├── output/discussions/          # Discussion records
└── LICENSE                     # MIT License
```

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## License

MIT
