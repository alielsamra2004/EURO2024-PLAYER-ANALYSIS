# 🇪🇺 EURO 2024 Player Analysis

A data-driven project that analyzes and ranks players in EURO 2024 using advanced performance metrics. This model compares actual tournament performance with public perception — revealing which players were **overhyped**, **underrated**, or **truly world-class**.

---

## 📊 Project Overview

This project aims to:

- Import and process player performance data from EURO 2024  
- Normalize and engineer features to evaluate player impact  
- Build a **Player Score Index (PSI)** based on weighted metrics  
- Compare model-based rankings with public opinion  
- Visualize insights and uncover perception vs. reality

---

## 🔍 Key Features

- 📈 Metric-based player rankings (G+A/90, consistency, impact)
- 🧠 Normalization & feature engineering for fair comparisons  
- 🎭 Mystery Player Challenge (guess the player based on stats)  
- ⚔️ 1v1 Showdowns between top players  
- 🗳️ Audience voting + Hype Gap analysis  
- 📊 Clear, interactive visualizations in Jupyter

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, difflib, unicodedata)  
- IPython / Jupyter Notebook  
- Matplotlib & Seaborn for visualization  

---

## 🚀 How to Run

1. **Clone the repository**:

```bash
git clone https://github.com/alielsamra2004/EURO2024-Player-Analysis.git
cd EURO2024-Player-Analysis
```

2. **Install dependencies**:

```bash
pip install -r requirements.txt
```

3. **Launch the notebook**:

Open `EURO_2024_Player_Analysis_Hands_On_Experience.ipynb` in Jupyter Notebook or Google Colab.

4. **Make sure you have the data file**:

> `euro_2024.csv` should be in the same folder as the notebook.  
> If using Colab, upload the file manually or use:

```python
df = pd.read_csv("https://raw.githubusercontent.com/alielsamra2004/EURO2024-PLAYER-ANALYSIS/main/euro_2024.csv")
```

---

## 📁 Repository Contents

- `EURO_2024_Player_Analysis_Hands_On_Experience.ipynb` – Main notebook  
- `euro_2024.csv` – Player stats dataset  
- `requirements.txt` – Python dependencies  
- `README.md` – Project documentation  

---

## ⚽ Created by the Sports Analytics Club
