# Exploratory Data Analysis (EDA) Project

This project contains a starter template for performing **Exploratory Data Analysis (EDA)** in Python using VS Code.

## 📦 Project Structure
```
eda_project/
 ├─ data/
 │   └─ housing.csv        # sample dataset (replace with your own)
 ├─ eda.py                 # Python script for EDA
 ├─ EDA.ipynb              # Jupyter Notebook for interactive EDA
 ├─ requirements.txt       # dependencies
 └─ README.md              # setup guide
```

## ⚙️ Setup Instructions

### 1. Create Virtual Environment
Open VS Code terminal and run:
```bash
py -m venv .venv
```

Activate it:
```bash
.venv\Scripts\activate
```

### 2. Install Requirements
```bash
py -m pip install -r requirements.txt
```

### 3. Run the Project

#### Option A: Run Jupyter Notebook (Recommended)
1. Open `EDA.ipynb` in VS Code.
2. Select the **.venv kernel** when prompted.
3. Run cells with **Shift+Enter**.

#### Option B: Run Python Script
```bash
py eda.py
```

This will print dataset info and generate plots.

### 4. Use Your Own Dataset
- Place your dataset inside the `data/` folder.
- Update file path in `eda.py` or `EDA.ipynb` if needed.

---

✅ You’re ready to explore your data! Modify and expand the notebook/script to perform deeper analysis.
