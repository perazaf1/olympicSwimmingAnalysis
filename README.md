# Swimming Data Analysis

A data analysis project focused on swimming performance, built with a Jupyter Notebook, a CSV dataset, and visual outputs stored in the `Images/` folder.

---

## Project Objective

This project aims to:

- explore a swimming-related dataset;
- clean and prepare the data;
- produce descriptive statistics;
- build visualizations to identify trends;
- extract useful and actionable insights.

---

## Project Structure

```text
swimming/
├─ Images/               # Figures, charts, exported visuals
├─ *.ipynb               # Main analysis notebook
├─ *.csv                 # Source dataset(s)
├─ .gitignore
└─ README.md
```

> The repository is intentionally minimal: notebook, CSV, `Images/`, and essential config/documentation files only.

---

## Tech Stack

- **Python 3.x**
- **Jupyter Notebook**
- Common analysis libraries (depending on notebook content), e.g.:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

---

## Setup & Run

### 1) Clone the repository

```powershell
git clone https://github.com/perazaf1/olympicSwimmingAnalysis
cd swimming
```

### 2) Create a virtual environment

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### 3) Install dependencies

```powershell
pip install -r requirements.txt
```



### 4) Launch Jupyter Notebook

```powershell
jupyter notebook
```

Then open the `*.ipynb` file.

---

## Analysis Workflow

The notebook typically follows this pipeline:

1. **Load data** (`.csv`)
2. **Initial inspection** (types, missing values, duplicates)
3. **Data cleaning / preparation**
4. **Exploratory Data Analysis (EDA)**
5. **Trend visualization**
6. **Interpretation and conclusions**

---

## Results & Visualizations

Generated figures are saved in `Images/`.

Typical outputs may include:

- performance distributions;
- category comparisons (stroke, distance, etc.);
- variable correlations;
- time-based performance evolution.

---

## Reproducibility

To reproduce results:

1. use the same CSV file;
2. run notebook cells in order;
3. ensure dependencies are installed;
4. export/save figures into `Images/`.

---

## Data Quality Checks

Key checks to include:

- missing values;
- outliers;
- unit consistency (time, distance);
- date format consistency;
- duplicates.

---

## Possible Improvements

- add automated data validation tests;
- automate part of the analysis pipeline;
- include richer/interactive visualizations.

---

## Author

Project created by **perzaf1**.

---

## Contributing

Contributions are welcome:

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Open a Pull Request

---
