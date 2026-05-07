<div align="center">

# 🚀 DATA STRUCTURE & ALGORITHM LAB MANUAL
### 📘 Complete DSA Notes with C Programs, Algorithms, Diagrams & Viva

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=00C2FF&center=true&vCenter=true&width=1000&lines=Data+Structures+%26+Algorithms;Complete+DSA+Lab+Manual;C+Programming+Examples;Searching+%7C+Sorting+%7C+Trees+%7C+Graphs;GitHub+Ready+README" />

<br>

![DSA](https://img.shields.io/badge/Subject-Data%20Structure-blue?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-C-orange?style=for-the-badge)
![Programs](https://img.shields.io/badge/Programs-Complete-success?style=for-the-badge)
![Algorithms](https://img.shields.io/badge/Algorithms-DSA-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Ready_For_GitHub-brightgreen?style=for-the-badge)
![University](https://img.shields.io/badge/Lab-Manual-purple?style=for-the-badge)

---

# 🌟 PROJECT OVERVIEW

</div>

> 📌 This repository contains a **complete Data Structure & Algorithm Lab Manual** designed for:
>
> - 🎓 University Lab Assignments
> - 💻 C Programming Practice
> - 🧠 DSA Interview Preparation
> - 📚 Semester Final Revision
> - 🔥 GitHub Portfolio Showcase

---

# ✨ FEATURES

<table>
<tr>
<td width="50%">

## ✅ Included Topics

- Array
- Linked List
- Stack
- Queue
- Tree
- Graph
- Searching
- Sorting
- Complexity Analysis

</td>
<td width="50%">

## 🚀 Extra Additions

- C Programs
- ASCII Diagrams
- Viva Questions
- Algorithms
- Notes & Tips
- Time Complexity Tables
- GitHub Styled README
- Clean Documentation

</td>
</tr>
</table>

---

# 📑 CLICKABLE TABLE OF CONTENTS

| 📌 Topic | 🔗 Link |
|---|---|
| 📖 Introduction to DSA | [Click Here](#-1-introduction-to-data-structure) |
| 🧠 Classification of DS | [Click Here](#-2-classification-of-data-structure) |
| 📦 Array | [Click Here](#-3-array) |
| 🔗 Linked List | [Click Here](#-4-linked-list) |
| 📚 Stack | [Click Here](#-5-stack) |
| 🚶 Queue | [Click Here](#-6-queue) |
| 🌳 Tree | [Click Here](#-7-tree) |
| 🌐 Graph | [Click Here](#-8-graph) |
| 🎯 Viva Questions | [Click Here](#-9-viva-questions-with-answers) |

---

<div align="center">

# 📖 1. INTRODUCTION TO DATA STRUCTURE

</div>

---

## 📌 What is Data Structure?

A **Data Structure** is a way of organizing, storing, and managing data efficiently so operations can be performed effectively.

---

## 📌 What is DSA?

```text
DSA = Data Structure + Algorithm
```

Where:

- **Data Structure** → Organizes data
- **Algorithm** → Solves problems step-by-step

---

## 🎯 Why DSA is Important?

<table>
<tr>
<th>Benefit</th>
<th>Description</th>
</tr>

<tr>
<td>⚡ Fast Processing</td>
<td>Reduces execution time</td>
</tr>

<tr>
<td>💾 Memory Efficiency</td>
<td>Uses memory effectively</td>
</tr>

<tr>
<td>🧠 Problem Solving</td>
<td>Improves logical thinking</td>
</tr>

<tr>
<td>💻 Interview Preparation</td>
<td>Essential for tech interviews</td>
</tr>

<tr>
<td>🚀 Software Development</td>
<td>Used in real applications</td>
</tr>

</table>

---

# 🧠 2. CLASSIFICATION OF DATA STRUCTURE

---

<div align="center">

## 📊 CLASSIFICATION DIAGRAM

</div>

```text
                              DATA STRUCTURE
                                     │
                ┌────────────────────┴────────────────────┐
                │                                         │
         LINEAR DATA STRUCTURE                 NON-LINEAR DATA STRUCTURE
                │                                         │
     ┌──────────┼──────────┐                     ┌────────┴────────┐
     │          │          │                     │                 │
   ARRAY      STACK      QUEUE                 TREE              GRAPH
                │
          LINKED LIST
```

---

## 🔹 Linear Data Structure

### 📌 Characteristics

- Data stored sequentially
- Easy traversal
- Single-level structure

### 📌 Examples

- Array
- Stack
- Queue
- Linked List

---

## 🔹 Non-Linear Data Structure

### 📌 Characteristics

- Hierarchical arrangement
- Complex relationships
- Multi-level structure

### 📌 Examples

- Tree
- Graph

---

# 📦 3. ARRAY

---

<div align="center">

## 📊 ARRAY VISUALIZATION

</div>

```text
Index :    0      1      2      3      4

         ┌────┬────┬────┬────┬────┐
Array :  │ 10 │ 20 │ 30 │ 40 │ 50 │
         └────┴────┴────┴────┴────┘
```

---

## 📌 Definition

An **Array** is a collection of elements of the same data type stored in contiguous memory locations.

---

## ⚡ Advantages of Array

| ✅ Advantages | 📌 Description |
|---|---|
| Fast Access | Direct index access |
| Easy Traversal | Sequential reading |
| Simple Implementation | Easy to understand |

---

## ❌ Disadvantages of Array

| ❌ Disadvantages | 📌 Description |
|---|---|
| Fixed Size | Cannot grow dynamically |
| Memory Wastage | Unused allocated memory |
| Costly Insertion | Requires shifting |

---

# 🔍 SEARCHING ALGORITHMS

---

## 🔎 Linear Search

### 📌 Algorithm

1. Start from first element
2. Compare each element
3. If found → return position
4. Else → not found

---

### 💻 C Program

```c
#include<stdio.h>

int main() {

    int a[100], n, i, key, found = 0;

    printf("Enter array size: ");
    scanf("%d", &n);

    printf("Enter elements:\n");

    for(i = 0; i < n; i++) {
        scanf("%d", &a[i]);
    }

    printf("Enter searching element: ");
    scanf("%d", &key);

    for(i = 0; i < n; i++) {

        if(a[i] == key) {
            found = 1;
            break;
        }
    }

    if(found)
        printf("Element found at position %d", i + 1);
    else
        printf("Element not found");

    return 0;
}
```

---

## ⚡ Time Complexity

| Case | Complexity |
|---|---|
| Best Case | O(1) |
| Average Case | O(n) |
| Worst Case | O(n) |

---

# 🔎 Binary Search

---

## 📌 Conditions

✅ Array must be sorted.

---

## 📊 Binary Search Working

```text
Array: [10 20 30 40 50 60 70]

Step 1:
Middle = 40

If key < 40 → search LEFT
If key > 40 → search RIGHT
```

---

## 💻 C Program

```c
#include<stdio.h>

int main() {

    int a[100], n, i;
    int low, high, mid, key;

    printf("Enter size: ");
    scanf("%d", &n);

    printf("Enter sorted elements:\n");

    for(i = 0; i < n; i++) {
        scanf("%d", &a[i]);
    }

    printf("Enter search key: ");
    scanf("%d", &key);

    low = 0;
    high = n - 1;

    while(low <= high) {

        mid = (low + high) / 2;

        if(a[mid] == key) {
            printf("Element found at position %d", mid + 1);
            return 0;
        }

        else if(a[mid] < key)
            low = mid + 1;

        else
            high = mid - 1;
    }

    printf("Element not found");

    return 0;
}
```

---

## ⚡ Complexity Analysis

| Case | Complexity |
|---|---|
| Best | O(1) |
| Average | O(log n) |
| Worst | O(log n) |

---

# 🔄 SORTING ALGORITHMS

---

<div align="center">

## 📊 SORTING COMPARISON TABLE

</div>

| Algorithm | Best | Average | Worst | Stable |
|---|---|---|---|---|
| Bubble Sort | O(n) | O(n²) | O(n²) | ✅ |
| Selection Sort | O(n²) | O(n²) | O(n²) | ❌ |
| Insertion Sort | O(n) | O(n²) | O(n²) | ✅ |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) | ✅ |
| Quick Sort | O(n log n) | O(n log n) | O(n²) | ❌ |

---

# 🫧 Bubble Sort

---

## 📊 Working Process

```text
Pass 1:

[5] [1] [4] [2]

5 > 1 → Swap
1 5 4 2

5 > 4 → Swap
1 4 5 2

5 > 2 → Swap
1 4 2 5
```

---

## 💻 Bubble Sort Program

```c
#include<stdio.h>

int main() {

    int a[100], n, i, j, temp;

    printf("Enter size: ");
    scanf("%d", &n);

    printf("Enter elements:\n");

    for(i = 0; i < n; i++) {
        scanf("%d", &a[i]);
    }

    for(i = 0; i < n - 1; i++) {

        for(j = 0; j < n - i - 1; j++) {

            if(a[j] > a[j + 1]) {

                temp = a[j];
                a[j] = a[j + 1];
                a[j + 1] = temp;
            }
        }
    }

    printf("Sorted Array:\n");

    for(i = 0; i < n; i++) {
        printf("%d ", a[i]);
    }

    return 0;
}
```

---

# ⚡ Merge Sort

---

## 📌 Divide & Conquer Technique

```text
          [38 27 43 3]

              ↓

      [38 27]    [43 3]

          ↓          ↓

       [27 38]   [3 43]

              ↓

      [3 27 38 43]
```

---

## ✅ Advantages

- Very efficient
- Faster for large data
- Stable sorting

---

# 🔗 4. LINKED LIST

---

<div align="center">

## 📊 LINKED LIST STRUCTURE

</div>

```text
 HEAD
   │
   ▼
┌────────┬────────┐
│ DATA   │ NEXT   │ ─────►
└────────┴────────┘
                        ┌────────┬────────┐
                        │ DATA   │ NEXT   │ ─────► NULL
                        └────────┴────────┘
```

---

## 📌 Definition

A **Linked List** is a linear data structure where elements are connected using pointers.

---

## 📌 Self Referential Structure

```c
struct node {

    int data;
    struct node *next;
};
```

---

## 🔥 Advantages

| Advantage | Description |
|---|---|
| Dynamic Size | Memory allocated dynamically |
| Fast Insertion | No shifting required |
| Efficient Deletion | Easy node removal |

---

## ❌ Disadvantages

| Disadvantage | Description |
|---|---|
| Extra Memory | Pointer storage needed |
| Sequential Access | No direct indexing |

---

# ➕ INSERTION OPERATIONS

---

## 📌 Insertion at Beginning

```text
NEW NODE → HEAD
```

### 💻 Code

```c
newNode->next = head;
head = newNode;
```

---

## 📌 Insertion at End

### 💻 Code

```c
while(temp->next != NULL) {
    temp = temp->next;
}

temp->next = newNode;
```

---

## 📌 Deletion Operation

### 💻 Code

```c
temp = head;
head = head->next;
free(temp);
```

---

# 📚 5. STACK

---

<div align="center">

## 📊 STACK STRUCTURE

</div>

```text
            TOP
             │
             ▼
          ┌─────┐
          │ 30  │
          ├─────┤
          │ 20  │
          ├─────┤
          │ 10  │
          └─────┘
```

---

## 📌 Principle

# 🔥 LIFO → Last In First Out

---

## 📌 PUSH Operation

```c
stack[top] = value;
top++;
```

---

## 📌 POP Operation

```c
top--;
```

---

## 📌 Applications of Stack

- Function Calls
- Browser History
- Undo/Redo
- Expression Evaluation
- Recursion

---

# 🚶 6. QUEUE

---

<div align="center">

## 📊 QUEUE STRUCTURE

</div>

```text
FRONT                                      REAR
  │                                           │
  ▼                                           ▼

┌─────┬─────┬─────┬─────┐
│ 10  │ 20  │ 30  │ 40  │
└─────┴─────┴─────┴─────┘
```

---

## 📌 Principle

# 🔥 FIFO → First In First Out

---

## 📌 ENQUEUE

```c
queue[rear] = value;
rear++;
```

---

## 📌 DEQUEUE

```c
front++;
```

---

## 📌 Applications

| Application | Description |
|---|---|
| CPU Scheduling | Process management |
| Printer Queue | Print management |
| Ticket Booking | First come service |
| Network Buffer | Packet handling |

---

# 🌳 7. TREE

---

<div align="center">

## 🌲 TREE STRUCTURE

</div>

```text
                10
              /    \
             5      15
            / \    /  \
           2   7  12  20
```

---

## 📌 Important Terminologies

| Term | Meaning |
|---|---|
| Root Node | Top node |
| Leaf Node | Node without child |
| Parent Node | Node having child |
| Child Node | Descendant node |

---

## 🌟 TYPES OF TREE

- Binary Tree
- Binary Search Tree
- AVL Tree
- Red Black Tree
- B Tree
- B+ Tree

---

## 🔄 TREE TRAVERSAL

| Traversal | Order |
|---|---|
| Inorder | Left → Root → Right |
| Preorder | Root → Left → Right |
| Postorder | Left → Right → Root |

---

# 🌐 8. GRAPH

---

<div align="center">

## 📊 GRAPH REPRESENTATION

</div>

```text
        A -------- B
        |          |
        |          |
        C -------- D
```

---

## 📌 Components of Graph

| Component | Description |
|---|---|
| Vertex | Node |
| Edge | Connection |
| Weight | Cost/Distance |

---

## 📌 Types of Graph

- Directed Graph
- Undirected Graph
- Weighted Graph
- Cyclic Graph
- Acyclic Graph

---

# 🔍 GRAPH TRAVERSAL

---

## 🌊 BFS (Breadth First Search)

### 📌 Uses Queue

```text
Level by level traversal
```

---

## 🌊 DFS (Depth First Search)

### 📌 Uses Stack

```text
Deep traversal first
```

---

## 📊 BFS vs DFS

| BFS | DFS |
|---|---|
| Queue | Stack |
| Level Wise | Depth Wise |
| More Memory | Less Memory |

---

<div align="center">

# 🎯 9. VIVA QUESTIONS WITH ANSWERS

</div>

---

# 📌 BASIC QUESTIONS

### 1️⃣ What is Data Structure?

A way of organizing data efficiently.

---

### 2️⃣ What is Algorithm?

A step-by-step procedure to solve a problem.

---

### 3️⃣ What is DSA?

Data Structure + Algorithm.

---

### 4️⃣ What is Array?

Collection of same type data stored sequentially.

---

### 5️⃣ What is Linked List?

A collection of nodes connected using pointers.

---

### 6️⃣ What is Stack?

A linear structure following LIFO.

---

### 7️⃣ What is Queue?

A linear structure following FIFO.

---

### 8️⃣ What is Tree?

Hierarchical data structure.

---

### 9️⃣ What is Graph?

Collection of nodes and edges.

---

### 🔟 What is Searching?

Finding a specific element.

---

### 1️⃣1️⃣ What is Sorting?

Arranging data in order.

---

### 1️⃣2️⃣ What is Binary Search?

Searching in sorted array using divide method.

---

### 1️⃣3️⃣ Time Complexity of Binary Search?

```text
O(log n)
```

---

### 1️⃣4️⃣ Time Complexity of Bubble Sort?

```text
O(n²)
```

---

### 1️⃣5️⃣ What is Recursion?

Function calling itself.

---

### 1️⃣6️⃣ What is Overflow?

Insertion when memory is full.

---

### 1️⃣7️⃣ What is Underflow?

Deletion when structure is empty.

---

### 1️⃣8️⃣ What is Pointer?

Variable storing memory address.

---

### 1️⃣9️⃣ What is Node?

Basic unit of linked structure.

---

### 2️⃣0️⃣ What is Dynamic Memory Allocation?

Memory allocation during runtime.

---

# 🏁 END OF DSA LAB MANUAL

<div align="center">

## ⭐ THANK YOU ⭐

### 🚀 Happy Coding & Keep Practicing DSA

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C2FF,100:6A5ACD&height=120&section=footer"/>

</div>
