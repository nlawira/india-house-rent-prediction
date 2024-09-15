# India's House Prices Prediction

## Preface
This self-initiated project improves my submitted project for the CB4247 Statistics & Computational Inference to Big Data module at NTU. After my initial project was graded, I sought my lecturer's feedback and incorporated it into this version of this project. This repository contains my project's code and report and showcases my machine learning, data analysis, pre-processing, Python, and report-writing skills.

## Project Overview
This self-initiated project aims to:
- Apply data analysis and visualization techniques to analyze a real-world dataset.
- Train machine learning algorithms on the chosen dataset, including Ordinary Least Squares Regression, Random Forest Regressor, and XGBoost Regressor.
- Conduct ANOVA and residual analysis to test the validity of Ordinary Least Squares (OLS) regression assumptions.
- Evaluate each algorithm's performance via metrics, including mean absolute error, root mean squared error, and R2.
- Identify critical variables via feature importance.
- Develop a robust and accurate model by combining high-performing algorithms.

This project used a dataset containing house prices in India for OLS regression analysis and training various machine learning models. The dataset can be found [here](https://www.kaggle.com/datasets/iamsouravbanerjee/house-rent-prediction-dataset) in Kaggle. Data pre-processing and thorough preliminary analysis were conducted before regression and training, removing outliers to reduce noise in the data and feature engineering to preserve information in the dataset. Afterward, OLS regression was performed on the dataset and residual analysis followed to verify the assumptions made by OLS. Next, various machine learning models were trained on the dataset. The best-performing models were selected, and feature importance analysis was done on them to determine the improvement of the model. Finally, the top-performing models were combined to perform a final test against the dataset for its performance.

Some of the graphs below comprise the analysis I conducted in this project.
![image](https://github.com/user-attachments/assets/4d341c53-0774-4751-ac0d-0eda6ad2896f)
**Figure 1** Distribution graphs of `Rent`
<br />
<br />
![image](https://github.com/user-attachments/assets/c227ee70-7cbc-40f9-9aa8-3b48e2c547da)
**Figure 2** Heatmap of numerical variables' correlations
<br />
<br />
![image](https://github.com/user-attachments/assets/901aa966-b584-4441-8e86-86941e11ea9b)
**Figure 3** Residual analysis of the OLS regression model
<br />
<br />
![image](https://github.com/user-attachments/assets/e682df97-83c0-4d4e-96a9-1563484496a1)
**Figure 4** Root mean squared errors of trained machine learning models
<br />
<br />
![image](https://github.com/user-attachments/assets/40dc380c-2355-43e9-970c-405dfd38de98)
**Figure 5** Feature importance graph of the CatBoost model

## Conclusion
The OLS regression analysis reveals that a OLS linear model does not fit the dataset well, with a R<sup>2</sup> value of 56.06% and RMSE of 3.54×10<sup>4</sup>. This is because preliminary and residual analysis reveals that the dataset exhibits non-linearity and existance of outliers. Regarding the machine learning models, CatBoost, Gradient Boosting, LightGBM, Random Forest, and XGBoost regressors performed the best amongst the others, exhibiting high R<sup>2</sup> values and low errors. However, the feature importance analysis conducted on these models revealed that feature selection did not improve the performance of the model. This conclusion was furhter validated by decreasing R<sup>2</sup> adjusted values before and after feature selection. Nonetheless, these five models were combined and tested on the original data, yielding a decently good result with an R<sup>2</sup> value of 77.54% and RMSE of 2.53×10<sup>4</sup>. Afterward, recommendations were suggested for future projects to improve the performance of machine learning models trained on this dataset.

## License
Protected under the MIT License. See `LICENSE` for more information.

## Contact me
Thank you so much for visiting my repository! I sincerely hope my project can help you in providing insights to regression analysis, machine learning models, and report writing! :smile:
If you would like me to explain my project further or contact me for any reason, you can email me below or connect with me on LinkedIn!

<a href="https://www.linkedin.com/in/nathan-lawira/" target="_blank">
  <img src="https://img.shields.io/badge/-LinkedIn-333333?style=flat&logo=Linkedin" alt="LinkedIn" style="height: 30px;"/>
</a>
<a href="mailto:nathanlawira@gmail.com" target="_blank">
  <img src="https://img.shields.io/badge/-Email-333333?style=flat&logo=Gmail" alt="Email" style="height: 30px;"/>
</a>
