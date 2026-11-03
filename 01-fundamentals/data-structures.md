# Data structures — selection guide

Choose a data structure based on the operations the problem needs, not because a pattern name sounds familiar.

| Structure | Useful operations / properties | Typical uses |
|---|---|---|
| Array / vector | O(1) indexed access; insertion in middle is costly | Sequences, sorting, two pointers |
| String | Sequence of characters; representation and encoding matter | Parsing, matching, windows |
| Hash map | Average O(1) lookup/insert in common implementations | Frequencies, lookup, grouping |
| Hash set | Average O(1) membership checks | Deduplication, visited tracking |
| Linked list | Local insertion/deletion when node is known; no O(1) indexing | Pointer manipulation |
| Stack | Last in, first out | Matching brackets, monotonic stack, DFS |
| Queue / deque | First in, first out / operations at both ends | BFS, sliding windows |
| Heap / priority queue | Efficient access to min or max | Top-K, scheduling, shortest paths |
| Tree | Hierarchical relationships | Search trees, recursion, traversal |
| Trie | Prefix-oriented lookup | Dictionaries, prefix search |
| Graph | Vertices and edges | Networks, dependencies, paths |
| Disjoint Set Union | Efficient connectivity grouping | Connected components, Kruskal |

## Before choosing

Ask:
- Which operations dominate?
- Is order important?
- Do I need fast membership checks?
- Are duplicates meaningful?
- Is the data hierarchical or network-shaped?
- Do I need the minimum/maximum repeatedly?
- What are the memory constraints?

Complexities depend on the implementation and assumptions. Verify the relevant language/library guarantees.
