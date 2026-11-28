# 30-Day ML Engineering Practice

A 30-day practice project where I learn data cleaning, model training, and deployment step by step. This README covers only the work that is done.

## Current status
Day 1 of 30 complete.

## Structure
- `Day01/`: Day 1 notebook (pandas on Titanic, Python test)

## Day 1: Pandas on Titanic
**Dataset:** Titanic passenger data, loaded with seaborn (`sns.load_dataset("titanic")`). 891 rows, 15 columns.

- Checked missing values: `age` 177 (20%), `deck` 688 (77%), `embarked` and `embark_town` 2 each.
- Filled missing `age` with the median of each passenger class, because 1st class passengers were older on average.
- Decided to drop `deck` for modeling: 77% missing and strongly linked to passenger class.
- Python exercise: function to average marks. Empty list and missing marks both return `None`, so they are not mistaken for a real score.

## Day log

| Day | What I did | What I learned |
|-----|------------|----------------|
| 1 | Pandas EDA on Titanic: missing values, class-wise median fill, groupby analysis. Python edge-case function. | Missing data needs a pattern check, not just a count. |
