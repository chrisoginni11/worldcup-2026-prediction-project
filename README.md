# 2026 FIFA World Cup Prediction Model

A data science project built in Python predicting the outcome of the 2026 FIFA World Cup using Monte Carlo simulation.

## What this project does

- Loads a dataset of all 48 qualified nations with FIFA rankings, World Cup titles, appearances, and squad depth scores
- Builds a weighted prediction model using historical performance and current form
- Runs 10,000 simulated tournaments using Monte Carlo simulation
- Visualizes win probabilities, squad depth, 2022 results, and my personal prediction vs the model

## My prediction

| Place | Nation |
|-------|--------|
| 🥇 Winner | Portugal |
| 🥈 Runner up | France |
| 🥉 3rd | Spain |
| 4th | England |

The model disagreed — it favored France and Brazil. The write-up in the notebook explains why I pushed back.

## Tech stack

- Python 3.14
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn

## How to run it

1. Clone the repo
2. Install dependencies: `pip install jupyter pandas numpy matplotlib seaborn`
3. Run: `jupyter notebook`
4. Open `worldcup_2026.ipynb` and run all cells

## About

Built by a D1 college soccer player learning data science — combining football knowledge with Python to see where the data and the eye test agree and disagree.
