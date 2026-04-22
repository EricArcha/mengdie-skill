# 梦蝶 (Mengdie Roundtable)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-7B68EE?style=flat)](https://claude.com/claude-code)

> 「庄周梦蝶，多视角交融，方见真章。」

多视角讨论 Skill。协调多个视角 Skill 进行讨论，产出共识结论 + 多元观点阵列 + 保留分歧点。

[**English README**](README_en.md)

---

## 快速开始

### 安装（终端）

```bash
git clone https://github.com/EricArcha/mengdie-skill.git ~/.claude/skills/mengdie
```

或手动复制：
```bash
cp -r mengdie ~/.claude/skills/
```

重启 Claude Code 或输入 `/skills reload` 即可使用。

### 激活

| 中文 | English |
|------|---------|
| 「开一个梦蝶讨论」 | "start a Mengdie discussion" |
| 「开个会吧」 | "let's have a meeting" |
| 「让XX和XX讨论一下」 | "let XX and XX discuss" |
| 「梦蝶，议题是XX」 | "Mengdie, topic is XX" |

---

## 核心定位

梦蝶取自庄周梦蝶的典故，象征多视角的交融与思辨。

梦蝶的核心使命是将多个视角 Skill 组织成讨论模式，对指定议题进行讨论，产出有价值的结论。

## 与辩论的本质区别

| 辩论 | 梦蝶 |
|------|------|
| 分胜负，一方赢一方输 | 求理解，保留分歧 |
| 消灭异见 | 尊重差异 |

## 三层结论结构

1. **共识结论**：最大公约数，1-2句话
2. **多元观点阵列**：表格形式，保留重要分歧
3. **保留分歧点**：列出未能解决的重要分歧（含各方立场摘要）

## 触发词

启动梦蝶：
- 「开一个梦蝶讨论」
- 「开个会吧」
- 「让XX和XX讨论一下」
- 「梦蝶，议题是XX」
- 「来讨论一下XX」

扩展触发词：
- 「继续上次讨论」→ 读取最近的讨论记录

## 执行流程（详细见 SKILL.md）

| Phase | 内容 | 关键动作 |
|-------|------|---------|
| 0 | 启动判断 | 判断完整启动/引导补充/续接讨论 |
| 1 | 确认参数 | 议题、参与者、主持人、**Skill 验证** |
| 2 | 讨论执行 | 开场→第一轮→第二轮→自由讨论→收尾 |
| 3 | 结论输出 | **先保存**→输出结论 |
| 4 | 安可 | 用户追问1-3轮 |
| 5 | 质量自检 | 内部检查，不输出 |

## 参与者来源

| 来源 | 格式 | 示例 |
|------|------|------|
| 女娲 | XX-perspective | elon-musk-perspective |
| 谛听 | character-XX | character-wukong-journey |
| 其他已安装 Skill | 直接使用 | character-lindiya-youth |

## 质量标准

| 检查项 | 通过标准 |
|--------|---------|
| 讨论轮次 | 每位参与者至少发言3轮 |
| 观点深度 | 每轮至少3句话有实质内容 |
| 主持人追问 | 至少追问2次 |
| 共识结论 | 真实反映讨论，不是和稀泥 |
| 保留分歧 | 真实存在，非刻意制造 |

## 与女娲和谛听的关系

| Skill | 仓库 | 用途 |
|-------|------|------|
| [女娲 (Nuwa)](https://github.com/alchaincyf/nuwa-skill) | 独立项目 | 蒸馏真实人物的思维方式 |
| [谛听 (Diting)](https://github.com/EricArcha/diting-skill) | 本项目 | 蒸馏虚构角色的表演风格 |

梦蝶是 Skill 编排层，调用女娲和谛听生成的 Skill 进行多视角讨论。

---

## 目录结构

```
mengdie/
├── SKILL.md                    # 主 Skill 文件（执行标准）
├── GOVERNANCE.md               # 治理索引（已精简）
├── README.md                   # 本文件
├── README_en.md                # English version
├── references/                 # 参考模板（核心内容已内联到 SKILL.md）
├── output/discussions/          # 讨论记录输出
└── LICENSE                    # MIT License
```

---

> 本文档对应 SKILL.md v2.0
> 版本：2.0
> 最后更新：2026-04-23
