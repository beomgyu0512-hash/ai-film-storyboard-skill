# 复制给 Agent，快速开始

解压后，将整个 `film-storyboard-workflow` 文件夹交给 Agent，并复制：

```text
请先读取 film-storyboard-workflow/SKILL.md，按其中流程处理我提供的情节。
已有成果时，按我指定的层进入；未指定则询问。
按模板交付，每幕一个 Markdown 文件，并执行检查与反馈。

情节文件／文字：〔附文件或粘贴文字〕
已有成果与已确认要求：〔有则提供〕
本次处理范围：〔集数、幕或镜号〕
```

## 怎么用

1. 提供情节文字、TXT 或 Word。
2. 依次完成叙事、导演、分镜；已有成果可以从对应层进入。
3. 查看幕文件顶部的检查结果。要改某镜，写明集数、幕号和“第几镜”。

## 文件位置

| 文件／目录 | 用途 |
|---|---|
| [SKILL.md](SKILL.md) | Agent 总入口 |
| [三层执行规则](references/three_layer_execution.md) | 各层输入、步骤、输出、修改边界 |
| [交接模板](assets/layer_handoff.md) | 已确认内容与修改范围 |
| [分镜模板](assets/storyboard_template.md) | 每幕分镜格式 |
| [检查约束](references/scene_storyboard_constraints.md) | 一致性4项、观众体验5项 |
| [知识库调用规则](references/knowledge_call_rules.md) | 查阅顺序、出处与适用条件 |
| references/knowledge/ | 三层知识索引、正文与参考模板 |
| [上游参考索引](references/upstream_index.md) | 已下载的导演与分镜机制 |
| [修改记录模板](assets/modification_log_template.md) | 记录问题、修改及复查结果 |

## 修改记录是什么

每次修改记录五项：**问题表现 → 所属层与依据 → 修改内容 → 修改后结果 → 是否值得改系统规则**。

它保存为项目独立的 MD，分镜只链接对应条目。最后一项用于积累优化建议，不会自动改规则。
