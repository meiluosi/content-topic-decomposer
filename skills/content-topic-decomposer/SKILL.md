---
name: content-topic-decomposer
description: Break any topic into a balanced content plan across five content types (tutorial, case, opinion, story, resource), tagged by reader stage (stranger, just learned, about to act, already using) and by format (graphic post, short video, long article, livestream), then show how to reuse one piece of real experience as several versions. Use this whenever the user wants to plan content around a subject, e.g. "what can I post about X", "turn my expertise in X into a content series", "build a content map / content pillars / topic outline / editorial calendar for X", "I know a lot about X but don't know what to write", or in Chinese "拆解主题", "选题规划", "内容矩阵", "一个主题怎么做成系列内容", "小红书/公众号/博客写什么", "一鱼多吃". Works for any topic that has an audience, not just business topics. Use it even when the user doesn't mention the five types. It plans content; it does not write the final posts unless asked afterwards.
---

# Content Topic Decomposer

A topic is not content. "SFT", "back pain" or "independent coffee shops" can each fill a hundred posts, and most people write the same kind of post a hundred times. This skill turns a topic into a *balanced* set of ideas, because each content type does a different job for the reader:

| Type | Gives the reader | Question it answers |
|---|---|---|
| Tutorial | clarity | How do I do / understand this? |
| Case | credibility | Has anyone really done this, and what changed? |
| Opinion | recognizability | What do you believe that others don't? |
| Story | warmth and memorability | Why should I remember you? |
| Resource | savability and shareability | What can I keep and reuse? |

Only tutorials: informative but forgettable. Only opinions: loud but unproven. Only stories: charming but nothing to take away. A mature topic has all five. (The five-way split is adapted from the framework in the book 《把自己变成一门生意》.)

Reply in the user's language.

## Workflow

### 1. Intake, kept light
Get four things: **topic**, **audience** (who, and what they already know), **creator's goal** (trust, leads, traffic, personal brand, sharing), and **real material** the creator has (projects done, experiments run, mistakes made, clients served, tools used). Read these from the request first. If something is missing, state a one-line assumption and proceed; ask at most 2 or 3 questions, and only when the answer would change the plan. The real-material question matters most, because cases and stories cannot be invented (see Principles).

Classify the topic kind (knowledge/technical, craft/skill, commercial/service, lifestyle/experience, creative). Each type looks different across kinds; `references/five-types.md` has the adjustments.

### 2. Split the topic into nodes
Before generating ideas, break the topic into 5 to 8 nodes: the concepts, steps, decisions, mistakes, tools and results a reader meets on the way. Ideas generated per node stay distinct; ideas generated from the bare topic all circle one point.

### 3. Build the map
For each of the five types, write 3 to 5 ideas (more if the user wants a bigger pool). Each idea gets: a working title with a concrete object in it, a one-line angle, the reader stage it serves, a recommended format, and the **material needed** from the creator. Use the generating questions and quality bars in `references/five-types.md`, the stage definitions in `references/reader-stages.md`, and the format guidance in `references/formats.md`.

### 4. Diagnose
Lay the ideas out as type × reader-stage and look for empty cells and pile-ups. Say in 2 to 4 sentences what is missing and what to produce first. Typical fixes: no entry point for strangers, no proof for people about to act, nothing for people already using it.

### 5. Choose hero material and plan reuse
Pick 2 or 3 pieces of real experience rich enough to be told several ways, and show how each becomes a tutorial, a case and a story version (plus opinion/resource spin-offs if they fit), then fans out across formats. Give every hero the same completeness (tutorial, case and story versions each with protagonist and hook), not a full chain for the first and sketches for the rest. Follow `references/repurposing.md`. If the user already supplied raw material and asked for reuse, start here and skip most of step 3.

### 6. Sequence
Suggest an order, not necessarily a calendar. A reliable default: open with an opinion or story for strangers, anchor with a tutorial, prove with a case, then publish a resource that collects it all. Give a dated calendar only if asked. If the user names a platform, adjust lengths and hooks to it; if not, stay at the format level (graphic, video, long, live), since platform rules change often.

## Output
Follow `references/output-template.md`: assumptions, topic nodes, the map (one table per type), coverage check, hero material with reuse chains, suggested order, and an offer to draft any item. Keep it scannable. About 20 to 25 ideas is plenty for a first pass; the aim is a plan the user can act on this week.

## Principles
- **Never invent the creator's experience.** A fabricated case or story destroys the credibility it exists to build, and the user then publishes it. Where a case or story needs real material, write the idea as a slot and say what the creator should dig up ("a run where the loss looked fine but outputs were bad"). Describe the *kind* of scene or experience to look for ("a run that looked fine but behaved wrongly"), but do not suggest a specific cause, ending or detail the creator might adopt as if it had happened to them; made-up numbers, clients, quotes and causes are not allowed. If the creator has little experience, propose cheap ways to generate it (a small experiment, reproducing a public result, teardown of a public example).
- **An opinion must be arguable.** Test: could a thoughtful person disagree? If not, it is a tutorial in disguise. State the common belief, the creator's stance, the reason, and where the stance would be wrong.
- **Titles name a concrete thing.** "Why your 3-epoch run overfits" beats "Tips for better training".
- **Match the stage to the type.** Strangers rarely read a 4,000-word tutorial; people about to act want proof, not hot takes.
- **Plan first, draft on request.** Finish the map, then offer to write any item or turn a hero idea into full drafts.
