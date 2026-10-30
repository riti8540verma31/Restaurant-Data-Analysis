# Restaurant Data Analysis

Exploratory data analysis (EDA) of a restaurant dataset with 9,551 restaurants across 141 cities, completed as part of the Cognifyz Technologies Data Analyst internship (Levels 1 and 2).

## Tools
Python, pandas, Matplotlib, Jupyter Notebook

## Project Structure
```
Restaurant-Data-Analysis/
├── README.md
├── Restaurant_Data_Analysis_Report.pdf
├── Level1/
│   └── level1_tasks.ipynb
└── Level2/
    └── level2_tasks.ipynb
```

## Level 1: Basic Analysis
- Top 3 cuisines and the share of restaurants serving each
- City with the most restaurants and average rating per city
- Price range distribution (bar chart and percentages)
- Online delivery share and rating comparison with and without delivery

## Level 2: Advanced Analysis
- Rating distribution and the most common rating range
- Average votes per restaurant
- Most common cuisine combinations and which ones rate higher
- Restaurant locations plotted by latitude and longitude
- Restaurant chains: outlets, ratings and popularity

## Key Findings
- North Indian (41.5%), Chinese (28.6%) and Fast Food (20.8%) are the top cuisines.
- New Delhi has the most restaurants (5,473, about 57% of the data).
- Nearly half of the restaurants (46.5%) are in the lowest price range.
- Restaurants with online delivery average a 3.25 rating versus 2.47 without.
- Most rated restaurants score between 3 and 4.
- Votes are heavily skewed: mean 156.9 versus median 31.
- Restaurants cluster strongly in the Delhi NCR region.
- The largest chains (Cafe Coffee Day, Domino's, Subway) are not the highest rated or the most popular.

## Techniques Used
`groupby`, `value_counts`, `str.split` with `explode`, filtering unrated restaurants (rating 0), minimum-count filters, and bar and scatter plots.

## How to Run
```bash
git clone https://github.com/riti8540verma31/Restaurant-Data-Analysis.git
cd Restaurant-Data-Analysis
pip install pandas matplotlib jupyter
jupyter notebook
```
Open `level1_tasks.ipynb` or `level2_tasks.ipynb` and run the cells. Both notebooks read `dataset.csv` from the same folder.

## Report
See [Restaurant_Data_Analysis_Report.pdf](Restaurant_Data_Analysis_Report.pdf) for the methodology, findings and learning outcomes.
