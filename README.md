# Machine_Learning
# ♟️ Chess Dataset Analysis

This project explores and analyzes a chess games dataset using **Python**, **Pandas**, and **NumPy** in Google Colab.

## 📊 Dataset Overview

- **Source**: Chess games dataset (e.g., from Kaggle or Lichess)
- **File**: `games.csv`
- **Sample columns**:
  - `white_id`, `black_id`
  - `winner`, `opening_name`
  - `white_rating`, `black_rating`
  - `turns`, `victory_status`

## ✅ Key Features

- Loaded the dataset using `pandas.read_csv()`
- Performed data cleaning and exploration
- Used **NumPy** for statistical calculations
- Added new columns (e.g., long games)
- Filtered and grouped data to extract insights

## 🧪 Sample Operations

1. **Viewed top 5 records**
2. **Calculated average and standard deviation of turns**
3. **Identified games where white won**
4. **Checked most popular openings**
5. **Flagged long games (more than 60 turns)**

## 🧠 Libraries Used

- `pandas`
- `numpy`
- `google.colab` (for file upload/drive access)

## 🧾 How to Run

1. Upload `games.csv` to Colab or connect Google Drive
2. Install necessary packages (already in Colab by default)
3. Run the notebook cells to explore the data

```python
import pandas as pd
import numpy as np
df = pd.read_csv('games.csv')
```

## 📈 Sample Output

```python
# Average turns per game
np.mean(df['turns'])  # e.g., 40.5
```

## 📌 Project Goal

The goal is to understand patterns in chess games like:
- Common openings
- Who wins more (white vs black)
- Game duration patterns
- Rating distribution

## 🔗 Useful Links

- [Kaggle Dataset (example)](https://www.kaggle.com/datasets/datasnaek/chess)
- [Pandas Documentation](https://pandas.pydata.org/)
- [NumPy Documentation](https://numpy.org/)
