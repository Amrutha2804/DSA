# DSA

Daily data structures and algorithms practice. Problems are organized by topic, not by source platform.

## Structure

```
arrays/
strings/
hashing/
two-pointers/
sliding-window/
stacks-queues/
linked-lists/
binary-search/
recursion-backtracking/
trees/
heaps/
graphs/
dynamic-programming/
greedy/
bit-manipulation/
math/
templates/
```

Each file is a single problem, named as `source-id-slug.py` (e.g. `lc-217-contains-duplicate.py`, `cf-1352a-groups.py`).

## File format

```python
"""
Problem name
Source: <link>
Topic: <topic>
Time: O(?) | Space: O(?)
"""
class Solution:
    def method(self, ...):
        ...

if __name__ == "__main__":
    assert ... 
```

## Progress

Tracked in `progress.md`: date, problem, topic, source, difficulty, whether it was solved independently or after seeing a hint/solution.

## Commit format

```
[Day N] Problem name (source id) — Topic
```

## Running tests

```
pytest
```

<!---LeetCode Topics Start-->
# LeetCode Topics
## Array
|  |
| ------- |
| [0128-longest-consecutive-sequence](https://github.com/Amrutha2804/DSA/tree/master/0128-longest-consecutive-sequence) |
| [0130-surrounded-regions](https://github.com/Amrutha2804/DSA/tree/master/0130-surrounded-regions) |
| [1288-remove-covered-intervals](https://github.com/Amrutha2804/DSA/tree/master/1288-remove-covered-intervals) |
| [1301-number-of-paths-with-max-score](https://github.com/Amrutha2804/DSA/tree/master/1301-number-of-paths-with-max-score) |
| [1331-rank-transform-of-an-array](https://github.com/Amrutha2804/DSA/tree/master/1331-rank-transform-of-an-array) |
| [3286-find-a-safe-walk-through-a-grid](https://github.com/Amrutha2804/DSA/tree/master/3286-find-a-safe-walk-through-a-grid) |
| [3336-find-the-number-of-subsequences-with-equal-gcd](https://github.com/Amrutha2804/DSA/tree/master/3336-find-the-number-of-subsequences-with-equal-gcd) |
| [3532-path-existence-queries-in-a-graph-i](https://github.com/Amrutha2804/DSA/tree/master/3532-path-existence-queries-in-a-graph-i) |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/Amrutha2804/DSA/tree/master/3534-path-existence-queries-in-a-graph-ii) |
| [3620-network-recovery-pathways](https://github.com/Amrutha2804/DSA/tree/master/3620-network-recovery-pathways) |
| [3867-sum-of-gcd-of-formed-pairs](https://github.com/Amrutha2804/DSA/tree/master/3867-sum-of-gcd-of-formed-pairs) |
## Breadth-First Search
|  |
| ------- |
| [0130-surrounded-regions](https://github.com/Amrutha2804/DSA/tree/master/0130-surrounded-regions) |
| [0133-clone-graph](https://github.com/Amrutha2804/DSA/tree/master/0133-clone-graph) |
| [2492-minimum-score-of-a-path-between-two-cities](https://github.com/Amrutha2804/DSA/tree/master/2492-minimum-score-of-a-path-between-two-cities) |
| [2685-count-the-number-of-complete-components](https://github.com/Amrutha2804/DSA/tree/master/2685-count-the-number-of-complete-components) |
| [3286-find-a-safe-walk-through-a-grid](https://github.com/Amrutha2804/DSA/tree/master/3286-find-a-safe-walk-through-a-grid) |
## Graph Theory
|  |
| ------- |
| [0133-clone-graph](https://github.com/Amrutha2804/DSA/tree/master/0133-clone-graph) |
| [2492-minimum-score-of-a-path-between-two-cities](https://github.com/Amrutha2804/DSA/tree/master/2492-minimum-score-of-a-path-between-two-cities) |
| [2685-count-the-number-of-complete-components](https://github.com/Amrutha2804/DSA/tree/master/2685-count-the-number-of-complete-components) |
| [3286-find-a-safe-walk-through-a-grid](https://github.com/Amrutha2804/DSA/tree/master/3286-find-a-safe-walk-through-a-grid) |
| [3532-path-existence-queries-in-a-graph-i](https://github.com/Amrutha2804/DSA/tree/master/3532-path-existence-queries-in-a-graph-i) |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/Amrutha2804/DSA/tree/master/3534-path-existence-queries-in-a-graph-ii) |
| [3620-network-recovery-pathways](https://github.com/Amrutha2804/DSA/tree/master/3620-network-recovery-pathways) |
## Heap (Priority Queue)
|  |
| ------- |
| [3286-find-a-safe-walk-through-a-grid](https://github.com/Amrutha2804/DSA/tree/master/3286-find-a-safe-walk-through-a-grid) |
| [3620-network-recovery-pathways](https://github.com/Amrutha2804/DSA/tree/master/3620-network-recovery-pathways) |
## Matrix
|  |
| ------- |
| [0130-surrounded-regions](https://github.com/Amrutha2804/DSA/tree/master/0130-surrounded-regions) |
| [1301-number-of-paths-with-max-score](https://github.com/Amrutha2804/DSA/tree/master/1301-number-of-paths-with-max-score) |
| [3286-find-a-safe-walk-through-a-grid](https://github.com/Amrutha2804/DSA/tree/master/3286-find-a-safe-walk-through-a-grid) |
## Shortest Path
|  |
| ------- |
| [3286-find-a-safe-walk-through-a-grid](https://github.com/Amrutha2804/DSA/tree/master/3286-find-a-safe-walk-through-a-grid) |
| [3620-network-recovery-pathways](https://github.com/Amrutha2804/DSA/tree/master/3620-network-recovery-pathways) |
## Depth-First Search
|  |
| ------- |
| [0129-sum-root-to-leaf-numbers](https://github.com/Amrutha2804/DSA/tree/master/0129-sum-root-to-leaf-numbers) |
| [0130-surrounded-regions](https://github.com/Amrutha2804/DSA/tree/master/0130-surrounded-regions) |
| [0133-clone-graph](https://github.com/Amrutha2804/DSA/tree/master/0133-clone-graph) |
| [2492-minimum-score-of-a-path-between-two-cities](https://github.com/Amrutha2804/DSA/tree/master/2492-minimum-score-of-a-path-between-two-cities) |
| [2685-count-the-number-of-complete-components](https://github.com/Amrutha2804/DSA/tree/master/2685-count-the-number-of-complete-components) |
## Union-Find
|  |
| ------- |
| [0128-longest-consecutive-sequence](https://github.com/Amrutha2804/DSA/tree/master/0128-longest-consecutive-sequence) |
| [0130-surrounded-regions](https://github.com/Amrutha2804/DSA/tree/master/0130-surrounded-regions) |
| [2492-minimum-score-of-a-path-between-two-cities](https://github.com/Amrutha2804/DSA/tree/master/2492-minimum-score-of-a-path-between-two-cities) |
| [2685-count-the-number-of-complete-components](https://github.com/Amrutha2804/DSA/tree/master/2685-count-the-number-of-complete-components) |
| [3532-path-existence-queries-in-a-graph-i](https://github.com/Amrutha2804/DSA/tree/master/3532-path-existence-queries-in-a-graph-i) |
## Binary Search
|  |
| ------- |
| [3532-path-existence-queries-in-a-graph-i](https://github.com/Amrutha2804/DSA/tree/master/3532-path-existence-queries-in-a-graph-i) |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/Amrutha2804/DSA/tree/master/3534-path-existence-queries-in-a-graph-ii) |
| [3620-network-recovery-pathways](https://github.com/Amrutha2804/DSA/tree/master/3620-network-recovery-pathways) |
## Dynamic Programming
|  |
| ------- |
| [0131-palindrome-partitioning](https://github.com/Amrutha2804/DSA/tree/master/0131-palindrome-partitioning) |
| [0132-palindrome-partitioning-ii](https://github.com/Amrutha2804/DSA/tree/master/0132-palindrome-partitioning-ii) |
| [1301-number-of-paths-with-max-score](https://github.com/Amrutha2804/DSA/tree/master/1301-number-of-paths-with-max-score) |
| [3336-find-the-number-of-subsequences-with-equal-gcd](https://github.com/Amrutha2804/DSA/tree/master/3336-find-the-number-of-subsequences-with-equal-gcd) |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/Amrutha2804/DSA/tree/master/3534-path-existence-queries-in-a-graph-ii) |
| [3620-network-recovery-pathways](https://github.com/Amrutha2804/DSA/tree/master/3620-network-recovery-pathways) |
## Topological Sort
|  |
| ------- |
| [3620-network-recovery-pathways](https://github.com/Amrutha2804/DSA/tree/master/3620-network-recovery-pathways) |
## Sorting
|  |
| ------- |
| [1288-remove-covered-intervals](https://github.com/Amrutha2804/DSA/tree/master/1288-remove-covered-intervals) |
| [1331-rank-transform-of-an-array](https://github.com/Amrutha2804/DSA/tree/master/1331-rank-transform-of-an-array) |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/Amrutha2804/DSA/tree/master/3534-path-existence-queries-in-a-graph-ii) |
| [3867-sum-of-gcd-of-formed-pairs](https://github.com/Amrutha2804/DSA/tree/master/3867-sum-of-gcd-of-formed-pairs) |
## Math
|  |
| ------- |
| [3336-find-the-number-of-subsequences-with-equal-gcd](https://github.com/Amrutha2804/DSA/tree/master/3336-find-the-number-of-subsequences-with-equal-gcd) |
| [3658-gcd-of-odd-and-even-sums](https://github.com/Amrutha2804/DSA/tree/master/3658-gcd-of-odd-and-even-sums) |
| [3754-concatenate-non-zero-digits-and-multiply-by-sum-i](https://github.com/Amrutha2804/DSA/tree/master/3754-concatenate-non-zero-digits-and-multiply-by-sum-i) |
| [3756-concatenate-non-zero-digits-and-multiply-by-sum-ii](https://github.com/Amrutha2804/DSA/tree/master/3756-concatenate-non-zero-digits-and-multiply-by-sum-ii) |
| [3867-sum-of-gcd-of-formed-pairs](https://github.com/Amrutha2804/DSA/tree/master/3867-sum-of-gcd-of-formed-pairs) |
## String
|  |
| ------- |
| [0131-palindrome-partitioning](https://github.com/Amrutha2804/DSA/tree/master/0131-palindrome-partitioning) |
| [0132-palindrome-partitioning-ii](https://github.com/Amrutha2804/DSA/tree/master/0132-palindrome-partitioning-ii) |
| [3756-concatenate-non-zero-digits-and-multiply-by-sum-ii](https://github.com/Amrutha2804/DSA/tree/master/3756-concatenate-non-zero-digits-and-multiply-by-sum-ii) |
## Prefix Sum
|  |
| ------- |
| [3756-concatenate-non-zero-digits-and-multiply-by-sum-ii](https://github.com/Amrutha2804/DSA/tree/master/3756-concatenate-non-zero-digits-and-multiply-by-sum-ii) |
## Hash Table
|  |
| ------- |
| [0128-longest-consecutive-sequence](https://github.com/Amrutha2804/DSA/tree/master/0128-longest-consecutive-sequence) |
| [0133-clone-graph](https://github.com/Amrutha2804/DSA/tree/master/0133-clone-graph) |
| [1331-rank-transform-of-an-array](https://github.com/Amrutha2804/DSA/tree/master/1331-rank-transform-of-an-array) |
| [3532-path-existence-queries-in-a-graph-i](https://github.com/Amrutha2804/DSA/tree/master/3532-path-existence-queries-in-a-graph-i) |
## Tree
|  |
| ------- |
| [0129-sum-root-to-leaf-numbers](https://github.com/Amrutha2804/DSA/tree/master/0129-sum-root-to-leaf-numbers) |
## Binary Tree
|  |
| ------- |
| [0129-sum-root-to-leaf-numbers](https://github.com/Amrutha2804/DSA/tree/master/0129-sum-root-to-leaf-numbers) |
## Backtracking
|  |
| ------- |
| [0131-palindrome-partitioning](https://github.com/Amrutha2804/DSA/tree/master/0131-palindrome-partitioning) |
## Two Pointers
|  |
| ------- |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/Amrutha2804/DSA/tree/master/3534-path-existence-queries-in-a-graph-ii) |
| [3867-sum-of-gcd-of-formed-pairs](https://github.com/Amrutha2804/DSA/tree/master/3867-sum-of-gcd-of-formed-pairs) |
## Greedy
|  |
| ------- |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/Amrutha2804/DSA/tree/master/3534-path-existence-queries-in-a-graph-ii) |
## Bit Manipulation
|  |
| ------- |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/Amrutha2804/DSA/tree/master/3534-path-existence-queries-in-a-graph-ii) |
## Enumeration
|  |
| ------- |
| [1291-sequential-digits](https://github.com/Amrutha2804/DSA/tree/master/1291-sequential-digits) |
## Number Theory
|  |
| ------- |
| [3336-find-the-number-of-subsequences-with-equal-gcd](https://github.com/Amrutha2804/DSA/tree/master/3336-find-the-number-of-subsequences-with-equal-gcd) |
| [3658-gcd-of-odd-and-even-sums](https://github.com/Amrutha2804/DSA/tree/master/3658-gcd-of-odd-and-even-sums) |
| [3867-sum-of-gcd-of-formed-pairs](https://github.com/Amrutha2804/DSA/tree/master/3867-sum-of-gcd-of-formed-pairs) |
## Simulation
|  |
| ------- |
| [3867-sum-of-gcd-of-formed-pairs](https://github.com/Amrutha2804/DSA/tree/master/3867-sum-of-gcd-of-formed-pairs) |
<!---LeetCode Topics End-->