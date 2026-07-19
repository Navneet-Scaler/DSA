# Arrays for DSA

Arrays are the most fundamental data structure — contiguous memory, direct indexing, and the foundation almost every other structure and algorithm builds on. This section goes from "what an array actually is in memory" all the way through the pattern library used to solve array problems in interviews and competitive programming: prefix techniques, sliding window, two pointers, monotonic structures, cyclic sort, and more.

Each lesson follows the same three-part structure used throughout these notes:

- **Theory** — the concept explained simply, with rules and edge cases.
- **Code** — a working Java implementation.
- **Example** — sample input, a dry run, and the output.

Most lessons cover a **progression of named problems per subtopic** (basic → advanced) rather than a single demo, and call out Java-specific idioms (`Collections.sort`, lambda `Comparator`s, `Collectors.groupingBy`, `PriorityQueue`, `Set` operations, ...) alongside the raw algorithm.

> **Language used:** Java

---

## Topics

| # | Topic | What you'll learn |
|---|-------|--------------------|
| 01 | [Array Fundamentals](<./01. Array Fundamentals.md>) | Memory layout, indexing, complexities, jagged arrays, Arrays vs ArrayList, primitive vs object arrays |
| 02 | [Basic Operations](<./02. Basic Operations.md>) | Traversal, insertion, deletion, search, copy, swap, rotation, reversal, merge, split, resize |
| 03 | [Java Array APIs](<./03. Java Array APIs.md>) | Arrays.sort/fill/copyOf/copyOfRange/binarySearch/equals/deepEquals/toString/deepToString, System.arraycopy |
| 04 | [Frequency Problems](<./04. Frequency Problems.md>) | Counting frequency, majority element, duplicate detection, missing number, valid/group anagrams, Stream-based counting |
| 05 | [Prefix Techniques](<./05. Prefix Techniques.md>) | Prefix sum/product/XOR/min/max, difference arrays, continuous subarray sum, max size subarray sum equals K |
| 06 | [Suffix Techniques](<./06. Suffix Techniques.md>) | Suffix sum/product/min/max, prefix+suffix combination (product except self, trapping rain water) |
| 07 | [Sliding Window](<./07. Sliding Window.md>) | Fixed/variable windows, longest/shortest window, sliding window max/min, Minimum Window Substring |
| 08 | [Two Pointers](<./08. Two Pointers.md>) | Opposite/same direction, slow-fast, partitioning, pair/triplet/four sum, Container With Most Water, Trapping Rain Water |
| 09 | [Sorting Based Arrays](<./09. Sorting Based Arrays.md>) | The 10 major sorting algorithms, Tim Sort, multi-key sorting, Collections.sort, stability/in-place analysis |
| 10 | [Binary Search on Arrays](<./10. Binary Search on Arrays.md>) | Basic search, lower/upper bound, binary search on answer, rotated array search, Find Peak Element, Median of Two Sorted Arrays |
| 11 | [Hashing](<./11. Hashing.md>) | HashMap/HashSet, index mapping, prefix hashing, Longest Consecutive Sequence, Set operations (retainAll/addAll) |
| 12 | [Greedy Arrays](<./12. Greedy Arrays.md>) | Jump Game, Gas Station, interval scheduling, rearrangement, meeting rooms, Candy Distribution, Partition Labels |
| 13 | [Kadane Family](<./13. Kadane Family.md>) | Max/min subarray, circular maximum, Maximum Product Subarray, Best Time to Buy and Sell Stock |
| 14 | [Matrix (2D Arrays)](<./14. Matrix (2D Arrays).md>) | Traversal patterns, spiral/diagonal order, 2D prefix sum, in-place Rotate Image, Set Matrix Zeroes |
| 15 | [Monotonic Structures](<./15. Monotonic Structures.md>) | Monotonic stack/queue, next/previous greater/smaller, Largest Rectangle in Histogram, Trapping Rain Water (stack) |
| 16 | [Heap + Arrays](<./16. Heap + Arrays.md>) | Top-K, running median, Kth Largest Element, Top K Frequent Elements, K Closest Points to Origin |
| 17 | [Cyclic Sort](<./17. Cyclic Sort.md>) | Missing/duplicate number, First Missing Positive, Corrupt Pair, Find All Duplicates/Missing Numbers |
| 18 | [In-place Manipulation](<./18. In-place Manipulation.md>) | Dutch National Flag, Move Zeroes, Wiggle Sort I/II, arr[i]=arr[arr[i]] index-encoding trick |
| 19 | [Simulation](<./19. Simulation.md>) | Rotate Array (3-reversal), Shift 2D Grid, Next Greater Element II, Game of Life, Robot Simulation |
| 20 | [Mathematical Arrays](<./20. Mathematical Arrays.md>) | Contribution Technique — Sum of All Subarray Sums, Sum of Subarray Minimums |
| 21 | [XOR Arrays](<./21. XOR Arrays.md>) | Single Number I/II/III, Pair XOR counting, Prefix XOR subarray counting |
| 22 | [Bit Manipulation + Arrays](<./22. Bit Manipulation + Arrays.md>) | Bitmask DP (Partition to K Equal Sum Subsets), Maximum XOR of Two Numbers, Bitwise AND of Numbers Range |
| 23 | [Advanced Array Algorithms](<./23. Advanced Array Algorithms.md>) | Merge Intervals, Sweep Line (Car Pooling), Coordinate Compression, Sparse Array idea |
| 24 | [Advanced Optimization](<./24. Advanced Optimization.md>) | Binary Search/Sliding Window/Greedy/Heap + Prefix combos, Monotonic Queue DP, Convex Hull Trick, D&C Optimization |
| 25 | [Array Design Problems](<./25. Array Design Problems.md>) | Insert Delete GetRandom O(1), Shuffle an Array, Random Pick Index, Circular Queue, Circular Buffer |

---

### Navigation

- [Back to main DSA index](../README.md)
- [Maths](../Maths/README.md)
