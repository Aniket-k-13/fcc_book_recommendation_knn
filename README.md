# 📚 Book Recommendation Engine using KNN

This project is part of the **FreeCodeCamp Machine Learning with Python Certification**.  
It recommends books based on user similarity using a **K-Nearest Neighbors model**.

---

## 🧠 Project Goal
Build a recommendation system that:
- Takes a book title as input
- Returns **5 similar books** with cosine similarity distance
- Format must match FCC testing output ✅

---

## ✅ Key Features
- Uses Book-Crossings dataset (270k books, 1.1M ratings)
- Filters noisy data for meaningful recommendations:
  - Users with ≥ 200 ratings
  - Books with ≥ 100 ratings
- Cosine similarity for nearest neighbors
- Sparse matrix for performance

---

## 🛠 Tech Stack
- Python
- Pandas
- SciPy Sparse Matrix
- Scikit-Learn (KNN)

---

## 📌 Required Function
Returns:
```py
["Input Book Title", [["Recommended Book", distance], ...]]
FCC automated unit tests passed ✅

```

---

## 🗂 Dataset Source
Provided by FreeCodeCamp inside the notebook

👤 Author
Aniket Khandare


