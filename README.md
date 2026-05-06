# IPL-Data-Analysis (2008 - 2023)
This is my first ever data analysis.
And I chose to analyse the matches and deliveries of IPL as this would be the perfect time for it since the 2026 season is going on.

## My analysis
Open the Jupyter Notebook file named `IPL_Data_Analysis.ipynb` to see the analysis I made on the matches and deliveries data of IPL (2008 - 2023).
The analysis I have covered are:
- **Team Performance** — Total matches won by each team across all seasons
- **Batting Analysis** — Top 10 Run Scorers across all seasons
- **Bowling Analysis** — Top 10 wicket-takers across all seasons
- **Win Percentage** — Batting first vs Chasing
- **Venue Analysis** — Most successful venues by average runs scored
- **Toss Analysis** — Impact of toss decisions on match outcomes
*Note: All the analysis I made are based on the data of the IPL seasons between 2008 and 2023*

## Tools used
| Tool | Purpose |
| - | - |
| Python | Core programming language |
| NumPy | Numerical operations |
| Pandas | Data loading, cleaning, and manipulation |
| Matplotlib | Base visualisations |
| Seaborn | Statistical visualisations and styling |
| Jupyter Notebook | Development and presentation environment |

## Insights & Conclusion
From the analysis, we can see that
- **Mumbai Indians** and **Chennai Super Kings** are the most dominant teams in IPL history, leading the chart for total match wins.
- **Virat Kohli** and **Shikhar Dhawan** top the run-scoring charts, showing incredible consistency across seasons.
- Spinners and experienced pacers like **Yuzvendra Chahal**, **Piyush Chawla**, and **Lasith Malinga** dominate the highest wicket-takers list.
- **Chasing is generally more advantageous**: Teams batting second (chasing) have won ~53% of matches, while teams batting first won ~47%.
- Venues like **Brabourne Stadium** and **M Chinnaswamy Stadium** are highly favorable for batting, boasting the highest average innings scores.
- Teams winning the toss and choosing to **field first** have a slightly higher match-win probability compared to those choosing to bat first.

## Source
I took the `deliveries.csv` and `matches.csv` datasets uploaded by *Prateek Bhardwaj* on Kaggle.
Link for the datasets: "https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020"
