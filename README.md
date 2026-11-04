# 写作风格档案 writer-dna（Style Alchemy 备选）

> **[writer-dna](https://github.com/simlpandordinary/writer-dna)** —— 飞书《WorkBuddy 视频系列 · 全技能与提示词总目录》里推荐的开源技能，已拆分为独立仓库分发（一个技能一个仓库）。

| 项 | 内容 |
| - | - |
| 上游仓库 | <https://github.com/liangjfblue/writer-dna> |
| 上游路径 | `templates/khazix-writer` |
| 上游协议 | 未声明（见上游） |
| 上游 Star | 112 |
| 拆分方式 | 仅抽取该技能自身文件，独立可用 |

## 技能说明

|

## 目录结构

```
['.gitkeep', 'SKILL.md', 'references/.gitkeep', 'references/content_methodology.md', 'references/scenes/scene_examples.md', 'references/style_examples.md', 'wiki/.gitkeep', 'index.html', 'README.upstream.md', 'CLAUDE.md']
```

- `SKILL.md` 是技能入口（触发条件 / 工作流 / 约束），安装时必须位于技能根目录。
- `references/`、`scripts/`、`assets/` 为该技能自带的参考文档、脚本与素材。
- `README.upstream.md` 为上游仓库原始说明，保留出处与版权信息。
- `LICENSE` 为上游许可证原文。

## 安装

WorkBuddy 技能目录为 `~/.workbuddy/skills/writer-dna/`：

```bash
git clone https://github.com/simlpandordinary/writer-dna.git ~/.workbuddy/skills/writer-dna
```

也可以直接对 AI 说：「把 <https://github.com/simlpandordinary/writer-dna> 装成 Skill」。

安装后用自然语言触发，例如「写作风格档案 writer-dna（Style Alchemy 备选）」「用 writer-dna 帮我处理这个任务」。

上游 `raw/`（个人样本）与 `outputs/`（产物）未收录，避免带入个人素材。

## 版权

原始作者与版权归上游仓库 `liangjfblue/writer-dna` 所有。本仓库仅做独立分发与结构整理，未修改技能内容；商用请遵循上游许可证。
