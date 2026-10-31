# Soft Computing — Module 1: Practical Exercise

**Course:** B.Tech CSE, 4th Year  
**Subject:** Soft Computing  
**Student Name:** Shivam Indore  
**Roll No.:** 2023BTCSE016  
**Assignment:** Module 1, Fuzzy Logic Practicals (Practicals 1 to 10)

---

## 📌 Overview

This repository contains the complete practical implementations for **Module 1 (Fuzzy Logic)** of Soft Computing. Each practical is implemented as a standalone Jupyter Notebook (`.ipynb`) with comprehensive markdown explanations, mathematical formulations, code implementations, and visualization plots using `numpy`, `matplotlib`, `scipy`, and `scikit-fuzzy`.

---

## 📚 Practical List & Syllabus Coverage

| # | Notebook File | Practical Title | Key Concepts & Functions |
|---|---|---|---|
| **01** | [`01_fuzzy_sets.ipynb`](./01_fuzzy_sets.ipynb) | **Fuzzy Sets using Membership Values** | Crisp vs. Fuzzy sets, Universe of discourse, Degree of membership $\mu_A(x) \in [0, 1]$, Support, $\alpha$-cut |
| **02** | [`02_membership_functions.ipynb`](./02_membership_functions.ipynb) | **Membership Functions** | Triangular (`fuzz.trimf`), Trapezoidal (`fuzz.trapmf`), and Gaussian (`fuzz.gaussmf`) membership curves |
| **03** | [`03_fuzzy_operations.ipynb`](./03_fuzzy_operations.ipynb) | **Fuzzy Set Operations** | Fuzzy Union ($\max$), Fuzzy Intersection ($\min$), and Fuzzy Complement ($1 - \mu$) |
| **04** | [`04_fuzzy_relation.ipynb`](./04_fuzzy_relation.ipynb) | **Fuzzy Relations & Composition** | Cartesian product ($R(x, y) = \min(A(x), B(y))$), Max-Min Composition ($R \circ S$) |
| **05** | [`05_linguistic_variables.ipynb`](./05_linguistic_variables.ipynb) | **Fuzzy Linguistic Variables** | Linguistic variables (e.g., *Temperature* with terms *Low*, *Medium*, *High*), Fuzzification of crisp values |
| **06** | [`06_fuzzy_rules.ipynb`](./06_fuzzy_rules.ipynb) | **Fuzzy IF-THEN Rules** | Rule structure (Antecedents & Consequents), Firing strength clipping, Aggregation of outputs |
| **07** | [`07_mamdani_fis.ipynb`](./07_mamdani_fis.ipynb) | **Mamdani Fuzzy Inference System** | End-to-end Mamdani FIS using `skfuzzy.control` (Quality & Service $\rightarrow$ Tip), Rule evaluation, Defuzzification |
| **08** | [`08_sugeno_fis.ipynb`](./08_sugeno_fis.ipynb) | **Sugeno (TSK) Fuzzy Inference System** | Takagi-Sugeno-Kang fuzzy model, Linear output functions ($z_i = p_i x + q_i y + r_i$), Weighted average aggregation |
| **09** | [`09_defuzzification.ipynb`](./09_defuzzification.ipynb) | **Defuzzification Methods** | Comparison of Centroid (`centroid`), Bisector (`bisector`), and Mean of Maximum (`mom`) on aggregated fuzzy sets |
| **10** | [`10_fuzzy_logic_controller.ipynb`](./10_fuzzy_logic_controller.ipynb) | **Complete Fuzzy Logic Controller (FLC)** | Full closed-loop FLC (Error & Change in Error $\rightarrow$ Control Action), 3D Control Surface visualization |

---

## 🛠️ Tech Stack & Requirements

- **Python 3.10+** (Tested on Python 3.14)
- **Core Libraries:**
  - `numpy` — Array manipulations and universe of discourse grids
  - `matplotlib` — 2D and 3D visualization of membership curves and control surfaces
  - `scipy` — Numerical routines and interpolation
  - `networkx` — Graph dependencies used by `skfuzzy.control`
  - `scikit-fuzzy` — Fuzzy logic functions, control systems, and defuzzification
  - `notebook` / `nbconvert` / `ipykernel` — Interactive notebook execution

---

## 🚀 Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/indoreshivam2006/Soft-Computing-Module-1.git
cd Soft-Computing-Module-1
```

### 2. Create and activate a Virtual Environment (Optional but recommended)
**On Windows (PowerShell):**
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

**On Linux / macOS:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Required Dependencies
```bash
python -m pip install numpy matplotlib scikit-fuzzy scipy networkx notebook nbconvert
```

---

## 💻 How to Run

### Option A: In VS Code / Antigravity IDE (Interactive)
1. Open any notebook (e.g. `01_fuzzy_sets.ipynb`) in your editor.
2. Select your Python kernel (or `.venv`) at the top right.
3. Click **Run All** or press `Shift + Enter` to run individual cells.

### Option B: In Jupyter Notebook Web UI
```bash
python -m notebook
```
This opens the Jupyter file browser in your default web browser where you can open and execute each notebook.

### Option C: Execute All Notebooks from Command Line
To run and execute all 10 notebooks in-place:
```bash
python -m nbconvert --to notebook --execute --inplace *.ipynb
```

---

## 📂 Project Structure

```text
Soft-Computing-Module-1/
│
├── .gitignore
├── README.md
├── 01_fuzzy_sets.ipynb
├── 02_membership_functions.ipynb
├── 03_fuzzy_operations.ipynb
├── 04_fuzzy_relation.ipynb
├── 05_linguistic_variables.ipynb
├── 06_fuzzy_rules.ipynb
├── 07_mamdani_fis.ipynb
├── 08_sugeno_fis.ipynb
├── 09_defuzzification.ipynb
└── 10_fuzzy_logic_controller.ipynb
```

---

## 📜 Author

- **Shivam Indore** (Roll No: `2023BTCSE016`)
- GitHub: [@indoreshivam2006](https://github.com/indoreshivam2006)
- Repository: [Soft-Computing-Module-1](https://github.com/indoreshivam2006/Soft-Computing-Module-1.git)
