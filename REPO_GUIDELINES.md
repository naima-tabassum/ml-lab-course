# 📋 Repository Organization Guidelines

> This document is for **the repo maintainer (you!)** — it explains how to add new weekly content consistently.

---

## 🗂️ When Adding a New Week's Materials

### Step 1: Create the week folder
Use the format `Week_XX` (always two digits):
```
Week_01/    ✅ Correct
Week_1/     ❌ Wrong
week_01/    ❌ Wrong (use capital W)
```

### Step 2: Create subfolders inside
```bash
Week_XX/
├── README.md          ← Required! Explain the week
├── notes/
├── code/
├── datasets/
├── slides/
└── assignments/
```

### Step 3: Write the week's README.md
Copy the template from `Week_01/README.md` and fill in:
- Learning objectives
- Study order (Step 1, 2, 3...)
- File table
- Key concepts summary
- Self-check questions
- Link to next week

---

## 📝 File Naming Rules

Always use this format:

| Content Type | Naming Pattern | Example |
|-------------|---------------|---------|
| Main notebook | `week_XX_topic.ipynb` | `week_04_linear_regression.ipynb` |
| Practice notebook | `week_XX_practice.ipynb` | `week_04_practice.ipynb` |
| Notes file | `week_XX_notes.md` | `week_04_notes.md` |
| Assignment | `assignment_XX.md` | `assignment_04.md` |
| Solution | `solution_XX.ipynb` | `solution_04.ipynb` |
| Slides | `week_XX_slides.pdf` | `week_04_slides.pdf` |
| Dataset | `descriptive_snake_case.csv` | `house_prices.csv` |

**Rules:**
- Always lowercase for files (except `README.md`)
- Use underscores `_` not dashes `-` or spaces
- Include the week number in code/notes filenames
- Dataset names should describe the data, not the week

---

## 📓 How to Write Beginner-Friendly Notebooks

Inside every `.ipynb` file, follow this structure:

### Cell 1: Title + Overview
```markdown
# Week XX — Topic Name
## What this notebook covers
Brief 2-3 sentence description of what the student will do.
**Prerequisites:** What they need to know first.
```

### Cell 2: Install/Import check
```python
# Run this cell first to make sure all libraries are available
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
print("✅ All libraries loaded!")
```

### Cell 3 onwards: Content cells
- **Always explain before the code**, not after
- Use plain English comments inside code: `# This line loads the CSV file`
- Keep each code cell short (5–15 lines max)
- Add a markdown cell after complex outputs explaining what you see

### Good comment style:
```python
# Load the dataset
# We're using pandas read_csv() — it turns a CSV file into a table we can work with
df = pd.read_csv('data.csv')

# Show the first 5 rows to get a quick look at the data
df.head()
```

### Bad comment style:
```python
df = pd.read_csv('data.csv')  # load data
df.head()
```

---

## 📊 Dataset Guidelines

When adding datasets to the repo:

1. **Prefer small files** — keep datasets under 10 MB if possible
2. **Use CSV format** whenever possible (easy to read with Pandas)
3. **Add to the right place:**
   - If used only in one week: `Week_XX/datasets/`
   - If shared across weeks: `Resources/datasets/`
4. **Name descriptively:** `iris_flowers.csv` not `data.csv`
5. **Credit the source** — add a comment in the notebook:
   ```python
   # Dataset: Iris Flower Dataset
   # Source: UCI Machine Learning Repository (public domain)
   ```

---

## ✍️ Writing Style Guide

When writing notes or README files, follow these principles:

### ✅ Do:
- Write as if explaining to a friend with no ML background
- Use analogies and real-world examples
- Break complex ideas into numbered steps
- Bold key terms on first use
- Use tables to compare things

### ❌ Don't:
- Use academic jargon without explaining it
- Assume prior knowledge (except what was covered in previous weeks)
- Write walls of text — break it up
- Skip the "why" — always explain why something matters

### Example (Bad):
> Gradient descent is an optimization algorithm that iteratively adjusts parameters by computing the gradient of the loss function with respect to each parameter.

### Example (Good):
> **Gradient descent** is how a model gets better at predictions. Imagine you're blindfolded on a hilly field and want to reach the lowest point. You feel the slope under your feet and take a small step downhill. You repeat this until you stop going lower. That's gradient descent — the model keeps adjusting itself in the direction that reduces its errors.

---

## 🔄 Weekly Update Checklist

When adding a new week, make sure you've:
- [ ] Created `Week_XX/` folder with correct name
- [ ] Added all 5 subfolders (notes, code, datasets, slides, assignments)
- [ ] Written `Week_XX/README.md` using the template
- [ ] Notebook has explanatory comments in every code cell
- [ ] Notes file explains all key concepts in simple language
- [ ] Updated the main `README.md` table if topics changed
- [ ] Checked that links to previous/next week work

---

*Consistency is kindness — when every week follows the same structure, learners always know where to look.* 🎯
