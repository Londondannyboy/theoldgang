# The Old Gang — Claude Code Guide

## What This Project Is
"The Old Gang" is a novel being written using a tag-team workflow:
- **Claude Desktop** is the Editorial Director — holds strategy, develops story, reviews and accepts drafts
- **Claude Code** is the Writer — executes chapter drafts from detailed briefs

## Origin
This story had no prior written documentation — it lived entirely in the author's head. The bible files were captured across five brain dump sessions and represent the foundational creative vision. Treat them as authoritative but expect evolution through editorial sessions.

## Before You Write Anything
1. Read this file completely
2. Read `bible/PREMISE.md` for the story premise, themes, and central irony
3. Read `bible/CHARACTERS.md` for all character details — deeply developed
4. Read `bible/WORLD.md` for settings, real-world anchors, and historical detail
5. Read `bible/LAYERS.md` for the story's layered revelations — CRITICAL
6. Read `bible/STYLE_GUIDE.md` for voice, tone, POV, and prose rules
7. Read `bible/CONTINUITY.md` for established facts
8. Read the specific chapter brief in `outline/chapters/` for the chapter you're writing

## Workflow
- Chapter briefs arrive in `outline/chapters/` as `chXX-brief.md`
- Write drafts into `drafts/` as `chXX-draft.md`
- After editorial review and acceptance, approved chapters move to `manuscript/` as `chXX.md`
- Never edit files in `manuscript/` unless explicitly instructed
- After writing, update `bible/CONTINUITY.md` with any new facts established

## Writing Rules
- Always follow `bible/STYLE_GUIDE.md`
- Do not contradict anything in `bible/CONTINUITY.md`
- The supernatural element must remain ambiguous for as long as possible
- The layers in `bible/LAYERS.md` must be revealed gradually — never jump ahead
- The Arthurian/Booth/Seventh Seal references should be FELT, never stated
- Do not invent major plot points not in the chapter brief — flag them as suggestions
- Keep each chapter as a single markdown file
- Use `---` for scene breaks within chapters

## Critical Story Notes
- The Old Gang are DEAD — clinically dead, cold, don't recognise cameras. Medical tests confirm death.
- Modern police misinterpret everything through modern frameworks — "dead" = slang, territory = postcode wars, violence = escalation
- The Old Gang can ONLY operate within streets Charles Booth coloured black/criminal on his 1886 Poverty Map
- Sarah's personal story (father wrongfully convicted, corrupt officers still in station) is interwoven with investigation
- The street gang Old Gang have their own honour — they are the PRODUCT of exploitation
- The TRUE Old Gang (City/East India Company layer) are the ones who CAUSED the exploitation — they adapt, they have different accents, they walk among us
- The Corrupt Policeman is Old Gang by LINEAGE — not supernatural, just institutional corruption inherited through generations
- The Camberwell Man has always been dead — doesn't know it — becomes a "deadly angel" ally
- The ultimate concept: as Sarah gets closer to death, death gets closer to life (Seventh Seal)

## Revision Workflow
- Review notes arrive in `review/notes/` as `chXX-review.md`
- Revised drafts: `chXX-draft-v2.md`, `chXX-draft-v3.md` etc.

## Commit Convention
- `scaffold:` / `brief:` / `draft:` / `review:` / `revise:` / `accept:` / `bible:` / `continuity:` / `decision:`

## Writing Workflow — How Chapters Are Produced

### The Tag-Team Process
1. **Claude Desktop** (Editorial Director) writes the chapter brief → commits to `outline/chapters/chXX-brief.md`
2. **Claude Code** (Writer) reads CLAUDE.md, the relevant bible files, and the chapter brief → writes the chapter → saves to `drafts/chXX-draft.md`
3. **Claude Desktop** reviews the draft, provides notes → saved to `review/notes/chXX-review.md`
4. **Claude Code** revises based on notes → saves as `drafts/chXX-draft-v2.md`
5. When approved, **Claude Code** copies to `manuscript/chXX.md` and updates `bible/CONTINUITY.md` with new facts

### Context Management
- **CLAUDE.md** = master orientation (read first, every session)
- **bible/CHARACTERS.md** = all characters (read before writing any chapter)
- **bible/STYLE_GUIDE.md** = voice, tone, POV rules (read before writing)
- **bible/CONTINUITY.md** = established facts (read before writing, update after)
- **outline/STRUCTURE.md** = full 28-chapter outline (reference for pacing and placement)
- **outline/chapters/chXX-brief.md** = specific chapter instructions (the "ticket")
- Each chapter brief specifies WHICH bible files are most relevant for that chapter

### What Gets Updated After Each Chapter
- `bible/CONTINUITY.md` — add any new facts established in the chapter
- `outline/STRUCTURE.md` — mark chapter as drafted/revised/accepted
- `CLAUDE.md` — update "Current Status" section below if needed

### Current Status
- **Last completed:** None — Chapter 1 brief ready to write
- **Next up:** Chapter 1 draft
- **Open decisions affecting next chapter:** None — Chapter 1 is straightforward setup
