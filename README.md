# BI2025 – Assignment 3 (Group 058)

This repository contains the implementation and documentation for
Assignment 3 (Data Analytics) of the BI2025 course at TU Wien.

## Authors
- **Student A:** Brikenda Lajqi Pepshi (Matr.Nr. 12502840)
- **Student B:** Sofiana Braho (Matr.Nr. 12502707)
- **Group:** 058

## Contents
- `BI2025_Group058.ipynb` – Jupyter notebook implementing the full CRISP-DM workflow
  (Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, Deployment),
  including provenance logging.
- `requirements.txt` – List of Python dependencies required to reproduce the experiments.
- `LICENSE` – License information for the repository.

## Data
The dataset used in this project originates from OpenML (US News Colleges dataset, ID 538).
For submission and reproducibility, the processed CSV file is included in the ZIP submission
under the `data/` directory. The GitHub repository intentionally contains only code and
documentation.
Link to the dataset: GR058 12502707 12502840 colleges_usnews https://www.openml.org/search?type=data&status=active&qualities.NumberOfInstances=between_1000_10000&qualities.NumberOfFeatures=between_10_100&qualities.NumberOfClasses=lte_1&sort=qualities.NumberOfInstances&order=asc&id=538

## Reproducibility
To reproduce the experiments, install the required dependencies and run the notebook
top to bottom:

```bash
pip install -r requirements.txt


