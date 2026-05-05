# What Makes a Good App?
### Analyzing User Ratings & UX Patterns in the Apple App Store

## Overview
This project analyzes over 1.2 million Apple App Store apps
to uncover what characteristics drive higher user ratings.
Built as a Data Science class project with a UI/UX focus.

## Research Question
What app characteristics are most strongly associated with 
higher user ratings on the Apple App Store?

## Key Findings
- Most apps cluster between 4.0–5.0 stars (mean: 4.13)
- Magazines & Newspapers rate highest by category
- Free vs. Paid apps rate virtually the same (~4.13)
- No single numeric feature strongly predicts ratings
- Apps with more reviews converge toward higher ratings
  — the App Store acts as a natural UX filter

## Tools & Libraries
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Note on Dataset
The dataset file `appleAppData.csv` (387MB) exceeds GitHub's 
100MB file size limit and is therefore not included in this repository.

Please download it manually from:
kaggle.com/datasets/gauthamp10/apple-appstore-apps

Once downloaded, place it in the root of the project folder:
Intro_to_DataSci_FinalProject/
── AppStore_Analysis.ipynb
── appleAppData.csv  ← place here
── README.md

## Project Structure
Intro_to_DataSci_FinalProject/
-- AppStore_Analysis.ipynb  ← main notebook
-- appleAppData.csv         ← download separately
-- README.md

## Team
- Samyuktha Prabhakaran
- Rithika Robert Prakash James
