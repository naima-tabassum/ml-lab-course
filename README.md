# 🤖 Machine Learning Lab — Complete Course Repository

> **A beginner-friendly, week-by-week guide to learning Machine Learning through hands-on lab work.**
> Perfect for students, self-learners, and anyone curious about ML — no prior experience needed!

---

## 🙋 Who Is This For?

This repository is for you if:
- You're taking a Machine Learning Lab course and want your materials organized
- You're a beginner who wants to learn ML step-by-step
- You want a clear roadmap instead of a pile of random files

**Don't worry if you're new.** Every folder has simple explanations written in plain English. We explain the *why*, not just the *what*.

---

## 📦 What's Inside This Repository?

```
ml-lab-course/
│
├── README.md                        ← You are here! Start here first.
├── LEARNING_ROADMAP.md              ← Your step-by-step study guide
├── SETUP_GUIDE.md                   ← How to set up your computer for ML
├── GLOSSARY.md                      ← Simple definitions of ML terms
│
├── Week_01/                         ← Introduction to ML & Python Basics
├── Week_02/                         ← Data Handling with Pandas & NumPy
├── Week_03/                         ← Data Visualization
├── Week_04/                         ← Linear Regression
├── Week_05/                         ← Logistic Regression & Classification
├── Week_06/                         ← Decision Trees & Random Forests
├── Week_07/                         ← Support Vector Machines (SVM)
├── Week_08/                         ← Model Evaluation & Validation
├── Week_09/                         ← Unsupervised Learning & Clustering
├── Week_10/                         ← Dimensionality Reduction (PCA)
├── Week_11/                         ← Neural Networks Introduction
├── Week_12/                         ← Deep Learning Basics
├── Week_13/                         ← Natural Language Processing (NLP)
├── Week_14/                         ← Final Project & Course Wrap-up
│
└── Resources/
    ├── cheatsheets/                 ← Quick-reference PDFs
    ├── datasets/                    ← All datasets used across weeks
    └── extra_reading/               ← Optional deeper learning material
```

> ⚠️ **Note:** Not all week folders may be filled yet — content is added weekly as the course progresses.

---

## 🗂️ Inside Each Week's Folder

Every week follows the **same clean structure** so you always know where to look:

```
Week_XX/
│
├── README.md          ← What this week is about (read this first!)
├── notes/
│   └── week_XX_notes.md        ← Simple written explanation of concepts
├── code/
│   ├── week_XX_main.ipynb      ← Main lab notebook (run this!)
│   └── week_XX_practice.ipynb  ← Extra exercises to practice
├── datasets/
│   └── (data files used this week)
├── slides/
│   └── week_XX_slides.pdf      ← Professor's presentation slides
└── assignments/
    ├── assignment_XX.md        ← Your task/questions
    └── solution_XX.ipynb       ← Solution (try yourself first!)
```

---

## 🚀 How to Get Started (Complete Beginner Guide)

### Step 1: Set Up Your Computer
Before anything else, read the **[SETUP_GUIDE.md](./SETUP_GUIDE.md)** to install:
- Python 3.x
- Jupyter Notebook or VS Code
- Required libraries (NumPy, Pandas, Matplotlib, Scikit-learn)

### Step 2: Understand the Big Picture
Read the **[LEARNING_ROADMAP.md](./LEARNING_ROADMAP.md)** to understand:
- What topics are covered and in what order
- How each week connects to the next
- How long each topic might take

### Step 3: Start from Week 01
Always begin with **[Week_01/README.md](./Week_01/README.md)**.
Each week tells you:
- What you'll learn
- What to read first
- Which notebook to run
- What to do next

### Step 4: Run the Code Yourself
- Open the `.ipynb` files in Jupyter Notebook
- Read each cell carefully — comments explain what each line does
- Run the code, change values, and experiment!

### Step 5: Practice
After each week's main notebook, try the `_practice.ipynb` file on your own.

---

## 🗺️ Learning Roadmap (Quick View)

| Week | Topic | Key Skill You'll Learn |
|------|-------|----------------------|
| 01 | Intro to ML + Python | Understand what ML is; Python basics |
| 02 | Data Handling | Load, clean, and explore data |
| 03 | Visualization | Plot data with Matplotlib & Seaborn |
| 04 | Linear Regression | Predict continuous values |
| 05 | Logistic Regression | Classify yes/no problems |
| 06 | Decision Trees | Make rule-based decisions |
| 07 | SVM | Find best decision boundaries |
| 08 | Model Evaluation | Know if your model is actually good |
| 09 | Clustering | Group similar data without labels |
| 10 | PCA | Reduce complexity of data |
| 11 | Neural Networks | Mimic how the brain learns |
| 12 | Deep Learning | Build powerful neural networks |
| 13 | NLP | Teach machines to understand text |
| 14 | Final Project | Apply everything you've learned! |

📖 **Full detailed roadmap** → [LEARNING_ROADMAP.md](./LEARNING_ROADMAP.md)

---

## 💻 Tools & Technologies Used

| Tool | What It's For | Beginner-Friendly? |
|------|--------------|-------------------|
| Python 3 | Main programming language | ✅ Yes |
| Jupyter Notebook | Run code interactively | ✅ Yes |
| NumPy | Math and arrays | ✅ Yes |
| Pandas | Handle data like spreadsheets | ✅ Yes |
| Matplotlib / Seaborn | Create graphs and charts | ✅ Yes |
| Scikit-learn | Ready-made ML algorithms | ✅ Yes |
| TensorFlow / Keras | Deep learning (later weeks) | ⚠️ Moderate |

---

## 📘 New to Machine Learning? Start Here

**What is Machine Learning?**
> Machine Learning is teaching computers to learn from data — without programming every single rule manually. Instead of writing `if it rains, carry an umbrella`, you show the computer thousands of past weather examples and let it figure out the pattern itself.

**Three Types of ML (Simple Explanation):**
- 🏷️ **Supervised Learning** — You give the computer labeled examples (like a teacher showing right answers). *Example: Spam email detection*
- 🔍 **Unsupervised Learning** — The computer finds patterns on its own with no labels. *Example: Grouping similar customers together*
- 🎮 **Reinforcement Learning** — The computer learns by trial and error with rewards. *Example: A game-playing AI*

---

## 📁 Naming Conventions Used in This Repo

To keep everything organized, we follow these rules:

| Type | Format | Example |
|------|--------|---------|
| Folders | `Week_XX` (two digits) | `Week_01`, `Week_12` |
| Notebooks | `week_XX_topic.ipynb` | `week_03_visualization.ipynb` |
| Notes | `week_XX_notes.md` | `week_05_notes.md` |
| Datasets | `descriptive_name.csv` | `house_prices.csv` |
| Slides | `week_XX_slides.pdf` | `week_07_slides.pdf` |

---

## 🤝 How to Use This Repo

### If you're a student in this course:
1. Star ⭐ this repository so you can find it easily
2. Follow the weeks in order — don't skip ahead
3. Always read the `README.md` inside each week's folder first
4. Try the code yourself before looking at solutions

### If you're a self-learner:
1. Start at [SETUP_GUIDE.md](./SETUP_GUIDE.md)
2. Follow the [LEARNING_ROADMAP.md](./LEARNING_ROADMAP.md)
3. Each week is self-contained — the notes explain everything
4. Use the [GLOSSARY.md](./GLOSSARY.md) when you see an unfamiliar word

---

## ❓ Frequently Asked Questions

**Q: Do I need to know math to start?**
> Basic math (addition, multiplication, percentages) is enough for Week 01–05. Math gets slightly deeper in later weeks, but all formulas are explained in simple terms.

**Q: What if my code doesn't run?**
> Check [SETUP_GUIDE.md](./SETUP_GUIDE.md) first. Make sure all libraries are installed. Each notebook also has a first cell that lists required packages.

**Q: Can I learn this without a teacher?**
> Absolutely! Every notebook has comments, and every week has a `notes/` folder with written explanations. You can work through this entirely on your own.

**Q: How long does each week take?**
> Typically 2–4 hours per week, including reading notes, running code, and doing the practice exercises.

---

## 📌 Quick Links

| Resource | Link |
|----------|------|
| 🗺️ Full Learning Roadmap | [LEARNING_ROADMAP.md](./LEARNING_ROADMAP.md) |
| ⚙️ Setup Guide | [SETUP_GUIDE.md](./SETUP_GUIDE.md) |
| 📖 ML Glossary | [GLOSSARY.md](./GLOSSARY.md) |
| 📊 All Datasets | [Resources/datasets/](./Resources/datasets/) |
| 📄 Cheat Sheets | [Resources/cheatsheets/](./Resources/cheatsheets/) |
| 🟢 Start Learning | [Week_01/](./Week_01/) |

---

## 🌟 Tips for Success

> 💡 **Read before you run** — Always read the week's `README.md` and notes before opening a notebook.

> 🔁 **Repeat the code** — Type the code yourself instead of just reading it. It makes a huge difference.

> 🤔 **Ask "why"** — Don't just memorize what the code does. Ask yourself *why* it's written that way.

> 🧪 **Break things** — Change values in the notebook and see what happens. Experimenting is how you truly learn.

> 📓 **Keep notes** — Write your own short summary after each week. Teaching it back to yourself is the best way to understand.

---

## 📬 About This Repository

This repository is maintained as part of a **Machine Learning Lab Course**.
Materials are added weekly as the course progresses.

- **Course Level:** Undergraduate / Beginner–Intermediate
- **Language:** Python 3
- **Updated:** Weekly during the semester

---

*Happy Learning! Remember: every expert was once a beginner. Take it one week at a time.* 🚀
