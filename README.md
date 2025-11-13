##**Movie Financial Performance Analysis**

**Overview**

This project explores key factors influencing movie performance, such as genre, release timing, runtime, and production budget.
By analyzing multiple movie datasets, we identify what drives profitability and provide strategic recommendations for data-driven decision-making in film production.

##**Business Understanding**

The movie industry faces high production costs and unpredictable audience preferences.
Our goal was to determine which features contribute most to a movie’s success and how studios can optimize release strategies and budgets.

**Key Business Questions**

1. What trends exist across genres, release periods, and budgets?

2. What is the ideal runtime for a movie?

3. Can early popularity predict long-term success?

##**Datasets Used**
|Dataset                |   Description                                              |
| --------------------- | ---------------------------------------------------------- |
|tmdb.movies.csv	    | Movie details (id, popularity, release_date, vote_average) |
|bom.movie_gross.csv    |	Box Office Mojo data (domestic_gross, year)              |
|tn.movie_budgets.csv   |	Budget and worldwide revenue                             |
|clean_movie_basics.csv |	Movie basics including genre                             |
|rt.movie_info.csv      |	Rotten Tomatoes data (runtime, genre, rating)            | 

**Data Cleaning Steps**

- Removed missing and duplicate values

- Converted currency fields to numeric format

- Extracted year and month from release dates

- Calculated new metrics: profit, ROI, profit margin

- Handled outliers and missing runtimes or genres

**Key Metrics**

1. Profit = worldwide_gross - production_budget

2. ROI = (profit / production_budget) × 100

3. Profit Margin = (profit / worldwide_gross) × 100

4. Month = extracted from release_date

##**Analysis & Insights**

1. Release Month & ROI:

    - Highest ROI in May–July and November–December.

    - Early-year releases perform weakest.

2. Top Profitable Movies:

    - Few blockbusters dominate profits.

3. Runtime Distribution:

    - Ideal range: 90–130 minutes (~100 min).

4. Genre vs Runtime:

    - Action/adventure longer; drama/comedy shorter.

5. Early Popularity vs Success:

    - Popularity ≠ sustained profitability.

##**Conclusions**

- Mid-budget films ($30M–$100M) perform best.

- Timing of release strongly affects ROI.

- Ideal runtime: ~100 minutes.

- Early hype doesn’t ensure lasting success.

##**Recommendations**

- Release major films during summer or holiday seasons.

- Focus on mid-budget productions for better returns.

- Maintain runtimes around 100 minutes.

- Invest in long-term marketing, not just opening-week hype.

**Technologies Used**

Python (Pandas, Matplotlib, Seaborn, NumPy)

Jupyter Notebook

SQL

**Tableau Dashboard** : 


##**Team Members**

KARU Group 1:
Sheilla Macharia | Margaret Mondia | Benard Kariuki | Bravian Ashono | Isaac Ndung’u | Ibrahim Mohamud