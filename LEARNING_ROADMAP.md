# 🗺️ Learning Roadmap — Machine Learning Lab Course

> This roadmap tells you exactly **what to study, in what order, and why**.
> Follow it step by step — each topic builds on the one before it.

---

## 🧭 How to Use This Roadmap

1. **Start at Phase 1** — even if you know some Python, review it quickly
2. **Don't skip weeks** — later topics assume you know earlier ones
3. **Each phase has a goal** — know what you're working toward
4. **Check off as you go** — use the checkboxes to track your progress

---

## 📍 Phase 1: Foundation (Weeks 01–03)
**Goal:** Be comfortable with Python and data before touching any ML

### ✅ Week 01 — Introduction to Machine Learning + Python Basics
- **Start with:** `Week_01/README.md`
- **Then read:** `Week_01/notes/week_01_notes.md`
- **Then run:** `Week_01/code/week_01_main.ipynb`
- **Practice:** `Week_01/code/week_01_practice.ipynb`

**What you'll learn:**
- What is Machine Learning and why it matters
- The 3 types of ML (supervised, unsupervised, reinforcement)
- Python basics: variables, loops, functions, lists
- How to use Jupyter Notebook

**You're ready for Week 02 when you can:**
- [ ] Explain what ML is in your own words
- [ ] Write a basic Python function
- [ ] Run cells in a Jupyter Notebook

---

### ✅ Week 02 — Data Handling with Pandas & NumPy
- **Start with:** `Week_02/README.md`
- **Then read:** `Week_02/notes/week_02_notes.md`
- **Then run:** `Week_02/code/week_02_main.ipynb`

**What you'll learn:**
- Load data from CSV files using Pandas
- Explore data: check size, types, missing values
- Clean messy data (handle nulls, fix types)
- Basic math operations with NumPy

**You're ready for Week 03 when you can:**
- [ ] Load a CSV file and display its first 5 rows
- [ ] Find and handle missing values
- [ ] Perform basic math on columns of a dataset

---

### ✅ Week 03 — Data Visualization
- **Start with:** `Week_03/README.md`
- **Then read:** `Week_03/notes/week_03_notes.md`
- **Then run:** `Week_03/code/week_03_main.ipynb`

**What you'll learn:**
- Plot bar charts, line graphs, histograms, scatter plots
- Use Matplotlib and Seaborn libraries
- Understand what each chart type is best for
- Visualize patterns and relationships in data

**You're ready for Week 04 when you can:**
- [ ] Create a histogram and explain what it shows
- [ ] Draw a scatter plot between two variables
- [ ] Identify whether two variables seem related

---

## 📍 Phase 2: Core Machine Learning (Weeks 04–08)
**Goal:** Learn and apply the most important ML algorithms

### ✅ Week 04 — Linear Regression
- **Start with:** `Week_04/README.md`
- **Key concept:** Predicting a *number* (like house price) from input features

**What you'll learn:**
- What regression means
- How a straight line fits data
- Train your first ML model with Scikit-learn
- Measure prediction error (MSE, R²)

**You're ready for Week 05 when you can:**
- [ ] Train a linear regression model on a dataset
- [ ] Interpret what the slope and intercept mean
- [ ] Calculate and explain the R² score

---

### ✅ Week 05 — Logistic Regression & Classification
- **Key concept:** Predicting a *category* (like spam/not spam) instead of a number

**What you'll learn:**
- Difference between regression and classification
- How logistic regression works (the S-curve)
- Binary and multi-class classification
- Accuracy, precision, recall explained simply

**You're ready for Week 06 when you can:**
- [ ] Train a logistic regression classifier
- [ ] Read a confusion matrix
- [ ] Explain the difference between precision and recall

---

### ✅ Week 06 — Decision Trees & Random Forests
- **Key concept:** Making decisions like a flowchart; combining many trees for power

**What you'll learn:**
- How a decision tree splits data using questions
- Why single trees can "overfit" (memorize instead of learn)
- How Random Forests fix this by combining many trees
- Feature importance: which inputs matter most?

**You're ready for Week 07 when you can:**
- [ ] Draw a simple decision tree by hand
- [ ] Explain what overfitting means
- [ ] Train a Random Forest and check feature importance

---

### ✅ Week 07 — Support Vector Machines (SVM)
- **Key concept:** Finding the best possible boundary between two classes

**What you'll learn:**
- What a "hyperplane" and "margin" are (in simple terms)
- Why SVMs try to maximize the margin
- The "kernel trick" for non-linear data
- When to use SVM vs other algorithms

---

### ✅ Week 08 — Model Evaluation & Validation
- **Key concept:** Knowing if your model is *actually* good, not just memorizing training data

**What you'll learn:**
- Train/test split — why you need separate data to test
- Cross-validation — a fairer way to evaluate
- Bias vs. Variance trade-off (simple explanation)
- Hyperparameter tuning with GridSearchCV

**⚠️ This is one of the most important weeks! Don't rush through it.**

**You're ready for Phase 3 when you can:**
- [ ] Split data into train and test sets correctly
- [ ] Perform 5-fold cross-validation
- [ ] Explain what "overfitting" and "underfitting" look like on a graph

---

## 📍 Phase 3: Advanced Topics (Weeks 09–13)
**Goal:** Go beyond the basics into specialized areas of ML

### ✅ Week 09 — Unsupervised Learning & Clustering
- **Key concept:** Finding patterns in data *without* any labels

**What you'll learn:**
- What unsupervised learning is and when to use it
- K-Means clustering algorithm (step by step)
- How to choose the right number of clusters (Elbow Method)
- Real-world use cases (customer segmentation, anomaly detection)

---

### ✅ Week 10 — Dimensionality Reduction (PCA)
- **Key concept:** Simplifying complex data without losing important information

**What you'll learn:**
- Why too many features causes problems ("curse of dimensionality")
- Principal Component Analysis (PCA) explained simply
- How to reduce 100 features to 2 while keeping most info
- Visualizing high-dimensional data in 2D

---

### ✅ Week 11 — Neural Networks Introduction
- **Key concept:** Machines that learn like the human brain (sort of)

**What you'll learn:**
- What a neuron is and how it connects to others
- Forward pass: how data flows through a network
- Backpropagation: how the network learns from mistakes
- Your first neural network with Keras

---

### ✅ Week 12 — Deep Learning Basics
- **Key concept:** Deeper neural networks that can learn complex patterns

**What you'll learn:**
- What makes a network "deep"
- Convolutional Neural Networks (CNNs) for images
- How to train a network to recognize handwritten digits
- Common problems: vanishing gradients, dropout

---

### ✅ Week 13 — Natural Language Processing (NLP)
- **Key concept:** Teaching machines to understand human language

**What you'll learn:**
- Text preprocessing: tokenization, stopwords, stemming
- Converting text to numbers (TF-IDF, word embeddings)
- Simple text classification (positive/negative sentiment)
- Introduction to modern NLP (transformers, BERT — overview)

---

## 📍 Phase 4: Capstone (Week 14)
**Goal:** Apply everything you've learned to a real problem

### ✅ Week 14 — Final Project
- **Pick a dataset** from `Resources/datasets/` or find your own
- **Apply the full ML pipeline:**
  1. Explore and visualize the data
  2. Clean and preprocess
  3. Try multiple algorithms
  4. Evaluate and compare models
  5. Write up your findings

**Final project checklist:**
- [ ] Dataset loaded and explored
- [ ] Data cleaned (no missing values, correct types)
- [ ] At least 2 ML models trained and compared
- [ ] Results visualized with charts
- [ ] Short write-up explaining what you found

---

## ⏱️ Suggested Study Schedule

| Phase | Weeks | Hours/Week | Total Time |
|-------|-------|-----------|------------|
| Foundation | 01–03 | 3–4 hrs | ~10 hrs |
| Core ML | 04–08 | 4–5 hrs | ~22 hrs |
| Advanced | 09–13 | 4–5 hrs | ~22 hrs |
| Capstone | 14 | 6–8 hrs | ~8 hrs |
| **Total** | **14 weeks** | | **~62 hrs** |

---

## 🔗 How the Topics Connect

```
Python Basics (W01)
       ↓
Data Handling (W02) → Visualization (W03)
       ↓
Linear Regression (W04) → Logistic Regression (W05)
       ↓
Decision Trees (W06) → SVM (W07)
       ↓
Model Evaluation (W08)  ← CRITICAL — applies to ALL models above
       ↓
Clustering (W09) → PCA (W10)
       ↓
Neural Networks (W11) → Deep Learning (W12) → NLP (W13)
       ↓
Final Project (W14) — combines everything
```

---

*Remember: slow and steady wins the race. Understanding one concept well is better than rushing through five.* 🐢
