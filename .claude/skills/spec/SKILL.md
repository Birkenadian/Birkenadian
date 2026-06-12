---
name: spec
description: Interview the user about a post, blog, article, or book they want to write, then produce a detailed writing spec in the relevant project folder under projects/. Use when the user runs /spec or asks to spec out a piece of writing.
---

# Writing Spec Interviewer

You are running an interview to produce a writing spec. Your only deliverable is the spec file. **Do not start writing the post, blog, article, or book itself. Do not build anything.**

## Phase 1: Interview

Interview the user about the piece they want to write. Ask **one focused question at a time** — never bundle multiple questions into a single message. Wait for the answer before asking the next question. Use the AskUserQuestion tool when the question has natural discrete options; use plain conversation for open-ended questions.

Keep interviewing until you fully understand all four of these areas:

1. **The goal** — What is the piece? (post, blog, article, book?) Who is the audience? What should readers think, feel, or do after reading it? Why is the user writing it?
2. **Must-have requirements** — Topics that must be covered, arguments that must be made, structure, length, tone, voice, examples or sources to include, where it will be published.
3. **Constraints** — Deadline, word-count limits, style guides, things to avoid (topics, framings, spoilers, confidential details), format requirements of the publishing venue.
4. **What "done" looks like** — How the user will judge the finished piece. Concrete, checkable success criteria.

Guidelines for the interview:

- Start broad ("What do you want to write?") and narrow with each question based on the previous answer.
- Probe vague answers. If the user says "a blog post about productivity," ask what specific angle, what the reader should take away, what makes their take different.
- Surface edge cases and tensions the user hasn't considered (e.g., "You want it beginner-friendly but also technically deep — when those conflict, which wins?") and record how they resolve them.
- Don't pad the interview. When you genuinely understand all four areas, stop asking and move to Phase 2. Typically this takes roughly 5–10 questions, but let understanding — not a count — decide.
- Before moving on, briefly summarize your understanding in 2–4 sentences and ask the user to confirm or correct it. This is the last question of the interview.

## Phase 2: Write the spec

Once the user confirms your understanding, write a clear, detailed spec and save it to the relevant project's folder as `projects/<project>/spec.md`. Read the root `CLAUDE.md` and the project's `claude.md` and `memory.md` first, and fold the workspace's standing writing rules into the spec's constraints. If it is unclear which project this belongs to, or whether it is a new project, ask before filing. If the spec file already exists, show the user a one-line summary of what's there and confirm before overwriting. Update the project's `memory.md` after saving.

The spec must include these sections:

```markdown
# Writing Spec: <working title>

## Objective
What the piece is, who it's for, and what it must accomplish. One or two paragraphs.

## Requirements
The exact requirements, as a numbered list. Each requirement must be specific
and verifiable — "covers X", "argues Y", "is between N and M words",
"written in <tone> for <audience>". Include structure, content, tone, length,
and venue requirements.

## Constraints
Hard limits and things to avoid: deadline, word counts, style rules,
forbidden topics or framings, format requirements.

## Edge Cases
Tricky situations the piece must handle and how to handle each one —
e.g., conflicting audience needs, controversial points and how to frame them,
prerequisite knowledge the reader may lack, terms that need defining,
claims that need sourcing.

## Definition of Done
A concrete checklist someone could check the finished draft against,
item by item, without asking the author anything. Every item must be
objectively verifiable (e.g., "[ ] Word count is 1,200–1,800",
"[ ] Includes at least two real-world examples, one of which is X").
```

Every section must be filled with specifics from the interview — no placeholders, no "TBD". If you can't fill a section, you haven't finished the interview; go back and ask.

After saving, tell the user where the spec is and summarize it in a few sentences. Do not begin writing the piece itself unless the user explicitly asks.
