---
name: minto-pyramid
description: "Structure any business communication (emails, Slack, reports, presentations, slides) using the Minto Pyramid Principle: conclusion first, then key arguments, then supporting details. TRIGGER when the user says any of: 'aplica la pirámide', 'aplica la pirámide de minto', 'estructura esto con minto', 'poné la conclusión primero', 'arrancá con el bottom line', 'dale forma de pirámide', 'aplica BLUF', 'usa minto', 'pirámide de minto', 'estructura minto', 'conclusión primero', 'apply the minto pyramid', 'apply the pyramid principle', 'use BLUF', 'bottom line up front', 'lead with the conclusion'. Also trigger when the user wants to make a message, email, report, or presentation clearer, more concise, or better structured — even without naming Minto: 'hacé este email más claro', 'estructurá este reporte', 'organizá esta presentación', 'poné lo importante primero', 'make this clearer', 'structure this better', 'put the key point first'. Works for written communication and slide decks."
license: MIT
metadata:
  version: 1.1.0
  propagation_policy: replace_unmanaged
  tags:
    - audience:all
---

# Minto Pyramid Principle

> Lead with the conclusion. Support it with key arguments. Back those with detailed evidence.

People are busy. They don't have time to read long walls of text or sit through presentations where the key message comes at the very end. The Minto Pyramid fixes this by giving your communication a top-down structure: the most important information goes first, and detail is optional — consumed only if the audience chooses to.

This skill applies the Minto Pyramid to two formats:

1. **Written communication** — emails, Slack messages, reports, memos
2. **Presentations** — slide decks, pitches, executive summaries

---

## When to Use

- Writing or restructuring an email, Slack message, memo, or report
- Building a slide deck or presentation
- The user says "make this clearer", "make it more concise", "structure this better"
- The user mentions Minto, BLUF, pyramid principle, or conclusion-first communication
- Drafting executive summaries or recommendations
- Communicating findings, results, or proposals to busy stakeholders

## When NOT to Use

- Creative writing, storytelling, or narrative fiction (those need suspense, not BLUF)
- Casual personal messages with no business purpose
- Technical documentation that must follow a sequential or reference structure

---

## The Three Levels

### Level 1 — Conclusion (the apex)

The single most important thing your audience needs to know. This is your main takeaway, recommendation, decision, or answer.

- Write it as a clear, direct statement — not a question, not a teaser
- One sentence is ideal; two at most
- This is also called **BLUF** — "Bottom Line Up Front." It originated in the military and is now standard in business communication
- If the reader stops here, they already have what matters most

### Level 2 — Key Arguments (the middle)

Three to five short points that explain *why* the conclusion is correct. These are the pillars that hold up your conclusion.

- Each point should be a concise summary — one or two sentences
- Use a parallel structure (e.g., bullet points with the same grammatical pattern)
- Arguments should be **MECE** — Mutually Exclusive, Collectively Exhaustive. That means: no overlap between arguments, and together they fully cover the reasoning behind the conclusion
- This level answers "why should I believe the conclusion?"

### Level 3 — Supporting Details (the base)

Facts, evidence, numbers, results, and data that make each key argument credible. This is the detail section.

- Group details under the argument they support, not in a separate appendix
- Include specific numbers, dates, names, and sources
- The busier people are, the more likely they skip this part — and that's fine. The structure ensures they already got the conclusion and arguments above
- Sometimes you can skip this level entirely if your key arguments are self-evident and your audience trusts them

---

## Format 1: Written Communication (Emails, Messages, Reports)

### Structure

```
[Subject/Title — if applicable]

[CONCLUSION — 1-2 sentences, the main takeaway or recommendation]

[KEY ARGUMENTS — 3-5 bullet points, each explaining why the conclusion holds]

[SUPPORTING DETAILS — data, evidence, numbers under each argument]

[Optional: closing line — next steps, call to action, or invitation for questions]
```

### Example: Research Findings Email

```
Subject: Product research results — recommendation

Hi team,

We just finished our strategic product research study. Our recommendation:
shift the focus of our product efforts to the buyer persona.

Our main findings:
• Buyers are underserved with the current product. They're missing
  better visibility into product usage.
• Users are pretty happy with the current feature set and usability is good.
• Internally, sales struggles in bigger deals because of product gaps
  for buyers.

How did we arrive at this?
• We talked to 10 buyers and 20 users from our customer base, and 4 buyers
  and 12 users from our churned customers.
• NPS among buyers is significantly lower than among users (5.4 vs 7.9).
• Buyers most commonly indicated lack of usage reporting as the reason
  they're considering churning or already churned.
• Users' SUS score was pretty high; no major usability problems found.

Feel free to read the full report and ask questions!
```

### Why this works

- The reader knows the recommendation before the first paragraph ends
- The three bullet points explain the "why" in under 10 seconds
- The detail section is there for anyone who wants to dig deeper, but isn't required to understand the message
- The closing line is a light call to action, not a buried lede

---

## Format 2: Presentations and Slide Decks

The Minto Pyramid maps naturally to a slide deck structure. The pyramid becomes a stack of slides:

### Slide Structure

```
SLIDE 1: INTRODUCTION — KEY MESSAGE
  Situation > Complication > Question > Answer (SCQA)

SLIDES 2, 6, 10: SUPPORTING ARGUMENTS
  One slide per key argument (3 arguments = 3 slides, spaced out)

SLIDES 3-5, 7-9, 11-13: SUPPORTING DATA
  Up to 3 data slides under each argument

FINAL SLIDE: CONCLUSION
  Restate the key message and call to action
```

### The SCQA Framework (for Slide 1)

The introduction slide uses **SCQA** to set context before delivering the answer:

| Element | What it is | Example |
|---------|-----------|--------|
| **S**ituation | The current state — what the audience already knows and accepts | "We've been selling to users for 3 years." |
| **C**omplication | What changed or what problem arose | "But buyer NPS is dropping and churn is rising." |
| **Q**uestion | The natural question the complication raises | "Should we shift focus to buyers?" |
| **A**nswer | Your conclusion / recommendation | "Yes — shift product focus to the buyer persona." |

The Answer in SCQA is the same as the Conclusion in the pyramid — it's the key message on Slide 1.

### Why MECE matters for slides

Each supporting argument slide should be **Mutually Exclusive** (no overlap with other arguments) and **Collectively Exhaustive** (together they cover everything needed to justify the conclusion). If arguments overlap, the audience gets confused about which point supports what. If they're not exhaustive, the conclusion feels unsupported.

---

## How to Apply This Skill

### When the user gives you content to restructure

1. **Identify the conclusion** — What is the single most important thing the audience needs to know? Extract or craft it as a clear, direct statement.
2. **Extract key arguments** — What are the 3-5 main reasons that support the conclusion? Make them MECE.
3. **Organize the details** — Group remaining facts, data, and evidence under the argument each one supports.
4. **Rewrite in pyramid order** — Conclusion first, arguments next, details last.
5. **Review for clarity** — Can someone who reads only the conclusion understand the message? Can someone who reads conclusion + arguments understand the reasoning? If yes, the structure works.

### When the user asks you to draft something new

1. **Ask what the main message is** — or help them figure it out
2. **Ask for the key reasons** — or help them brainstorm 3-5 MECE points
3. **Ask for supporting evidence** — or help them identify what data they have
4. **Draft in pyramid order** — Conclusion → Arguments → Details
5. **Keep it tight** — Shorter is better at the top; detail can expand at the base

### When the user wants a presentation

1. **Define the key message** — this goes on Slide 1, framed as SCQA
2. **Define 3 key arguments** — each gets its own slide
3. **Identify supporting data** — up to 3 data slides per argument
4. **End with a conclusion slide** — restate the key message and the call to action
5. **Map slide numbers** — use the slide structure above as a template

---

## Common Mistakes to Avoid

- **Burying the lede** — starting with background or context instead of the conclusion. Context belongs in the SCQA framing of Slide 1, not before the conclusion in written communication.
- **Too many arguments** — if you have more than 5, group them into 3 themes. The audience can't hold more than 3-5 points in working memory.
- **Non-MECE arguments** — if two arguments overlap, merge them. If they don't cover the full reasoning, add the missing piece.
- **Details without a home** — every piece of data should sit under a specific argument, not in a general "other information" section.
- **Teaser conclusions** — "We have an important recommendation" is not a conclusion. "Shift focus to the buyer persona" is.
- **Skipping the conclusion on the last slide** — presentations should end by restating the key message, not just showing data. The audience should leave with the conclusion top of mind.

---

## Quick Reference

```
PYRAMID LEVEL     WRITTEN COMM         PRESENTATION
─────────────     ─────────────        ──────────────
Apex (1)          First sentence       Slide 1 (SCQA + Answer)
Middle (2-5)      Bullet points        Slides 2, 6, 10
Base (detail)     Data under each      Slides 3-5, 7-9, 11-13
Close             Optional CTA         Final slide (Conclusion)
```

**Remember**: Conclusion → Arguments → Details. Every time. Every format.
