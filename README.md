# 🌸 DSA Journey — Anime Arc ⚔️ (C++)

<p align="center">
  <img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" width="300">
</p>

> “Hard work is worthless for those that don’t believe in themselves.” — Naruto Uzumaki

---

## 🎯 Mission

Master Data Structures & Algorithms by solving:

* ✅ 12 Topics
* ✅ 40 Problems per Topic

  * 🟢 Easy: 10
  * 🟡 Medium: 20
  * 🔴 Hard: 10

📊 Total Goal: **480 Problems**

---

## 🧭 Folder Structure

```
dsa-journey-cpp/
│
├── README.md
├── progress.md
│
├── arrays/
├── strings/
├── linked_lists/
├── stacks/
├── queues/
├── trees/
├── graphs/
├── sorting/
├── binary_search/
├── hash_maps/
├── recursion/
├── dynamic_programming/
│
└── templates/
    └── base.cpp
```

---

## 🧩 Problem Template (use for every solution)

```cpp
/*
🧩 Problem: [Problem Name]
🔗 Link: [Problem URL]
📂 Topic: [Topic Name]
⚡ Difficulty: Easy / Medium / Hard

💡 Approach:
- Explain logic step by step
- Why this approach?

⏱ Time Complexity: O()
📦 Space Complexity: O()
*/

#include <bits/stdc++.h>
using namespace std;

int main() {
    // your code here
    return 0;
}
```

---

## 🧭 Progress Tracker

| Topic               | Easy | Medium | Hard | Total |
| ------------------- | ---- | ------ | ---- | ----- |
| Arrays              | 0/10 | 0/20   | 0/10 | 0/40  |
| Strings             | 0/10 | 0/20   | 0/10 | 0/40  |
| Linked Lists        | 0/10 | 0/20   | 0/10 | 0/40  |
| Stacks              | 0/10 | 0/20   | 0/10 | 0/40  |
| Queues              | 0/10 | 0/20   | 0/10 | 0/40  |
| Trees               | 0/10 | 0/20   | 0/10 | 0/40  |
| Graphs              | 0/10 | 0/20   | 0/10 | 0/40  |
| Sorting             | 0/10 | 0/20   | 0/10 | 0/40  |
| Binary Search       | 0/10 | 0/20   | 0/10 | 0/40  |
| Hash Maps           | 0/10 | 0/20   | 0/10 | 0/40  |
| Recursion           | 0/10 | 0/20   | 0/10 | 0/40  |
| Dynamic Programming | 0/10 | 0/20   | 0/10 | 0/40  |

---

## ⚔️ Power Levels

* 🟢 Beginner: 0–120 problems
* 🟡 Intermediate: 120–300 problems
* 🔴 Advanced: 300–480 problems
* 👑 Hokage Level: 480+

---

## 📜 Rules of the Journey

* Solve at least 2–5 problems daily ⚡
* Push to GitHub every day
* Always write approach before code
* Focus on understanding, not memorizing

---

## 🧠 Topics Covered

* Arrays
* Strings
* Linked Lists
* Stacks
* Queues
* Trees
* Graphs
* Sorting
* Binary Search
* Hash Maps
* Recursion
* Dynamic Programming

---

## 🧾 Example Solution File

```
arrays/two_sum.cpp
```

```cpp
/*
🧩 Problem: Two Sum
🔗 Link: https://leetcode.com/problems/two-sum/
📂 Topic: Arrays
⚡ Difficulty: Easy

💡 Approach:
- Use hashmap to store visited elements
- Check if (target - current) exists

⏱ Time: O(n)
📦 Space: O(n)
*/

#include <bits/stdc++.h>
using namespace std;

vector<int> twoSum(vector<int>& nums, int target) {
    unordered_map<int, int> mp;

    for(int i = 0; i < nums.size(); i++) {
        int complement = target - nums[i];
        if(mp.count(complement)) {
            return {mp[complement], i};
        }
        mp[nums[i]] = i;
    }
    return {};
}
```

---

## 📅 progress.md

```
# 📈 Daily Progress Log

Day 1:
- Two Sum ✅
- Best Time to Buy and Sell Stock ✅

Day 2:
- Binary Search ✅
- Reverse Linked List ✅

Day 3:
- Valid Parentheses ✅
```

---

## 🚀 Git Workflow

```
git add .
git commit -m "Day X: solved Y problems"
git push
```

---

## 🌟 Final Goal

Become a:

* 💻 Strong Problem Solver
* 🚀 Freelance Developer
* 🧠 Logical Thinker

---

<p align="center">
  <img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" width="300">
</p>

---
