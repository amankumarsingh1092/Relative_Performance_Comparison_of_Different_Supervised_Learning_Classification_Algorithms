# NTCC Summer Internship
# Relative_Performance_Comparison_of_Different_Supervised_Learning_Classification_Algorithms
This project aims to analyze and compare the predictive performance of various supervised learning classification algorithms using real-world financial and economic data. Stock prices, trading volumes, and exchange rates were sourced from reliable platforms like BSE, NSE, Bloomberg, RBI, Investing.com, and CMIE. The analysis was carried out using Python and includes feature engineering, model training, evaluation, and visualization.

## Objectives
* Collect financial and economic data from BSE, NSE, RBI, Bloomberg, Investing.com, and CMIE.
* Engineer technical indicators like daily returns, moving averages, and volatility.
* Train and evaluate multiple supervised learning algorithms:
** Logistic Regression
** Decision Tree
**Random Forest
**Support Vector Machine (SVM)
**k-Nearest Neighbors (k-NN)
**Naïve Bayes
* Assess models using metrics like Accuracy, Precision, Recall, F1 Score, and ROC-AUC.
* Visualize market trends and classification results.

## Data Sources
* BSE India
* NSE India
* RBI Exchange Rate Archive
* Bloomberg Terminal
* Investing.com
* CMIE India

## Machine Learning Models
The project includes comparison of six supervised classifiers on the task of predicting whether a stock’s price will go Up (1) or Down (0) on the next trading day:

* Random Forest: Best overall performance in terms of precision and robustness.
* Decision Tree: Highest recall and F1 Score — useful when capturing "Up" trends is critical.
* SVM and k-NN: Moderate performance, better with kernel and scaling tuning.
* Logistic Regression & Naïve Bayes: Performed poorly due to linear assumptions and correlated data.

## Visualizations
The following were plotted for stock analysis and model evaluation:
* Closing price trends (BSE & NSE)
* Moving Averages (30-day)
* Daily Returns & Volatility
* Correlation Heatmaps
* Histograms and Boxplots of returns
* ROC Curves & Confusion Matrices
* Monthly USD/INR trend analysis using RBI data

## Tools & Technologies
* Python
* Jupyter Notebook
* Libraries:
** pandas, numpy, scikit-learn
** matplotlib, seaborn
** datetime, os, warnings

## Key Insights
* Random Forest was the most reliable for real-world financial forecasting.
* Decision Tree captured more upward trends but risked overfitting.
* USD/INR analysis showed a consistent rupee depreciation trend, with possible RBI interventions.
* CMIE and Bloomberg data enriched contextual understanding with macroeconomic indicators and firm-specific fundamentals.

## References
* Eligo, W. M., et al. (2022). Comparing Supervised ML Algorithms on Classification Efficiency.
* Patel, J., et al. (2015). Predicting Stock Movement Using Technical Indicators.
* Huang, W., et al. (2005). Stock Forecasting using SVM.
* Dash, M., & Dash, P. (2016). ML for Stock Market Trend Prediction.



