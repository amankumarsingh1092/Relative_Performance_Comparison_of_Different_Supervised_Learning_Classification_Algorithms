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
## Model Outputs & Visualizations
![Picture38](https://github.com/user-attachments/assets/fcfdccb5-223d-40e7-86f7-ce4347c190d7)
![Picture39](https://github.com/user-attachments/assets/194019fe-a8b7-4883-a56e-b34020e3941f)
![Picture41](https://github.com/user-attachments/assets/a0a5069d-b199-4aaa-b2f6-6d63c6f2d201)
![Picture42](https://github.com/user-attachments/assets/5409dae9-5eb8-4e42-bea3-ce517f00b4c6)
![Picture43](https://github.com/user-attachments/assets/78634186-9b16-4848-a4f9-6c0cc1a431d7)
![Picture44](https://github.com/user-attachments/assets/bb632498-1ba0-40b6-af45-ed23434e6bc9)
![Picture45](https://github.com/user-attachments/assets/69e4c971-542d-4fe2-ac1b-865a4b95f0ed)
![Picture48](https://github.com/user-attachments/assets/c8eb3327-99b8-42e6-8254-7c34f4dc13fd)
![Picture46](https://github.com/user-attachments/assets/6290a254-2818-4e6b-b1e2-a812073b8788)

## Data Sources
* BSE India
* NSE India
* RBI Exchange Rate Archive
* Bloomberg Terminal
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
   pandas,
   numpy,
   scikit-learn,
   matplotlib,
   seaborn

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
## Author
* Aman Kumar Singh
* www.linkedin.com/in/aman-kumar-singh-71a090206
* aksingh1652@gmail.com


