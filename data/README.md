# Dataset Overview

This is a detailed dataset comprising health and demographic data of 100,000
individuals, aimed at facilitating diabetes-related research and predictive
modeling. It includes information on gender, age, location, race, hypertension,
heart disease, smoking history, BMI, HbA1c level, blood glucose level, and
diabetes status.

# Installation Instructions

For obvious reasons, the full dataset is not committed to the repository. The
dataset is publicly available on to download on Kaggle
[here](https://www.kaggle.com/datasets/priyamchoksi/100000-diabetes-clinical-dataset).
It is a single CSV file named `diabetes_dataset.csv`. A preview of the dataset
is in this directory containing the first 500 entries named `sample_data.csv`.

## 1) Navigate to the dataset + find the Download button
1. Open the Kaggle dataset page:
2. At the top of the page, locate the black **Download** button (near the top-right area).
3. Under the Download section, find the dropdown labeled **DOWNLOAD VIA**.
4. Select **kagglehub** from the dropdown (this will show a Python code snippet).

## 2) Install kagglehub
Open a terminal in your project folder and run:

```bash
pip install kagglehub
```
## 3) Paste the kagglehub code into your main Python file

Open your project’s main Python file (example: main.py).
Copy paste this code:
```
import kagglehub

path = kagglehub.dataset_download("shivamb/netflix-shows")

print("Path to dataset files:", path)
```

Once you have downloaded the dataset, place the file in the `data/` directory
(this directory) of this repository. 

