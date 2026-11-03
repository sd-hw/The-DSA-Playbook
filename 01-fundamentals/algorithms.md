# Algorithms and common techniques

This is a compact index of techniques to recognise and understand. It is not a list to memorise blindly.

| Technique | Core idea | Questions to ask |
|---|---|---|
| Sorting | Establish an order to simplify later operations | Does sorted order expose a useful invariant? |
| Binary search | Eliminate part of a monotonic search space | What exactly is monotonic? |
| Two pointers | Move two indices according to a condition | Why is it safe to discard a region? |
| Sliding window | Maintain information about a contiguous range | What condition expands or shrinks the window? |
| Prefix sums | Precompute cumulative aggregates | Can a range be answered from two prefixes? |
| Hashing | Store information for fast lookup | What key represents the information needed? |
| BFS | Explore by distance layers | Is the graph unweighted? |
| DFS | Explore deeply through a graph/tree | What is the recursion/stack state? |
| Backtracking | Explore choices and undo them | What is the choice space and pruning condition? |
| Greedy | Make a locally justified choice | Why can this choice be part of an optimal solution? |
| Dynamic programming | Cache solutions to overlapping subproblems | What is the state, transition and base case? |
| Monotonic stack/queue | Maintain ordered candidates | What elements can be safely removed? |
| Topological sort | Order a directed acyclic graph | What dependency must precede another? |
| Union-Find | Maintain disjoint connected groups | When do components merge? |

## Dynamic programming starter checklist

1. Define the state in one sentence.
2. Identify decisions/transitions.
3. Establish base cases.
4. Determine evaluation order.
5. Derive time and space complexity.
6. Consider memoisation vs tabulation.
7. Optimise space only after the recurrence is correct.

## Greedy starter checklist

A greedy intuition is not enough. Look for an exchange argument, invariant or other correctness justification. Test small counterexamples before trusting the strategy.
