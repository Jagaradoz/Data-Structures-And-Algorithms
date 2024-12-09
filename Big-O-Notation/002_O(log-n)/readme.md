## O(log n) : Analysis of time and space complexity  ✏️
Analyzing time complexity involves determining how the running time of an algorithm changes with respect to the size of the input.


### Item : 1
```c
for (int i = 0; i < n; i = i * 2) {		// log₂(n) times
    stmt;
}
```
**Explanation:**

- Iteration : doubles `i` each time (`i = i * 2`)

T(n) = log₂(n) = O(log n)

---

### Item : 2
```c
for (int i = n; i > 1; i = i / 2) {		// log₂(n) times
    stmt;
}
```
**Explanation:**

- Iteration : divides `i` each time (`i = i / 2`)

T(n) = log₂(n) = O(log n)