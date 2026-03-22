# find-middle-element-linked-list
# 🔗 Find Middle Element of Linked List

## 📌 Problem Statement

Given the head of a singly linked list, find the value of the middle node.

If the list has an even number of nodes, return the **second middle element**.

---

## 💡 Approach: Slow & Fast Pointer

* Use two pointers:

  * `slow` moves one step
  * `fast` moves two steps
* When `fast` reaches the end, `slow` will be at the middle.

---

## 🧠 Example

### Input

```
1 → 2 → 3 → 4 → 5
```

### Output

```
3
```

---

### Input

```
1 → 2 → 3 → 4 → 5 → 6
```

### Output

```
4
```

---

## ⏱ Complexity

* **Time Complexity:** O(N)
* **Space Complexity:** O(1)

---

## 🚀 How to Run

1. Clone the repository
2. Compile:

   ```
   g++ middle_element.cpp -o output
   ```
3. Run:

   ```
   ./output
   ```

---

## 📚 Topics

* Linked List
* Two Pointers
