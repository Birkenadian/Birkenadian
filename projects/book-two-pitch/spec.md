# Writing Spec: Book Two Pitch Document for Dennis at Quarto

## Objective

A pitch document, sent as an email attachment with a short cover email, that gives Dennis at Quarto 4 to 6 developed concepts for Andrew Cashin's second book. Context: Dennis is managing publication of Andrew's first book, *Zen and the Art of Record Collecting* (Quarto, early 2027, foreword by Alan Cross), which treats record collecting as a mindful practice. Andrew asked Dennis for follow-up ideas; Dennis said he would think on it and asked Andrew the same. Andrew wants to get something to Dennis soon, while the exchange is fresh.

The document must stay squarely in Andrew's lane (record collecting, music, hi-fi and listening culture, mindfulness, meditation) and follow every writing rule in the root `CLAUDE.md`. It is a conversation starter for an editor who already knows and works with the author, never a cold formal proposal.

## Requirements

1. Produce two files in this project folder: the pitch document at `projects/book-two-pitch/book2-pitches.md` and the cover email draft at `projects/book-two-pitch/cover-email-dennis.md`.
2. The pitch document contains between 4 and 6 book concepts, inclusive.
3. Every concept stays within the lane: record collecting, music, listening and hi-fi culture, mindfulness, or meditation, or a combination.
4. Each concept includes exactly these four elements, clearly labeled or structurally obvious:
   a. A working title.
   b. A hook of 2 to 4 sentences describing the concept and why a reader would want it.
   c. The target reader, in 1 or 2 sentences.
   d. A bridge: 1 or 2 sentences on how it builds on *Zen and the Art of Record Collecting*.
5. Each concept additionally includes one sentence stating how it stands apart from book one, phrased positively, without contrast framing.
6. Concepts are presented in ranked order, strongest first, and the document opens with a 1 or 2 sentence note explaining why the lead concept leads.
7. Each concept runs 150 to 250 words; the full pitch document runs 900 to 1,600 words including any intro and outro.
8. The pitch document opens with a brief framing paragraph of at most 75 words that carries enough context to stand alone if Dennis forwards it internally at Quarto.
9. Tone matches book one's sensibility: warm, practical, contemplative, conversational, and professional. No hard-sell marketing language.
10. The cover email is at most 150 words, addresses Dennis by first name, references their recent idea exchange, says the ideas are attached, invites his reaction, and contains no proposed dates or deadline commitments.
11. Both files are plain Markdown, with the pitch document formatted cleanly enough to convert directly to an attachment: clear headings, no raw URLs, no code blocks.
12. Both files obey the writing rules in the root `CLAUDE.md` in full, including the banned word list, the ban on em dashes, the ban on contrast framing, and the records terminology rule.

## Constraints

- **Style rules are hard limits.** Zero em dashes. Zero contrast-frame constructions. Zero words from the banned list in `CLAUDE.md`. Records are never called "vinyl" as a noun and the word "vinyls" never appears. Prose carries the argument; bullet lists appear only where the labeled concept structure requires clear scanning.
- **No invented facts.** No sales figures, print runs, statistics, or claims about book one's performance. Permitted facts about book one: its title, publisher (Quarto), publication in early 2027, subject matter, practical and philosophical approach, foreword by Alan Cross, and the existence of endorsements from the people listed in `about-me/claude.md`. Blurbs are quoted exactly or not at all.
- **No fabricated credentials or biography.** Andrew's background comes from `about-me/claude.md` only.
- Do not presume a series or sequel commitment from Quarto; concepts may suggest series potential without assuming it.
- Do not disparage book one, other authors, other books, streaming, or digital music; the lane's spirit is appreciation.
- Mindfulness and meditation content stays secular and accessible, with no religious instruction and no claims of therapeutic or medical benefit.
- No placeholder text, no "TBD", no bracketed gaps in either file.
- The build completes the deliverable in one pass without requesting additional research from the user.

## Edge Cases

- **Overlap with book one.** Every concept must state in one sentence what makes it its own book; any concept that cannot is excluded. The statement must be positive, naming what the book is, with no contrast framing.
- **Unknown commercial performance.** Book one is not yet published, so no concept may justify itself by book one's success; bridges speak to subject and voice.
- **Dennis's surname and title are unknown.** The email addresses him as "Dennis" only.
- **"Zen" framing.** At most one concept may use a "Zen and the Art of..." style title; the rest must show range beyond the formula.
- **Mixed audience for the attachment.** The framing paragraph carries enough context that the document makes sense without the email.
- **Reader knowledge floor.** Any collecting or hi-fi jargon used in a hook must be self-explanatory in context.

## Definition of Done

- [ ] `projects/book-two-pitch/book2-pitches.md` exists and is valid Markdown with clear headings.
- [ ] `projects/book-two-pitch/cover-email-dennis.md` exists.
- [ ] The pitch document contains 4 to 6 concepts (count them).
- [ ] Every concept has all four elements: working title, 2 to 4 sentence hook, 1 to 2 sentence target reader, 1 to 2 sentence bridge to book one.
- [ ] Every concept has a one-sentence statement of how it stands apart from book one, with no contrast framing.
- [ ] Every concept's subject falls within record collecting, music, listening and hi-fi culture, mindfulness, or meditation.
- [ ] At most one concept uses a "Zen and the Art of..." title pattern.
- [ ] Concepts appear in ranked order and the document explains the lead ranking in 1 or 2 sentences.
- [ ] Each concept is 150 to 250 words; the total document is 900 to 1,600 words.
- [ ] The document opens with a framing paragraph of at most 75 words that makes sense without the cover email.
- [ ] The cover email is at most 150 words, opens with "Dennis," references their recent idea exchange, states the pitches are attached, invites a reaction, and contains no dates or deadline commitments.
- [ ] Neither file contains an em dash (—) anywhere.
- [ ] Neither file contains any word or phrase from the banned list in `CLAUDE.md`.
- [ ] Neither file contains a contrast-frame construction (including "not just X, but Y", "rather than", "on the contrary", "it's worth noting", "a testament to", or similar).
- [ ] Neither file uses "vinyl" as a noun for records, and "vinyls" appears nowhere.
- [ ] Neither file contains sales figures, statistics, invented quotes, invented biography, religious instruction, or therapeutic claims, and book one is described as arriving early 2027 from Quarto wherever its status is mentioned.
- [ ] Neither file contains placeholders, "TBD", or bracketed gaps.
- [ ] No disparagement of book one, other books or authors, streaming, or digital music in either file.
