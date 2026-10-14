# content-topic-decomposer（主题内容拆解）

一个 [Claude](https://claude.ai) skill：把**任何主题**拆成一套结构均衡的内容规划。

> English: [README.md](README.md)

大多数人围绕一个主题持续输出时，会一直写同一种内容。这个 skill 从三个维度拆解主题，让规划没有盲区：

1. **五种内容类型**，每种为读者完成不同的任务
   | 类型 | 给读者什么 |
   |---|---|
   | 教程型 | 清晰度 |
   | 案例型 | 可信度 |
   | 观点型 | 辨识度 |
   | 故事型 | 温度与记忆点 |
   | 资源型 | 可收藏、可转发 |
2. **四个读者阶段**：不认识你 → 刚了解 → 准备行动 → 已经在用
3. **四种形式**：图文、短视频、长文、直播

随后它会挑出 2～3 段你的**真实经历**，示范如何一鱼多吃：同一段素材改写成教程版、案例版、故事版，每个版本的主角、开头和结尾都不同。

它只做规划，不会直接代写成稿，除非你接着要求。

## 它不会做的事
- 不会编造你的经历。案例和故事只会写成"待填空位"，告诉你该去找什么真实素材，因为编造的证据会毁掉信任。
- 不预设平台。形式是通用的；你说"小红书""公众号""博客"，它再按平台调整。

## 安装

**Claude Code**（个人 skill）：
```bash
git clone https://github.com/meiluosi/content-topic-decomposer.git
cp -r content-topic-decomposer/skills/content-topic-decomposer ~/.claude/skills/
```

**Claude.ai / Claude 桌面端**：把 `skills/content-topic-decomposer` 文件夹打成 zip（`SKILL.md` 需在文件夹顶层），在 设置 → 能力 → Skills 中上传。

## 使用

直接描述你的主题即可，例如：

- "我很懂某个主题，帮我做成一套系列内容"
- "除了干货技巧，我还能发什么？"
- "把『模型后训练里的 SFT』拆成一套内容选题"
- "我有一段经历，帮我做成教程版、案例版和故事版"

你提供的真实素材（项目、实验、客户、踩过的坑）越多，案例和故事部分就越具体。

## 目录

```
skills/content-topic-decomposer/
├── SKILL.md                    # 工作流与原则
└── references/
    ├── five-types.md           # 五种类型：任务、提问、质量标准、常见失败
    ├── reader-stages.md        # 四个读者阶段
    ├── formats.md              # 四种形式及其与类型的搭配
    ├── repurposing.md          # 一段经历 → 多个版本
    └── output-template.md      # 最终规划的输出结构
examples/
├── sft-post-training.zh.md     # 示例（中文）：大模型后训练中的 SFT
└── back-pain-physio.en.md      # 示例（英文）：理疗师为久坐人群做腰背痛内容
```

## 致谢
五种内容类型的划分改编自《把自己变成一门生意》一书中的框架。本仓库为独立实现，不包含该书原文。

## 许可
MIT
