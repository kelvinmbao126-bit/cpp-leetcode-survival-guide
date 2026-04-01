# cpp-leetcode-survival-guide
Notes and examples of common C++ mistakes, STL usage, and performance optimizations discovered while practicing data structures and algorithms.

# C++ Competitive Programming Survival Guide

A collection of common C++ mistakes, performance traps, and useful templates
encountered while solving problems on platforms like LeetCode.

This repository is designed as a quick reference for:

- Vector pitfalls
- Performance optimizations
- Common runtime errors
- Competitive programming templates

---

## Topics Covered

### Vectors
- Vector size vs capacity
- reserve() vs resize()
- push_back() usage
- iterator invalidation

### Performance
- Pass by value vs reference
- Fast input/output
- endl vs "\n"

### Common Bugs
- Integer overflow
- Index out of bounds
- Modifying containers during iteration

---

## Competitive Programming Template

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    ios::sync_with_stdio(false);
    cin.tie(nullptr);

    // solution code here

    return 0;
}
