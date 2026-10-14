# content-topic-decomposer

A [Claude](https://claude.ai) skill that turns **any topic** into a balanced content plan.

> 中文说明见 [README.zh-CN.md](README.zh-CN.md)

Most people who write about a topic keep making the same kind of post. This skill splits a topic along three axes so the plan has no blind spots:

1. **Five content types**, each doing a different job for the reader
   | Type | Gives the reader |
   |---|---|
   | Tutorial | clarity |
   | Case | credibility |
   | Opinion | recognizability |
   | Story | warmth and memorability |
   | Resource | something to save and share |
2. **Four reader stages**: stranger → just learned → about to act → already using
3. **Four formats**: graphic post, short video, long article, livestream

It then picks 2 or 3 pieces of your *real* experience and shows how to reuse each as a tutorial, a case and a story (一鱼多吃), with a different protagonist, hook and ending for each.

It plans content. It does not write the final posts unless you ask afterwards.

## What it does not do
- It does not invent your experience. Cases and stories are written as slots that say what real material to dig up, because made-up proof destroys trust.
- It does not assume a platform. Formats are generic; tell it "Xiaohongshu", "WeChat official account", "Substack" or "blog" and it adapts.

## Install

**Claude Code** (personal skills):
```bash
git clone https://github.com/meiluosi/content-topic-decomposer.git
cp -r content-topic-decomposer/skills/content-topic-decomposer ~/.claude/skills/
```

**Claude.ai / Claude desktop**: zip the `skills/content-topic-decomposer` folder (the `SKILL.md` must sit at the top level of the zip's folder) and upload it under Settings → Capabilities → Skills.

## Use

Just describe your topic. It triggers on requests like:

- "I know a lot about X; help me turn it into a content series."
- "What can I post about X besides tips?"
- "把『模型后训练里的 SFT』拆成一套内容选题"
- "我有一段经历，帮我做成教程版、案例版和故事版"

The more real material you mention (projects, experiments, clients, mistakes), the better the case and story slots get.

## Contents

```
skills/content-topic-decomposer/
├── SKILL.md                    # workflow and principles
└── references/
    ├── five-types.md           # the five types: jobs, questions, quality bars, failure modes
    ├── reader-stages.md        # the four reader stages
    ├── formats.md              # four formats and which type fits which
    ├── repurposing.md          # one experience → several versions
    └── output-template.md      # shape of the final plan
examples/
├── sft-post-training.zh.md     # worked example (Chinese): SFT in LLM post-training
└── back-pain-physio.en.md      # worked example (English): a physiotherapist building an audience
```

## Credit
The five-type split is adapted from the framework described in the book 《把自己变成一门生意》. This repository is an independent implementation and contains no text from the book.

## License
MIT
