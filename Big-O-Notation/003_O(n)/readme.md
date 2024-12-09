# O(n) : Analysis of time and space complexity  ✏️
Analyzing time complexity involves determining how the running time of an algorithm changes with respect to the size of the input.

### Item : 1
```c
for (int i = 0; i < n; i++) {		// n times
    stmt;
}
```
**Explanation:**

- Iteration : increments linearly (`i++` )

T(n) = n = O(n)

---

### Item : 2
```c
for (int i = 0; i < n; i = i + 2) {		// n/2 times
    stmt;
}
```
**Explanation:**

- Iteration : increments by 2 each time (`i = i + 2` )

T(n) = n/2 = O(n)

