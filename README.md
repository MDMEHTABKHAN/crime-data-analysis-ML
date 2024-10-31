# Predicting-Crime-in-Toronto
Using data sourced from the Toronto Police (http://data.torontopolice.on.ca/pages/open-data), I construct a multi-class classification model using a Random Forest classifier to predict the type of major crime committed based on time of day, neighbourhood, division, year, month, etc. The dataset includes every major crime committed from 2014-2017* in the city of Toronto, with detailed information about the location and time of offence. The data contains only categorical variables so the modeling process tests both numeric encoding and OneHot encoding, with some improvement with the latter approach. 

The model performs reasonably well on F1-score (precision and recall) for a five-class classification problem. Though the data set is somewhat unbalanced towards assaults (higher volume), balancing class weights does not materially impact model performance.

# Project: Crime Data Analysis Using Machine Learning
Description: Developed a machine learning model to analyze and predict crime patterns based on historical data. Leveraged Python and data analysis techniques to classify criminal incidents by type, time, and location, providing law enforcement agencies with actionable insights to enhance response strategies and prevent criminal activities.

# Skills and Technologies Used:

Machine Learning Algorithms: Decision Tree, Naive Bayes, Logistic Regression, k-Nearest Neighbor, Ensemble Methods <br>
Data Analysis & Processing: Data wrangling, feature engineering, and exploratory data analysis using Pandas and NumPy <br>
Data Visualization: Insights and patterns visualized using Matplotlib and Seaborn <br>
Front-End Design: Created a simple, interactive interface with HTML, CSS, and JavaScript for report viewing <br>
Database Management: Organized and stored data with MySQL <br>
Version Control: Managed codebase with GitHub <br>
Impact: Enabled efficient crime pattern analysis, helping identify crime hotspots and support law enforcement decision-making with data-driven insights. <br>

