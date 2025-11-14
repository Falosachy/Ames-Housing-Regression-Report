**Ames Housing Price Regression**

Predicting residential home sale prices in Ames, Iowa (2006–2010) using a Random Forest model.

**Project Overview**

Over the past decade, the nuances of the housing market have fascinated data enthusiasts and real estate professionals alike. In this project, we delve into the classic Ames Housing dataset (Dean De Cock, 2006–2010), examining over 80 features that describe home characteristics, and build a regression model to predict sale prices.
By carefully cleaning, imputing, and engineering features, and then training a Random Forest regressor, we aim to provide buyers, agents, lenders, and city planners with a data-driven edge in pricing decisions.

**What You’ll Find Here**

•	Data Wrangling: Dropped low‑value identifiers and poorly populated columns (e.g., Alley, Fence). Imputed missing values by median, constant, or domain‑informed defaults.

•	Feature Engineering: Created House_Age from Year_Built. Encoded all categorical variables for seamless modeling.

•	Modeling & Evaluation: Train/validation split (80 %/20 %) for honest performance estimation. Random Forest regressor achieving ~6 % scaled RMSE on held‑out data.

•	Exploratory Visuals: Living Area vs. Price scatter and Quality rating vs. Price box plots.

•	Key Insights: Larger living areas and higher quality ratings are strong price drivers. Thoughtful imputation and pruning of low‑signal features are critical to model accuracy.

**Getting Started**

1.	Clone the repo: git clone https://github.com/your‑username/ames‑housing‑regression.git && cd ames‑housing‑regression
2.	Install dependencies: pip install -r requirements.txt
3.	Run the data pipeline: python src/data_wrangle.py
4.	Train the model: python src/train_model.py
5.	Evaluate & visualize: python src/evaluate.py
   
**Contributing**

7.	Fork this repository and create a feature branch (`git checkout -b feature/YourIdea`).
8.	Commit your changes (`git commit -m "Add awesome feature"`).
9.	Push to the branch (`git push origin feature/YourIdea`).
10.	Open a pull request and share your thoughts!
    
**License**

This project is released under the MIT License. Feel free to adapt and build on it, just remember to give attribution!

