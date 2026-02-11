# 🐍 Common Python Interview Coding Questions

A clean, well-structured collection of **22 frequently asked Python coding questions** organized by difficulty level — from basic logic to advanced algorithmic challenges. Each solution is clearly commented, wrapped in reusable functions, and includes time/space complexity notes where relevant.

---

## 📁 File

| File | Description |
|------|-------------|
| `Python_Interview_Questions.ipynb` | Main notebook with all 22 questions and solutions |

---

## 📚 Topics Covered

### 🟢 Section 1 — Basic / Logical Level
Foundational questions that test core Python skills.

| # | Question | Key Concept |
|---|----------|-------------|
| 1 | Hello World | Basic I/O |
| 2 | Reverse a String (no built-ins) | Loop + List insert |
| 3 | Palindrome Check | String slicing |
| 4 | Factorial (iterative & recursive) | Iteration / Recursion |
| 5 | Fibonacci Series | Loop, tuple swap |
| 6 | Find Min & Max in a List | Linear scan |
| 7 | Remove Duplicates from a List | Set / Manual filter |
| 8 | Count Character Frequency | Dictionary |
| 9 | Anagram Check | Frequency map |
| 10 | Find Second Largest Number | Two-variable scan |
| 11 | Swap Two Variables (no temp) | Tuple / Arithmetic |

---

### 🟡 Section 2 — Intermediate Level
Questions involving arrays, sorting, and combined data structures.

| # | Question | Key Concept |
|---|----------|-------------|
| 12 | Find Missing Number (1 to N) | Math formula |
| 13 | Merge Two Sorted Lists | Two-pointer merge |
| 14 | Find Intersection of Two Lists | Set operations |
| 15 | Flatten a Nested List | List comprehension |
| 16 | Count Vowels and Consonants | String traversal |
| 17 | Sort Dictionary by Values | Lambda + sorted() |
| 18 | Implement a Stack Using a List | LIFO data structure |
| 19 | Find Duplicate Elements | Set + count |

---

### 🔴 Section 3 — Advanced / Interview Favorites
High-frequency questions from top tech interviews requiring algorithmic optimization.

| # | Question | Key Concept | Time Complexity |
|---|----------|-------------|-----------------|
| 20 | Two Sum Problem | Two-pointer technique | O(n log n) |
| 21 | Check if a Number is Prime | √n optimization | O(√n) |
| 22 | Longest Substring Without Repeating Characters | Sliding window | O(n) |

---

## 🚀 How to Use

### Run in Jupyter Notebook (Local)
```bash
# 1. Clone or download the repository
# 2. Install Jupyter if not already installed
pip install notebook

# 3. Launch Jupyter
jupyter notebook

# 4. Open Python_Interview_Questions.ipynb
```

### Run in Google Colab
1. Go to [colab.research.google.com](https://colab.research.google.com)
2. Click **File → Upload Notebook**
3. Upload `Python_Interview_Questions.ipynb`
4. Run cells with `Shift + Enter`

---

## 💡 Key Highlights

- ✅ **Every question is wrapped in a clean function** with a proper docstring
- ✅ **Multiple approaches shown** where applicable (e.g., brute force vs. optimal)
- ✅ **Time & space complexity** noted for advanced solutions
- ✅ **Multiple test cases** so you can verify outputs at a glance
- ✅ **Section dividers and markdown explanations** make it easy to navigate
- ✅ **No `input()` calls** — all values are hardcoded for reproducibility

---

## 🧠 Concepts & Techniques Used

| Technique | Questions |
|-----------|-----------|
| Recursion | Q4 (Factorial) |
| Two-pointer | Q13 (Merge Sorted Lists), Q20 (Two Sum) |
| Sliding Window | Q22 (Longest Unique Substring) |
| Frequency Map / Dictionary | Q8, Q9 |
| Set Operations | Q7, Q14, Q19 |
| Math Formula | Q12 (Missing Number) |
| List Comprehension | Q15 (Flatten List) |
| Lambda + Sorted | Q17 (Sort Dict by Values) |
| √n Optimization | Q21 (Prime Check) |
| LIFO Stack | Q18 (Stack using List) |

---

## 📌 Interview Tips

> These are collected from real coding interview rounds.

1. **Always state the time and space complexity** before coding — interviewers expect it.
2. **Start with a brute-force** approach, then optimize — shows structured thinking.
3. **Use descriptive variable names** — `left/right` over `i/j` for two-pointer problems.
4. **Test with edge cases**: empty input, single element, all duplicates, negative numbers.
5. **Know the Pythonic way**: tuple swap, list comprehension, `dict.get()`, `set` operations.

---

## 🛠️ Requirements

- Python **3.7+**
- Jupyter Notebook or Google Colab
- No external libraries required — all standard Python

---

## 📂 Difficulty Summary

```
Total Questions : 22
🟢 Basic        : 11  (Q1  – Q11)
🟡 Intermediate :  8  (Q12 – Q19)
🔴 Advanced     :  3  (Q20 – Q22)
```

---

## 🤝 Contributing

Feel free to open a pull request to add more questions or improve existing solutions!

---

*Happy Coding! 🚀*
