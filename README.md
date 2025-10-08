[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MathiasBuff/RNA-cleaver/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Python](https://img.shields.io/badge/python-3.12%2B-blue)

# RNA Cleavage Simulation (Notebook App)

A lightweight, notebook-based app to simulate **RNA cleavage** and visualize fragment length distributions.  
Built for colleagues who want to **run the workflow directly in Jupyter** with minimal setup.

> **Note:** This repository ships a single Jupyter notebook containing the full app.

---

## ✨ Features

- Load an RNA sequence (FASTA or plain text)
- Apply in‑silico digestion with a chosen enzyme
- Generate a **fragment length map/plot**
- Export the **fragment list** as plain text for copy–paste into Excel

---

## 🚀 Quick Start

### Option A — Open in Binder (no install)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MathiasBuff/RNA-cleaver/main)

> **Heads‑up:** Binder sessions are temporary. **Download your results** before closing the tab.

### Option B — Run locally
1. Install dependencies into a fresh environment:
   ```bash
   pip install -r requirements.txt
   ```
2. Launch JupyterLab:
   ```bash
   jupyter lab
   ```
3. Open `main.ipynb` and run:
   - **Kernel → Restart & Run All** to execute the workflow in order.

---

## 🧭 Workflow Overview

Run cells **top → bottom**. If you change parameters, **re‑run the affected section** (or “Restart & Run All”).

---

## 🔧 Parameters

Common places to edit:
- **Sequence input**: path or pasted sequence
- **Enzyme choice**: rule set for cleavage
- **Plot options**: bins, range, labels, visual customisation

---

## 📥 Inputs & 📤 Outputs

- **Inputs**: RNA sequence file (FASTA or plain text).  
- **Outputs**: Fragment list as **plain text** (copy–paste to Excel).  
  - CSV/Excel/FASTA exports can be added later if needed.

---

## 🛠️ Troubleshooting

- **Module not found** → `pip install -r requirements.txt` or install packages manually.  
- **File not found** → Check the path/filename and working directory.  
- **Plots not visible** → Re‑run the plotting cell; ensure Jupyter is using the Python env with `matplotlib`.  
- **Binder data loss** → Binder is ephemeral; download outputs before closing.

When asking for help, include the **full error message** and mention which cell/section you ran.

---

## 🧪 Tested Environment

- Python 3.12
- JupyterLab or classic Notebook
- Libraries: `matplotlib` (core); standard library for the rest

---

## 📄 License

This project is licensed under the [MIT License](https://mit-license.org/)

---

*Last updated: 2025-10-08*
