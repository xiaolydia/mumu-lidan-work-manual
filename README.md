# mumu-lidan-work-manual

An unofficial agent skill distilled from 《李诞工作手册（全新修订版）》 by 李诞.

It turns the book's working methods into a practical toolkit for:

- content creation and self-media positioning;
- personal IP / creator mindset;
- livestreaming, reading letters, and companionship-style content;
- stand-up writing and spoken scripts;
- performance rhythm and camera/stage expression;
- creative meetings, read-through meetings, pitch, and pre-interviews;
- professional collaboration in content teams.

This repository contains a synthesized skill, not the book text. It does not include the original book file, scans, raw chapters, or long excerpts.

## Who This Is For

Use this skill if you want an AI agent to help you think like a practical content lead rather than a generic writing assistant.

It is especially useful for:

- creators building a personal IP;
- AI bloggers planning content series;
- video creators writing spoken scripts;
- livestream hosts designing audience relationships;
- content teams running topic meetings or read-through meetings;
- founders or solo creators pitching ideas to clients, users, or collaborators.

## Installation

### Codex / local skills

Clone the repository into your skills directory:

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/xiaolydia/mumu-lidan-work-manual.git ~/.codex/skills/mumu-lidan-work-manual
```

Then restart Codex or reload your skills list.

### Amp / agents skills

If your agent reads skills from `~/.config/agents/skills`, install it there:

```bash
mkdir -p ~/.config/agents/skills
git clone https://github.com/xiaolydia/mumu-lidan-work-manual.git ~/.config/agents/skills/mumu-lidan-work-manual
```

### Manual install

You can also copy the whole folder into any compatible skills directory. Keep this structure:

```text
mumu-lidan-work-manual/
  SKILL.md
  README.md
  chapters/
  patterns.md
  cheatsheet.md
  glossary.md
  source-notes.md
```

## How To Use

Mention the skill by name in your prompt:

```text
Use mumu-lidan-work-manual to help me design my AI creator positioning.
```

The agent should:

1. read `SKILL.md`;
2. identify the relevant topic;
3. read the matching chapter file if the topic needs more depth;
4. answer with concrete diagnosis, tradeoffs, and next actions;
5. avoid quoting or recreating the source book.

## Good Prompts

### Personal IP positioning

```text
Use mumu-lidan-work-manual to analyze my creator positioning.
I want to be an AI blogger, but I do not want to become a generic AI tools account.
Help me define my motive, audience, persona, and content pillars.
```

### Video topic planning

```text
Use mumu-lidan-work-manual to turn these rough notes into a 30-day video topic plan.
Prioritize topics that show real judgment, long-term style, and useful audience value.
```

### Script rewriting

```text
Use mumu-lidan-work-manual's verbatim draft and delete-to-the-bone principles.
Rewrite this short video script so it is more speakable, concrete, and emotionally clear.
```

### Livestream or companionship content

```text
Use mumu-lidan-work-manual to design a livestream format for an AI creator.
I want it to feel useful and companionable, not like a hard-selling webinar.
```

### Creative meeting

```text
Use mumu-lidan-work-manual to design a read-through meeting process for my content team.
We need rules for bringing drafts, giving feedback, deciding who has final say, and leaving with next actions.
```

### Pitch and pre-interview

```text
Use mumu-lidan-work-manual to help me pitch this content idea to a client.
Give me several options, likely objections, and a way to ask better pre-interview questions.
```

## Topic Map

| Need | Read |
|---|---|
| creator motive, self-media positioning, livestream companionship, data anxiety | `chapters/01-self-media-mindset.md` |
| persona, authenticity, exposure, criticism, emotional cooling | `chapters/02-authenticity-and-exposure.md` |
| creative work rhythm, treating content as work, practice through real projects | `chapters/03-work-and-creative-rhythm.md` |
| scripts, verbatim drafts, deleting weak wording, topic boundaries, value through story | `chapters/04-writing-and-ideas.md` |
| performance, stage/camera attention, emotional connection, rhythm, style | `chapters/05-performance-and-style.md` |
| program design, short-form work, five-minute pieces, public growth | `chapters/06-program-and-short-work.md` |
| read-through meetings, creative collaboration, pitch, pre-interview | `chapters/07-meetings-pitch-and-preinterview.md` |
| career doubts, hard and correct work, professionalism, cross-role learning | `chapters/08-career-and-professionalism.md` |

Supporting files:

- `patterns.md`: reusable operating patterns.
- `cheatsheet.md`: quick checklist for content, script, performance, meetings, and career choices.
- `glossary.md`: key terms.
- `source-notes.md`: source metadata, public release notes, and limits.

## Recommended Agent Behavior

When using this skill, the agent should not merely summarize the book. It should behave like a working content lead:

- identify the user's real constraint;
- separate creator mode from distributor mode;
- avoid persona-first advice;
- look for the user's real motive and sustainable content rhythm;
- convert abstract advice into concrete prompts, scripts, meeting rules, or content plans;
- preserve the author's practical emphasis without copying long source passages.

## Example Output Style

Weak answer:

> You should be sincere and create good content.

Better answer:

> Your current topic list is too tool-led. If you publish these as-is, the audience will remember the tools, not you. Reframe the series around the recurring human problem: "I collected too many AI tools but still cannot finish real work." Then use each tool only as one step in a workflow. Start with these three episodes...

## Public-Use Notes

This skill is unofficial and not affiliated with the author or publisher of 《李诞工作手册（全新修订版）》.

The book copyright belongs to the original rights holders. This repository contains a synthesized, transformative working toolkit intended for personal learning and agent behavior design. It is not a replacement for the book.

If you find the ideas useful, read the original book through legitimate channels.
