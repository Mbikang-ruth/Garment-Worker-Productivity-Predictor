# Garment-Worker-Productivity-Predictor
This code was developed to help predict the productivity of workers in a garment factory given certain features. Based on the training of over seven Machine Learning models, the predictor was developed based on the model with the least error.

This project aims to build a machine learning model that predicts productivity levels of garment workers based on various operational factors within a manufacturing setting. 

By analyzing features like work-in-progress, overtime, incentives, and team dynamics, we have developed models to predict continuous productivity values.

This shall help businesses improve their workflow efficiency and resource management.

With regards to this project we have worked on the dataset provided by Hubblemind having over 14 columns and 1,197 rows. Using python, we have performed some analysis on the dataset relating to Garment worker productivity and we intend providing insights that could benefit the industry.

Code and new dataset can be accessed through this link: https://drive.google.com/drive/folders/1ifii1rsFNsnU5t4XDjl1Q0mZ8nVbI1ns?usp=sharing
   
    
# To Conclude

- The aim was to develop an ML-based predictive system to forecast garment worker productivity.
  
- The process involved data exploration, cleaning, feature engineering, model selection, and evaluation.
  
-  We evaluated models including Linear, Ridge, Lasso, Random Forest, Gradient Boosting, Support Vector Regressor, and XGBoost.
  
- Linear models showed limited performance compared to tree-based models like Random Forest, Gradient Boosting, and XGBoost that performed better, with **XGBoost** emerging as the **best model** due to its superior accuracy, random residual distribution, and lowest error metrics.
  
- The final predictive system, built using the optimized XGBoost model, allows users to input operational data and receive a predicted productivity level. This tool can help improve decision-making and resource management in garment manufacturing.
  
- In conclusion, the project successfully built a robust predictive system, with potential for further improvement through additional data, feature refinement, and hyperparameter tuning.
