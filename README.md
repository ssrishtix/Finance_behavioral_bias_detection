# 🧠 Behavioral Bias Detector

A Machine Learning project that identifies **behavioral finance biases** in user-written thoughts or statements.

---

## 📌 What Is This?

This project detects **cognitive biases** behind financial or decision-making statements using a supervised ML model. It can classify thoughts into biases like:

- **Loss Aversion**
- **Overconfidence**
- **Anchoring Bias**
- **Confirmation Bias**
- **Herding Behavior**
- *(...and more)*

---

## 🧠 Why Behavioral Finance?

Behavioral finance studies how human psychology affects financial decisions. People are often unaware that their emotions, habits, or cognitive shortcuts (biases) influence decisions like investing, spending, or saving.

This project aims to **identify those hidden biases** and increase self-awareness.

---

## ⚙️ How It Works

- Dataset of labeled bias statements (including paraphrased samples)
- Preprocessing using:
  - Text cleaning
  - Lowercasing, punctuation removal
  - TF-IDF Vectorization
- Classification using:
  - Logistic Regression (baseline ML model)

---

## 📊 Visualizations

- **Bias Distribution**
- **Bias × Word Frequency Heatmap**
- **2D PCA Projection**

---

## 🖥️ Sample Output

```python
Input: "I don't want to sell this stock even if it's falling, I might lose more."
Detected Bias: Loss Aversion
