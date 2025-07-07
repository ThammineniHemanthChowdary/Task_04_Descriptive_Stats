# Task\_04\_Descriptive\_Stats

This repository contains descriptive statistical analysis of a dataset related to Facebook Ads during the 2024 U.S. Presidential Election. The analysis is performed using three different methods: **Pure Python**, **Pandas**, and **Polars**. Each method is implemented in a separate Colab notebook.

---

## Repository Structure

```
Task_04_Descriptive_Stats/
├── Output/
│   ├── pandas_output.txt
│   ├── polars_output.txt
│   └── python_only_output.txt
├── pandas.ipynb
├── polars.ipynb
├── python_only.ipynb
├── README.md
└── .gitignore
```

---

## Notebooks Overview

* `python_only.ipynb`: Performs the analysis using only base Python libraries like `csv`, `collections`, and `statistics`.
* `pandas.ipynb`: Uses the Pandas library to compute descriptive statistics and grouped summaries efficiently.
* `polars.ipynb`: Uses Polars, a fast DataFrame engine, to compute the same statistics with high performance.

Each notebook reads the dataset, performs analysis, and saves output to a corresponding `.txt` file in the `/Output` directory.

---

## Output Files

Located in the `Output/` folder:

* `pandas_output.txt`
* `polars_output.txt`
* `python_only_output.txt`

These files contain the computed statistics and grouped summaries.

---

## Dataset

* The dataset used is `2024_fb_ads_president_scored_anon.csv`
* It includes metadata and performance metrics of political ads
* The dataset is not committed to this repository

---

## How to Run

1. Open any of the `.ipynb` notebooks in Google Colab or Jupyter
2. Upload the dataset when prompted
3. Run all cells to generate statistics and save the output

---

## Summary

This project demonstrates how the same data summarization task can be approached using different tools:

* **Base Python** for transparency and control
* **Pandas** for ease of use and readability
* **Polars** for speed and efficiency with large data

Outputs from all three approaches are consistent and provide grouped insights by `page_id`.

The repository is organized, clean, and ready for demonstration or presentation.
