# The Old Gang — Claude Code Guide

## What This Project Is
"The Old Gang" is a novel being written using a tag-team workflow:
- **Claude Desktop** is the Editorial Director — holds strategy, develops story, reviews and accepts drafts
- **Claude Code** is the Writer — executes chapter drafts from detailed briefs

## Before You Write Anything
1. Read this file completely
2. Read `bible/PREMISE.md` for the story premise and themes
3. Read `bible/CHARACTERS.md` for all character details
4. Read `bible/STYLE_GUIDE.md` for voice, tone, POV, and prose rules
5. Read `bible/CONTINUITY.md` for established facts that must not be contradicted
6. Read the specific chapter brief in `outline/chapters/` for the chapter you're writing

## Workflow
- Chapter briefs arrive in `outline/chapters/` as `chXX-brief.md`
- Write drafts into `drafts/` as `chXX-draft.md`
- After editorial review and acceptance, approved chapters move to `manuscript/` as `chXX.md`
- Never edit files in `manuscript/` unless explicitly instructed — those are accepted drafts
- After writing, update `bible/CONTINUITY.md` with any new facts established in the chapter

## Writing Rules
- Always follow `bible/STYLE_GUIDE.md` — it is authoritative on voice, tense, POV, and prose style
- Do not contradict anything in `bible/CONTINUITY.md`
- Do not invent major plot points not in the chapter brief — flag them as suggestions instead
- Keep each chapter as a single markdown file
- Use `---` for scene breaks within chapters
- Do not add markdown headers within chapter prose (no # Chapter X at the top) — just write the prose

## Revision Workflow
- Review notes arrive in `review/notes/` as `chXX-review.md`
- Read the review notes, then revise the draft in `drafts/`
- Suffix revised drafts: `chXX-draft-v2.md`, `chXX-draft-v3.md` etc.

## Commit Convention
- `scaffold: initial project structure`
- `brief: ch01 scene breakdown`
- `draft: ch01 first draft`
- `review: ch01 editorial notes`
- `revise: ch01 v2 based on review`
- `accept: ch01 moved to manuscript`
- `bible: updated characters after ch01`
- `continuity: new facts from ch01`
- `decision: [short description of narrative choice]`
