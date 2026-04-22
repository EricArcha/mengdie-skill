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

## Discussion Highlights

Mengdie produces not debate records, but multi-perspective fusion insights. Here are excerpts from two discussions:

### On Love: Destiny vs. Gradual Accumulation

> **Super Dragon Ball Goku**: (shaking head) No. Love isn't something you think about—it's something you feel. Like when Bulma and I adventured together, when Kuririn and I trained together, those were real. Not thought out—actually experienced together.

> **Purple Cloud Fairy (Zixia)**: Right, experience. But before that, you first confirm the person. It's not about confirming after experiencing—once you confirm, you don't waver.

*—Core disagreement between Zixia and Dragon Ball Goku: Is recognition instantaneous or gradual?*

### On Products: Real Artists Ship

> **Steve Jobs**: A product is a gift to the user. You make something, then hand it to the user—that's the most sacred thing in the world. A bad product is an insult to the user. A good product is respect for the user.

> **Elon Musk**: What Trump describes is marketing, not product. Rockets either work or they don't—no reputation. A truly bad product and the company dies. Tesla almost died three times in 2008 because the product was actually good.

> **MrBeast**: Good product = shipped + positively impacted users. Both required.

*—All four participants agreed on one thing: a good product must reach users.*

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
