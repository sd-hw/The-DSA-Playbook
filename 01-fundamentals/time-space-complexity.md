# Time and space complexity

Complexity describes how resource usage grows as input size grows. It is not a stopwatch measurement for one machine.

## Common growth rates

| Complexity | Typical intuition | Example |
|---|---|---|
| O(1) | Constant | Array access by index |
| O(log n) | Repeatedly reduce search space | Binary search |
| O(n) | Visit each item a constant number of times | Linear scan |
| O(n log n) | Divide and combine / comparison sorting | Merge sort |
| O(n²) | Compare many pairs | Nested loops over the same input |
| O(2ⁿ) | Explore subsets / branching choices | Basic subset enumeration |
| O(n!) | Explore permutations | Brute-force permutation search |

## Rules of thumb

- Drop constant factors when describing asymptotic growth: O(3n) becomes O(n).
- Keep the dominant term: O(n² + n) becomes O(n²).
- Sequential sections add; nested loops often multiply, but inspect their actual bounds.
- A loop that halves a value is often logarithmic.
- Two nested loops are not automatically O(n²): their combined iteration count matters.
- Recursion uses call-stack space. State it when relevant.
- Distinguish auxiliary space from memory used for the returned output.

## Amortised complexity

An operation may occasionally be expensive but cheap on average across a sequence of operations. Dynamic-array append is a common example: an individual resize can cost O(n), while append is amortised O(1).

## Complexity checklist

For every solution, answer:
1. What is n (and are there other input dimensions)?
2. How many times can each loop or recursive branch run?
3. What operations are performed inside it?
4. What data structures are used, and what are their operation costs?
5. What extra memory grows with the input?
6. Is the stated complexity worst-case, average-case or amortised?
