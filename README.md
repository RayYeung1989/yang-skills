# yang-skills

我的 [Claude Code](https://docs.anthropic.com/en/docs/claude-code) 自定义技能集。

> **愿景**：希望人人都能通过做自己就能舒服地赚到钱。
> **核心信念**：持续输出你独特的自己，才是变现的最优路径。
> 
> 这个仓库里的每个 Skill，都是这套信念的武装化形态——不是教你怎么扭曲自己去迎合市场，而是帮你看见做自己就已经具备的独特价值，然后把它交付出去。

## 安装

```bash
# 克隆仓库到本地
git clone https://github.com/RayYeung1989/yang-skills.git

# 安装全部技能到 Claude Code 技能目录
cp -r yang-skills/yang-* ~/.claude/skills/

# 或安装单个技能
cp -r yang-skills/yang-diagnose ~/.claude/skills/
```

## 技能

| 技能 | 说明 |
|------|------|
| **yang-diagnose** | 认知定位诊断 — 帮高认知高敏感、有东西但出不来的知识型创业者，找到他做自己就已经具备的独特价值。核心功能：帮用户看见他自己看不见的认知资产和核心堵塞点 |

## 输出格式

所有技能输出为 Markdown 格式（`.md`），适用于 Obsidian / VSCode / Notion 等 Markdown 生态。

输出目录默认为 `~/Documents/yang-notes/`，文件名包含时间戳和核心关键词。
