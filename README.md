# 📚 C Programming Journey — B.Tech CSE (AKTU)

My C Programming journey as a **B.Tech Computer Science Engineering** student (Batch 2025–2029) at **KCC Institute of Technology and Management**, affiliated with **AKTU (Dr. A.P.J. Abdul Kalam Technical University)**.

This repository contains module-wise solutions based on coursework problem statements (**BCS-201 — C Programming**), covering fundamentals, searching, and sorting algorithms.

---

## 📂 Modules Overview

| Module | Topics Covered | Folder / File |
|--------|-----------------|----------------|
| Module 1 | Conditionals, Loops, Switch Cases, Pattern Programs | [Module-1-Basics](./Nasir_module_week1.pdf) |
| Module 2 | Linear Search, Binary Search, Bubble Sort, Insertion Sort, Selection Sort | [Module-2-Searching-Sorting](./Module-2-Searching-Sorting) |
| Module 3 | Merge Sort, Quick Sort | [Module-3](./Nasir_module_week3.pdf) |

*(More modules will be added as the semester progresses)*

---

## 🧩 Module 1 — Basics

Covers core C fundamentals:
- Conditional statements (`if-else`, nested `if`)
- Loops (`for`, `while`, `do-while`)
- Switch case statements
- Pattern printing programs

➡️ [View Module 1 files](./Nasir_module_week1.pdf)

---

## 🔍 Module 2 — Searching & Sorting Algorithms

Real-world inspired problems solved using core searching and sorting techniques:

| No. | Problem | Concept | File |
|-----|----------|----------|------|
| 1 | Find Student Roll Number | Linear Search | `01_linear_search.c` |
| 2 | Search Product ID | Binary Search | `02_binary_search.c` |
| 3 | Arrange Exam Scores | Bubble Sort | `03_bubble_sort.c` |
| 4 | Arrange Library Book Numbers | Insertion Sort | `04_insertion_sort.c` |
| 5 | Rank Players by Score | Selection Sort | `05_selection_sort.c` |

**Concept Summary:**
- **Linear Search** — Scans sequentially, O(n), works on unsorted data
- **Binary Search** — Divide-and-conquer on sorted data, O(log n), much faster
- **Bubble Sort** — Repeatedly swaps adjacent out-of-order elements, O(n²)
- **Insertion Sort** — Builds sorted array one element at a time, efficient for small/nearly-sorted data
- **Selection Sort** — Finds minimum each pass and places it correctly, O(n²)

➡️ [View Module 2 files](./Module-2-Searching-Sorting)

---

## 📘 Module 3 — Merge Sort & Quick Sort

Covers two of the most important **divide-and-conquer sorting algorithms**, applied to real-world inspired problems:

### 🔹 Topic 1: Merge Sort

| No. | Problem | Difficulty | File |
|-----|----------|------------|------|
| 1 | Rank Students by Marks | Easy | `rank_students_by_marks.c` |
| 2 | Organizing Product Prices | Easy | `organizing_product_prices.c` |
| 3 | Sort Employee Records by Salary (with lowest, highest, difference) | Medium | `sort_by_salary.c` |

### 🔹 Topic 2: Quick Sort

| No. | Problem | Difficulty | File |
|-----|----------|------------|------|
| 1 | Race Timing Analysis | Easy | `race_timing_analysis.c` |
| 2 | Organizing Library Book IDs | Easy | `organizing_library_book.c` |
| 3 | Online Store Sales Ranking (with top 3 & average) | Medium | `online_stores_sales_ranking.c` |

**Concept Summary:**
- **Merge Sort** — Divides the array recursively into halves until single elements remain, then merges them back in sorted order. Stable, O(n log n), needs extra space for merging.
- **Quick Sort** — Picks a pivot, partitions the array so smaller elements go left and larger go right, then recursively sorts each partition. In-place, average O(n log n), worst case O(n²) on poor pivot choices.

➡️ [View Module 3 files](./Nasir_module_week3.pdf)

---

## 🛠️ Tools Used

- **Language:** C
- **IDE:** VS Code
- **Compiler:** GCC

---

## ▶️ How to Run Any Program

```bash
gcc filename.c -o output
./output
```

---

## 🎯 About Me

I'm a first-year CSE student building a strong foundation in programming and data structures, with a long-term goal in Data Science & AI/ML.

**Author:** Md Nasir Ansari
