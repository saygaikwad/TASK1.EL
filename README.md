# Netflix Data Cleaning and Preprocessing

This repository contains a cleaned version of the **Netflix Movies and TV Shows dataset**, originally sourced from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows). The project focuses on cleaning and preparing the data using Python (Pandas), making it ready for further analysis or visualization.

---

## Objective

To clean the raw Netflix dataset by handling missing values, removing duplicates, standardizing column formats, and correcting data types, so that the data can be reliably used for analysis, modeling, or dashboarding (e.g., Tableau, Power BI).

---

## Contents

| File | Description |
|------|-------------|
| `netflix_titles.csv` | Original raw dataset (if added) |
| `netflix_cleaned.csv` | Final cleaned dataset |
| `cleaning_script.ipynb` | Jupyter Notebook containing full cleaning steps |
| `README.md` | Documentation of the project |

---

## Cleaning Summary

- Filled missing values in `director`, `cast`, and `country` with `"unknown"`
- Dropped rows with missing `rating`, `duration`, or `date_added`
- Removed duplicate records
- Standardized text columns to lowercase and removed extra spaces
- Converted `date_added` to datetime format
- Renamed columns to lowercase with underscores
- Verified and corrected data types

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/netflix-data-cleaning.git
   cd netflix-data-cleaning
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook cleaning_script.ipynb
   ```

3. Run the notebook cells to review or reprocess the dataset.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Acknowledgments

Dataset originally published on [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) by Shivam Bansal.
