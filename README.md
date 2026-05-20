# Primetrade.ai Assignment

# Trader Performance vs Market Sentiment Analysis

## Objective

The objective of this project is to analyze the relationship between Bitcoin market sentiment (Fear vs Greed) and trader behavior/performance on Hyperliquid.

The analysis aims to identify patterns in:
- Trader profitability
- Trade frequency
- Position behavior
- Market participation
- Risk-taking activity

---

## Datasets Used

### 1. Bitcoin Fear & Greed Dataset

Contains:
- Date
- Fear/Greed classification
- Sentiment value

### 2. Hyperliquid Historical Trader Dataset

Contains:
- Account information
- Trade size
- Execution price
- Trade direction
- Closed PnL
- Timestamp
- Other trade-related features

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- PyCharm

---

## Project Workflow

### Data Preparation

- Loaded and cleaned datasets
- Checked missing values and duplicates
- Converted timestamps into datetime format
- Aligned datasets on daily date level
- Merged sentiment and trading datasets

### Feature Engineering

Created metrics including:
- Daily PnL per trader
- Win rate
- Average trade size
- Number of trades per day
- Long vs Short ratio

### Analysis

Performed comparative analysis between:
- Fear vs Greed periods
- Frequent vs infrequent traders
- Consistent vs inconsistent traders

---

## Key Insights

1. Traders generated higher average profits during Greed periods.

2. Fear periods showed lower trading activity and reduced profitability.

3. Frequent traders generally outperformed less active traders during bullish sentiment conditions.

4. Average trade sizes increased during Greed periods, indicating higher trader confidence and risk appetite.

---

## Strategy Recommendations

1. Reduce leverage and risk exposure during Fear market conditions.

2. Momentum-based strategies appear more effective during Greed periods.

3. Active traders may benefit more during bullish market sentiment compared to cautious market phases.

---

## Files Included

- `notebook.ipynb` → Main analysis notebook
- `summary.md` → Project summary and findings
- `charts/` → Generated visualization charts
- `data/` → Input datasets

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/primetrade-assignment.git
```

### 2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn notebook
```

### 3. Open the project in PyCharm or Jupyter Notebook

### 4. Run all cells inside:

```bash
notebook.ipynb
```

---

## Output

The project generates:
- Statistical summaries
- Visual charts
- Sentiment-based trader insights
- Strategy recommendations

---

## Note

AI assistance was used for guidance in project structuring, debugging, and workflow support. All implementation, analysis, execution, and final review were completed manually.
