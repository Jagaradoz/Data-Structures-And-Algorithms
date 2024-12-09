# O(1) : Analysis of time and space complexity  ✏️
Analyzing time complexity involves determining how the running time of an algorithm changes with respect to the size of the input.

### Item : 1

```c++
int a = 5;          	// 1 operator
int b = 10;         	// 1 operator
int result = a + b; 	// 1 operator
```
**Explanation :**
-  Initialization: **3** operators. (`a`, `b`, and `result`)
-  Space Complexity: **3** operators. (`a`, `b`, and `result`)

T(n) = 1 + 1 + 1 = O(1)<br/>
S(n) = 1 + 1 + 1 = O(1)

---

### Item : 2

```c++
int[] arr = new int[5];		// 1 operator
int count = arr[0];		// 1 operator
```
**Explanation :**
-   Initialization: **2** operators. (`arr` and `count`)
-  Space Complexity: **2** operators. (`arr` and `count`)

T(n) = 1 + 1 = O(1)<br/>
S(n) = 1 + 1 = O(1)