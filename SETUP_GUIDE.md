# ⚙️ Setup Guide — Get Your Computer Ready for ML

> Follow these steps **once** before you start Week 01. This takes about 15–30 minutes.

---

## What You'll Install

| Tool | Why You Need It |
|------|----------------|
| Python 3 | The programming language we use |
| pip | Python's package installer |
| Jupyter Notebook | Interactive coding environment |
| NumPy | Math and number arrays |
| Pandas | Working with data tables |
| Matplotlib | Basic charts and graphs |
| Seaborn | Beautiful statistical plots |
| Scikit-learn | Ready-made ML algorithms |
| TensorFlow/Keras | Neural networks (used in Week 11+) |

---

## 🪟 Windows Setup

### Step 1: Install Python
1. Go to [python.org/downloads](https://www.python.org/downloads/)
2. Download **Python 3.10 or newer**
3. Run the installer
4. ⚠️ **Important:** Check the box that says **"Add Python to PATH"** before clicking Install

### Step 2: Verify Python is installed
Open **Command Prompt** (search for `cmd`) and type:
```
python --version
```
You should see something like `Python 3.11.2`

### Step 3: Install all required libraries
In Command Prompt, paste this and press Enter:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter tensorflow
```
Wait for everything to download and install (may take a few minutes).

### Step 4: Launch Jupyter Notebook
```bash
jupyter notebook
```
Your browser will open automatically. You're ready!

---

## 🍎 Mac Setup

### Step 1: Install Python
1. Go to [python.org/downloads](https://www.python.org/downloads/)
2. Download **Python 3.10 or newer** for macOS
3. Run the `.pkg` installer

### Step 2: Verify in Terminal
Open **Terminal** (search in Spotlight) and type:
```
python3 --version
```

### Step 3: Install libraries
```bash
pip3 install numpy pandas matplotlib seaborn scikit-learn jupyter tensorflow
```

### Step 4: Launch Jupyter
```bash
jupyter notebook
```

---

## 🐧 Linux Setup

```bash
sudo apt update
sudo apt install python3 python3-pip
pip3 install numpy pandas matplotlib seaborn scikit-learn jupyter tensorflow
jupyter notebook
```

---

## 🌐 No Installation? Use Google Colab (Recommended for Beginners!)

If installation feels overwhelming, use **Google Colab** — it's free and works in your browser with zero setup!

1. Go to [colab.research.google.com](https://colab.research.google.com)
2. Sign in with your Google account
3. Click **"New Notebook"**
4. Upload any `.ipynb` file from this repository using **File → Upload Notebook**

> All libraries (NumPy, Pandas, Scikit-learn, etc.) are **already installed** in Colab. Just run your code!

---

## ✅ Test Your Setup

After installation, open a Jupyter Notebook and run this code to make sure everything works:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.linear_model import LinearRegression

print("✅ NumPy version:", np.__version__)
print("✅ Pandas version:", pd.__version__)
print("✅ All libraries loaded successfully!")
```

If you see the version numbers printed without any errors — **you're all set!** 🎉

---

## 🐛 Common Problems & Fixes

| Problem | Fix |
|---------|-----|
| `python` not found | Use `python3` instead, or re-install Python with "Add to PATH" checked |
| `pip` not found | Try `python -m pip install ...` |
| Library not found error | Run `pip install <library-name>` again |
| Jupyter won't open | Try `pip install --upgrade jupyter` |
| Port already in use | Run `jupyter notebook --port=8889` |

---

*Once setup is done, head to [Week_01/](./Week_01/) and start learning!* 🚀
