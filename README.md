# Poet · 诗人 Skill

A Chinese poetry composition skill for Claude — grounded in classical poetics, powered by the [chinese-poetry](https://github.com/chinese-poetry/chinese-poetry) corpus. **Gu Xianrong's Tianci Menjing (填词门径) is the structural backbone**, with Yan Yu's Canglang Shihua and Wang Guowei's Renjian Cihua as complementary pillars.

为 Claude 打造的中文写诗技能。以顾宪融《填词门径》为填词统揽，严羽《沧浪诗话》统揽诗道，王国维《人间词话》贯串诗词，chinese-poetry 数据库为范本。

---

## Theory Framework · 理论体系

| 著作 | 地位 | 核心范畴 |
|------|------|----------|
| **顾宪融《填词门径》** | 填词之纲 | 选调·十六要诀·意内言外·先空后实·起结转折·北宋重拙大/南宋深细密 |
| 严羽《沧浪诗话》 | 诗道统揽 | 妙悟·兴趣·气象·辨体·入神·别材别趣 |
| 王国维《人间词话》 | 诗词通贯 | 境界·有我/无我·造境/写境·隔与不隔·忧生忧世 |

### 十六要诀 (16 Keys to Ci Poetry)

From Sun Linzhi's Cijing, adopted by Gu Xianrong:

> **清 轻 新 雅 灵 脆 婉 转 留 托 澹 空 皱 韵 超 浑**

Eight for sonic-emotional quality, six for technique.

### Ci Tune Selection (选调)

词调各有声情 — every ci tune carries its own emotional register. Picking the right tune for the right mood is the **first and most important decision** in ci composition.

## Features · 功能

- **Genres**: 绝句 / 律诗 / 词 / 古风 / 现代诗
- **Formal techniques**: 藏头 / 回文 / 步韵 / 限韵
- **Style emulation**: Mimics specific poets from corpus analysis, not stereotypes
- **Critique**: Every poem delivered with evaluation using the relevant theoretical framework
- **Anti-AI guardrails**: 填词尤戒三病 (清·新 / 留·托 / 空·澹)

## Skill Structure · 章节

```
SKILL.md
  ├── 核心立场（以填词门径为纲）
  ├── 填词门径（顾宪融）★ 独立顶级章节
  │   ├── 词与诗之别
  │   ├── 十六要诀
  │   ├── 意内言外
  │   ├── 先空后实
  │   ├── 布局·起结·转折
  │   ├── 选调（词牌与声情匹配）
  │   └── 用韵
  ├── 范本源：chinese-poetry 数据库
  ├── 评骘框架（沧浪 + 人间词话）
  ├── 工作流程（5 Step）
  ├── 格律规范
  ├── 反 AI 诗味
  └── 诗论提要
```

## Installation · 安装

Copy `SKILL.md` into your Claude Code skills directory, or paste into the skill creation dialog.

**Trigger words**: 写诗 / 作诗 / 填词 / 词牌 / 诗评 / poem / 藏头诗 / 步韵

## Dependencies · 依赖

[chinese-poetry/chinese-poetry](https://github.com/chinese-poetry/chinese-poetry) — the largest open-source database of classical Chinese poetry (~55k Tang poems, 260k Song poems, 21k Song ci).

## License · 许可

MIT

---

*Gu Xianrong (1898-1955), courtesy name Foying, pseudonym Damo Shiren. His ci pedagogy — systematic, beginner-friendly, never obscure — is the structural spine of this skill.*
