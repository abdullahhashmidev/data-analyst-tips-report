# Data Analyst Tips Report

A practical guide and analysis workflow for writing clear, decision-ready data analyst reports, using a restaurant tips dataset. Written for beginners and experienced analysts alike.

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-analysis-150458?style=flat&logo=pandas&logoColor=white)

## What is in this repo

| Path | Purpose |
|------|---------|
| `readme.md` | This guide |
| `scripts/` | Jupyter notebooks for the analysis |
| `data/` | Input dataset |
| `Reports/` | Generated report outputs |
| `requirements.txt` | Python dependencies |

## Getting started

**Requirements:** Python 3.10+.

```bash
# 1. Clone
git clone https://github.com/abdullahhashmidev/data-analyst-tips-report.git
cd data-analyst-tips-report

# 2. Create and activate a virtual environment (Git Bash on Windows)
python -m venv .venv
source .venv/Scripts/activate
# macOS / Linux: source .venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Open the analysis notebook
jupyter notebook scripts/
```

## Analysis workflow

Each report follows the same four steps:

1. **Data composition:** what the data contains, types, missing values
2. **Data distribution:** spread, outliers, normality checks
3. **Data comparison:** groups compared with suitable tests
4. **Data relationships:** correlation and regression, with interpretation

Statistical tests use SciPy and statsmodels. Every plot is followed by a written interpretation, written as it would appear in a submitted report.

## Writing tips

- Lead with the answer, then the evidence.
- Name the test you used and why it fits the data.
- Report effect sizes and uncertainty, not only p-values.
- Show one chart per question. Remove charts that do not support a conclusion.
- State limitations: sample size, missing data and what the data cannot tell you.

## Using AI assistants for analysis

A prompt that worked well for generating a first draft of the analysis:

> I have a dataframe of tips data. Act as a data analyst and write Python code using pandas, NumPy, seaborn, matplotlib and Plotly for: (1) data composition, (2) data distribution, (3) data comparison, and (4) data relationships. Use SciPy and statsmodels for statistics. Interpret each result in short report form. Check every number before you use it.

Always verify AI-generated code and numbers against the data yourself.

## Author

**Abdullah Hashmi**, AI Engineer, Karachi, Pakistan · [GitHub](https://github.com/abdullahhashmidev)
