# Podcast Writing

面向 Codex 的播客策划、写稿与 shownotes skill。它会先判断当前处于选题策划、录前准备、录制辅助、录后整理还是发布阶段，再按节目类型和交付物选择写法。

## 能做什么

- 撰写口播稿、节目大纲、主持提纲、访谈问题单和录制提示卡
- 整理录音转写，保留不同说话者的表达与观点归属
- 根据全文转录和概要改写 shownotes，并核对自动转录可能出现的专名、观点归属和剪辑差异
- 支持单口、双人聊天、访谈、圆桌、纪实、科普、新闻评论、音乐、灵异与虚构节目
- 遵守录前与录后材料的边界，不把计划内容误写成节目实况

## 安装

将本仓库放入 Codex 的个人 skills 目录，并确保目录结构如下：

```text
podcast-writing/
├── SKILL.md
└── references/
    ├── author-style.md
    ├── formats.md
    ├── shownotes.md
    └── spoken-style.md
```

Windows 默认位置为 `%USERPROFILE%\.codex\skills\podcast-writing`；也可以使用 `$CODEX_HOME\skills\podcast-writing`。安装后在 Codex 中使用 `$podcast-writing`，或直接提出播客写稿、录后整理和 shownotes 需求。

## 文件说明

- `SKILL.md`：阶段判断、写作流程、事实边界和交付原则
- `references/author-style.md`：依据作者过往内容提炼并延续表达风格
- `references/formats.md`：不同播客类型与制作阶段的写法
- `references/spoken-style.md`：口播可听性与多人互动
- `references/shownotes.md`：shownotes 的材料等级、转录概要处理、发言归属和时间章节规则

## 说明

欢迎下载并在自己的播客创作中使用这个 skill，也欢迎通过 GitHub Issues 反馈使用体验、提出建议或报告问题。反馈时如果能附上使用场景和期望效果，会更方便改进。
