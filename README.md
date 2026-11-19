# 建筑效果图 Skill

用 CAD/PDF 和 SketchUp 的设计依据、同机位截图与真实家具产品样本，制作和验收受控建筑效果图。适用于建筑室内外项目，可从已有模型、机位资料或验收记录继续。

## 安装

下载本仓库后，将完整的 `controlled-archviz` 文件夹复制到 `~/.agents/skills/`。Windows 可在资源管理器中打开 `%USERPROFILE%\.agents\skills`。复制后，`controlled-archviz/SKILL.md` 应直接位于该技能文件夹中。已有同名技能时，可先比较版本再决定是否替换。

## 调用

- ChatGPT Work 桌面端使用本机文件的会话中，输入 `@` 搜索「建筑效果图 Skill」。
- Codex CLI 输入 `$controlled-archviz`，或使用 `/skills` 查找。

可以在选中技能后发送：

> 按 V2.1 接续这个 SketchUp 模型的单机位效果图。先只读检查现有模型、设计图纸、机位截图和家具样本，说明能从哪一步继续，以及需要补齐的输入。

技能包含 G1–G5 工作流程、同机位索引卡、家具样本卡、续作记录和 P0/P1/P2 验收模板。SketchUp 操作取决于当前环境提供的 MCP 能力。公开版仅包含说明和模板。
