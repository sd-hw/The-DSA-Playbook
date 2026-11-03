# The DSA Playbook

> **Stop collecting problems. Start understanding them.**

A practical, AI-assisted approach to learning data structures and algorithms through four connected habits:

1. **Build fundamentals** — understand the ideas behind data structures, algorithms and complexity.
2. **Practise deliberately** — use a structured problem set such as NeetCode 150 to apply those ideas.
3. **Use AI as a tutor** — ask for hints, explanations, counterexamples and feedback, not just finished code.
4. **Revise actively** — return to problems after a delay and derive the solution again without looking.

The goal is not merely to clear your next coding interview. It is to become a stronger problem solver and software engineer.

---

## Who this is for

- Students beginning structured DSA preparation.
- Developers who have solved many problems but still struggle with unfamiliar ones.
- Learners who want a repeatable practice and revision system.
- Anyone who wants to use AI without outsourcing the thinking.

You do **not** need to complete every resource in this repository in a fixed order. Treat the roadmap as a guide and adapt it to your current level.

## The recommended learning loop

```text
Understand a concept
       ↓
Attempt a problem independently
       ↓
Use a hint only when needed
       ↓
Explain and implement the solution
       ↓
Study the explanation and alternatives
       ↓
Re-derive it without looking
       ↓
Schedule a later revision
       ↓
Apply the concept to a new problem
```

## Start here

**New: [The DSA Study Map](07-the-dsa-study-map/README.md)** — find exactly where to study each topic across the uploaded CTCI and Reema Thareja editions, then connect it to practice and revision. See the [Book & Reference Library](02-learning-resources/books/README.md) for edition details.


| Step | Resource | What to do |
|---|---|---|
| 1 | [Problem-solving framework](01-fundamentals/problem-solving-framework.md) | Learn a repeatable way to approach unfamiliar questions. |
| 2 | [CTCI: how to use it](02-learning-resources/cracking-the-coding-interview.md) | Use the book as a fundamentals and reasoning resource, not a race to finish 189 questions. |
| 3 | [NeetCode 150](02-learning-resources/neetcode-150.md) | Practise common patterns with a structured roadmap. |
| 4 | [Socratic DSA tutor](04-ai-learning-prompts/socratic-dsa-tutor.md) | Add the prompt to an existing learning chat or start a dedicated one. |
| 5 | [Revision tutor](04-ai-learning-prompts/dsa-revision-tutor.md) | Turn past learning context into active-recall sessions. |
| 6 | [Problem tracker](03-practice-tracker/dsa-tracker.csv) | Record attempts, hints, confidence and next revision dates. |

## The four pillars

### 01 — Fundamentals
Understand why a data structure or algorithm works, what assumptions it relies on, and what trade-offs it introduces. Start with [the fundamentals guide](01-fundamentals/README.md).

### 02 — Structured practice
Use CTCI to strengthen core reasoning and foundational topics. Pair it with a more contemporary pattern-oriented practice roadmap such as [NeetCode 150](02-learning-resources/neetcode-150.md). You can work through them in parallel; CTCI is not a gate you must finish before starting NeetCode.

### 03 — AI-assisted learning
Use the prompts in [04-ai-learning-prompts](04-ai-learning-prompts/) to get hints, challenge your assumptions, review code and simulate interviews. AI output can be wrong: verify explanations, complexity and edge cases yourself.

### 04 — Revision
Solving a problem once is exposure. Re-deriving it later is evidence of retention. Use [the revision system](05-revision-system/README.md), [the tracker](03-practice-tracker/dsa-tracker.csv) and the revision tutor.

## How to use CTCI correctly

A common mistake is to treat *Cracking the Coding Interview* as a checklist of 189 questions to speedrun. A better approach:

1. Read the relevant topic introduction and understand the core concept.
2. Attempt a practice question without opening the solution. Write down assumptions, examples and a brute-force approach first.
3. If stuck, use the book's hint or give yourself a bounded attempt before reading the explanation.
4. Study the explanation to understand how the solution is derived, not just what code is written.
5. Close the book and re-derive the approach in your own words. Implement it in your interview language.
6. Test edge cases and explain time and space complexity.
7. Add the problem to your tracker and revisit it later.
8. Apply the same concept to a different problem in NeetCode 150 or another current practice list.

**Do not force a one-resource-at-a-time sequence.** Use CTCI for foundational explanations and classic practice; use NeetCode 150 / LeetCode to build breadth with modern patterns and problem variations. If a CTCI topic or example feels dated, keep the underlying concept where useful and supplement it with current practice.

## Resource links

- [CTCI official website](https://www.crackingthecodinginterview.com/)
- [CTCI official table of contents](https://www.crackingthecodinginterview.com/contents.html)
- [NeetCode 150 roadmap](https://neetcode.io/roadmap)
- [LeetCode](https://leetcode.com/)
- [HashTo CTCI-to-LeetCode mapping](https://hashto.net/book/cracking-the-coding-interview) — independent third-party mapping; verify each match and availability.
- [GitHub Markdown guide](https://docs.github.com/en/get-started/writing-on-github)

### About the CTCI PDF link sometimes shared online

This repository does not host or mirror a copy of the book. The author/publisher's materials identify the book as copyrighted. Please obtain the book through an authorised source, a library, or another legitimate channel. The resource links here point to the official book site and an independent problem-mapping page rather than redistributing the PDF.

## Suggested weekly rhythm

A sustainable starting point (adjust to your schedule):

- **3–4 focused practice sessions:** concept + problem attempts.
- **2 short revision blocks:** revisit problems due in your tracker.
- **1 reflection block:** review recurring mistakes and choose next week's focus.

Consistency and quality of reasoning matter more than an arbitrary daily problem count.

## Repository map

- `01-fundamentals/` — problem-solving, complexity and core topic notes.
- `02-learning-resources/` — CTCI and NeetCode guidance.
- `03-practice-tracker/` — CSV tracker and revision schedule.
- `04-ai-learning-prompts/` — reusable tutor, revision, interviewer and reviewer prompts.
- `05-revision-system/` — active recall, spaced repetition and revision workflow.
- `06-interview-preparation/` — interview approach and mock interview guide.
- `07-the-dsa-study-map/` — chapter-by-chapter topic routes across the uploaded books.

## Important notes

- This is an independent learning resource, not affiliated with Gayle Laakmann McDowell, CareerCup, NeetCode or LeetCode.
- Book titles, platform names and linked materials belong to their respective owners.
- The repository does not reproduce copyrighted book chapters, questions, solutions or platform problem statements.
- AI-generated explanations can be inaccurate. Cross-check important details and test your code.
- No resource or roadmap guarantees an interview or job outcome.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Suggestions, corrections and improvements are welcome.

## Licence

Original text, templates and prompts in this repository are licensed under [CC BY 4.0](LICENSE). This licence does not apply to third-party material linked from this repository.
