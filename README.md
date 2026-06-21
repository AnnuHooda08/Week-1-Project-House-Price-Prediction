House Price Prediction

Week 1 internship project — predicts house prices from property features using regression, and identifies which features matter most.

Dataset

Housing Prices Dataset (Kaggle, by yasserh) — 545 rows, 13 columns.

Structure

analysis.ipynb     # Full notebook: cleaning, modeling, visualization
Housing.csv         # Dataset
summary.docx         # 1-page findings summary
charts/               # 3 chart PNGs

Approach

Cleaned data → encoded categorical features → trained Linear Regression & Random Forest → compared performance → visualized results → summarized insights.

Results

ModelMAERMSER²Linear Regression970,0431,324,5070.653Random Forest1,014,9471,399,7690.612

Top price drivers: area, bathrooms, air conditioning.

Tools

Python, Pandas, Scikit-learn, Matplotlib/Seaborn, Jupyter.
