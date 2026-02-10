# nsfg-statistical-analysis


This project works with a public health dataset from the National Survey of Family Growth (NSFG), a large study conducted in the United States that contains pregnancy and birth data from 2002. Each row in the dataset represents one pregnancy, which makes it useful for exploring trends related to pregnancy outcomes and birth characteristics.

The goal of this project was to work with a large dataset, apply statistical analysis using Python, and explore relationships between different variables through visualization.

### Dataset overview

The dataset includes information such as:
caseid, a unique ID for each respondent
prglngth, the length of the pregnancy in weeks
outcome, a code representing the pregnancy outcome (1 indicates a live birth)
pregordr, the order of the pregnancy for a respondent
birthord, the order of live births
birthwgt_lb and birthwgt_oz, the pound and ounce portions of birth weight
totalwgt_lb, the total birth weight in pounds
agepreg, the mother’s age at the end of the pregnancy

The dataset contains 13,593 rows and 244 columns and is publicly available for educational and research use.

### What I did in this project

I loaded and explored the dataset using Pandas, cleaned and processed the data, and handled missing values where needed. I calculated summary statistics such as mean, variance, standard deviation, and quantiles to better understand the data. I also created visualizations like histograms and scatter plots to look at distributions and relationships between variables.

I also built a linear regression model using the FemPreg dataset to explore the relationship between the mother’s age at pregnancy (agepreg) and birth weight (totalwgt_lb). The goal was to see whether maternal age had a measurable relationship with birth weight.

This project helped me build familiarity working with datasets and using Python for data analysis and reporting. It focuses on understanding the data, exploring patterns, and clearly presenting results.


### Tools used

Python,
Pandas,
NumPy,
Matplotlib.

