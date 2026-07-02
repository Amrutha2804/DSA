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
