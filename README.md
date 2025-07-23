# Algorithm Checkpoint Projects

This repository contains two algorithmic solutions written in pseudocode for a checkpoint assignment. Each file tackles a different problem—one focused on set operations, and the other on vector mathematics.

---

## 📘 Contents

1. [Addition of Complement of Two Sets]
2. [Dot Product & Orthogonality Check]

---

## 1. ➕ Addition of Complement of Two Sets

### 🔍 Description

This algorithm computes the **sum of elements** that are in the **complement** of two given sets. That is, it adds:
- Elements in `set1` that are **not** in `set2`
- Elements in `set2` that are **not** in `set1`

### 🧮 Logic
- Read two arrays: `set1` (size 4) and `set2` (size 5)
- For each element in `set1`, check if it is **absent** in `set2`, and add it to the `sum`
- Do the reverse for `set2` compared to `set1`
- Output the final `sum`



---

## 2. 🔗 Dot Product & Orthogonality Check

### 🔍 Description

This algorithm checks if **multiple pairs of vectors** are **orthogonal** by computing their dot product. Two vectors are orthogonal if their dot product equals zero.

### 🧮 Logic
- The user specifies how many vector pairs (`N`) to evaluate.
- For each pair, the vectors are read as arrays.
- Their dot product is calculated either:
  - Using a `PROCEDURE` (imperative approach), or
  - Using a `FUNCTION` (functional approach) that returns the result.
- If the dot product is `0`, the vectors are **orthogonal**.

### 🧪 Dot Product Formula
