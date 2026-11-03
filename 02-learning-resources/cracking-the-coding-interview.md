# How to use *Cracking the Coding Interview* (CTCI)

**Role in this playbook:** a fundamentals, interview-reasoning and classic-problem resource — not the only DSA roadmap you need.

The author's official site describes the sixth edition as containing 189 programming questions and solutions, hints, walkthroughs of solution derivation, core computer-science coverage and five strategies for approaching algorithm questions.

## Official and supplementary links

- [Author's official CTCI website](https://www.crackingthecodinginterview.com/)
- [Official table of contents](https://www.crackingthecodinginterview.com/contents.html)
- [Independent CTCI-to-LeetCode mapping on HashTo](https://hashto.net/book/cracking-the-coding-interview) — third-party resource, not an official CTCI site. Check each mapping and current availability.

This repository intentionally does not mirror or link to an unauthorised PDF copy. Obtain the book from an authorised seller, a library or another legitimate source. The official site and book copyright notice should be treated as authoritative for permissions.

## The correct way to work through a CTCI question

### Phase A — Learn the topic

1. Read the chapter's introductory explanation.
2. Write a short summary in your own words.
3. Identify the data structure or algorithm, its operations and its trade-offs.
4. Work through the book's examples before attempting the practice question.

### Phase B — Attempt before reading

1. Read the question carefully and restate it.
2. Identify constraints and edge cases.
3. Work through at least one example manually.
4. Propose a brute-force approach.
5. Try to improve it and explain why the improvement is valid.
6. Set a reasonable timebox. If stuck, use a hint rather than immediately opening the full solution.

### Phase C — Study the explanation

When you consult the book's hint or solution, ask:

- What observation did I miss?
- Which part of the explanation changes the problem?
- Why is this data structure appropriate?
- What invariant makes the algorithm correct?
- What are the time and space costs?
- Are there alternative approaches or trade-offs?

Do not treat reading a solution as equivalent to solving the problem.

### Phase D — Re-derive and implement

1. Close the explanation.
2. Explain the approach aloud or in writing.
3. Implement it in your interview language (for this playbook, C++ examples are encouraged).
4. Test edge cases.
5. Compare your implementation with the reasoning, not just the final code.

### Phase E — Revisit

Record the question in the [tracker](../03-practice-tracker/dsa-tracker.csv). Reattempt it after a delay without looking at the solution. If you cannot derive it, return it to an earlier revision interval.

## How CTCI fits with NeetCode 150

A useful division of labour:

| Resource | Primary role |
|---|---|
| CTCI | Conceptual foundations, classic questions, interview problem-solving process and worked explanations |
| NeetCode 150 | Structured, pattern-oriented practice across a broad set of interview topics |
| LeetCode | Additional practice, variations and timed implementation |
| AI tutor prompts | Socratic hints, reasoning checks, code review and revision |

**Recommended approach:** use CTCI and NeetCode in parallel. For a topic, learn the foundations, attempt selected CTCI exercises, then solve relevant NeetCode problems to practise applying the concept in different forms. You do not have to finish all CTCI questions before beginning NeetCode.

## What about the claim that CTCI is outdated?

The sixth edition was published in 2015. Some examples, coverage and interview context may not reflect every current interview loop. That does not make foundational explanations useless. Use it selectively for concepts and reasoning, and supplement it with current practice lists and newer problem patterns.

Do not use CTCI as your sole source for current interview preparation, system design, language/library details or company-specific hiring expectations.

## A sample topic workflow

For arrays and strings:

1. Review the chapter's explanation and relevant techniques.
2. Attempt a selected CTCI question without looking at the answer.
3. Study the hint and solution derivation if needed.
4. Re-implement independently.
5. Solve related NeetCode / LeetCode questions involving arrays, hashing, two pointers or sliding windows.
6. Revisit the original question after 1, 3, 7 and 14 days, adjusting based on performance.

The goal is transfer: being able to recognise and derive a technique in a problem you have never seen before.
