# Poet · 诗人 Skill

A Chinese poetry composition skill for Claude, grounded in classical poetics theory and the [chinese-poetry](https://github.com/chinese-poetry/chinese-poetry) corpus.

为 Claude 打造的中文写诗技能，以 chinese-poetry 数据库为范本、以《沧浪诗话》和《人间词话》为诗评框架。

---

## Features · 功能

- **Genres**: 绝句 (quatrain), 律诗 (regulated verse), 词 (ci / lyrics), 古风 (ancient-style), 现代诗 (modern poetry)
- **Formal techniques**: 藏头诗 (acrostic), 回文诗 (palindrome), 步韵 (step-rhyme), 限韵 (restricted rhyme)
- **Style emulation**: Mimics specific poets by analyzing their actual works from the corpus — not from labels
- **Poetics critique**: Every poem is delivered with a critique using categories from Yan Yu's *Canglang Shihua* (沧浪诗话) and Wang Guowei's *Renjian Cihua* (人间词话)
- **Anti-AI-slop guardrails**: Specific strategies to avoid the "fluent but soulless" patterns common in AI-generated poetry

## Installation · 安装

### Via the Claude desktop app

Copy the entire `SKILL.md` and paste it into the skill creation dialog (triggered by `/save-skill` or the skills panel). The skill registers under the name `poet`.

### Manual

Place `SKILL.md` in your skills directory. Triggered by keywords: 写诗、作诗、填词、藏头诗、步韵、诗评、poem.

## Skill structure · 技能结构

```
poet-skill/
├── SKILL.md      # The skill definition (frontmatter + full instructions)
├── README.md     # This file
└── LICENSE       # MIT
```

## Core principles · 核心理念

1. **境界为最上** (Realm/artistic conception is supreme) — Wang Guowei
2. **诗道在妙悟** (The way of poetry lies in inspired insight) — Yan Yu
3. **先辨气象，次论兴趣，末议格律** — Judge by vitality and atmosphere first, emotional texture second, prosody last

## Dependencies · 依赖

This skill fetches poems from the [chinese-poetry/chinese-poetry](https://github.com/chinese-poetry/chinese-poetry) GitHub repository as its source of canonical examples. No other external dependencies.

## License · 许可

MIT — see [LICENSE](./LICENSE).

## Author · 作者

Created by Cowork 3P · 2026
