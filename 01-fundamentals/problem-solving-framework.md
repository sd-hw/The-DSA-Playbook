# A repeatable problem-solving framework

When you see an unfamiliar problem, resist the urge to guess a pattern immediately.

## 1. Understand the problem

- Restate the task in your own words.
- Identify inputs, outputs and constraints.
- Clarify whether duplicates, negative values, empty inputs or invalid inputs are possible.
- Identify what must be returned and whether mutation is allowed.

## 2. Build examples

Create:
- A normal example.
- A smallest valid example.
- An edge case.
- A case that might break your first intuition.

Walk through each example manually.

## 3. Start with a correct brute-force idea

A brute-force approach gives you a baseline. State:
- What are you enumerating?
- Why does it cover all valid answers?
- What is its time and space complexity?

Do not optimise before you understand what the simple solution is doing.

## 4. Identify the bottleneck

Ask:
- Are repeated computations happening?
- Am I repeatedly searching for an element?
- Is the input already sorted?
- Do I need a contiguous range, a subsequence or a relationship between nodes?
- Can I store previous work?
- Is there an invariant I can maintain?

## 5. Choose a technique for a reason

Examples:
- Hash map: fast lookup or frequency counting.
- Two pointers: coordinated movement through a sequence.
- Sliding window: a contiguous range with a maintainable condition.
- Prefix sums: repeated range-sum calculations.
- Stack: last-in-first-out structure, nesting or monotonic relationships.
- Binary search: a sorted search space or a monotonic predicate.
- BFS: shortest path in an unweighted graph.
- DFS: reachability, traversal, components or recursive structure.
- Dynamic programming: overlapping subproblems and reusable states.

A pattern name is not a proof. Explain why the technique fits.

## 6. Define the invariant or state

Before coding, explain:
- What does each variable represent?
- What is true before and after each iteration?
- What does each DP state mean?
- What condition makes the algorithm terminate?

## 7. Prove correctness informally

Explain why:
- Every valid answer is considered or represented.
- Invalid answers are excluded.
- The algorithm cannot stop before finding the required result.

## 8. Analyse complexity

Count operations in terms of input size. State auxiliary space separately from output space when useful. Account for recursion depth and data structure costs.

## 9. Implement and test

Test:
- Minimum input.
- Maximum or boundary constraints.
- Duplicates.
- Negative and zero values where relevant.
- Already sorted / reverse sorted inputs.
- No solution / multiple solutions.
- Overflow and index boundaries.

## 10. Reflect and revise

After solving:
- What was the key observation?
- What did you initially miss?
- What other problem could use the same idea?
- Could the approach be improved?
- Can you derive it again tomorrow without looking?

Use the [problem tracker](../03-practice-tracker/dsa-tracker.csv) to record the attempt.
