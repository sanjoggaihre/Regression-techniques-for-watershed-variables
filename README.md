## Various Regression Techniques
In this repository, a regression model is developed to predict the target variable, mean.gw.nit, using other input variables. Several regression techniques are applied to identify the most optimized model. Basic data processing steps, such as categorical encoding and normalization, are performed to ensure faster model convergence.

For model evaluation, **Root Mean Square Error (RMSE)** and **Mean Absolute Error (MAE)** are used as metrics to assess performance. After comparing different models, it was concluded that** RandomForestRegressor** performs best and is the most optimized model for this dataset. A comparison of the models is presented below:
 
 ![models](https://github.com/user-attachments/assets/9c5842db-a81e-47a7-85ff-ed3415631424)
 
After applying Hyperparameter tuning to the Random Forest Regressor, the model's performance improves, yielding an RMSE of approximately **4.908285.**

![Screenshot 2025-02-09 203920](https://github.com/user-attachments/assets/8d4d19d8-9e00-49d6-82f9-455ecf63124e)

Furthermore, MLPRegressor from sklearn is also used to train the model, which resulted in an RMSE of approximately **5.21943**

![Screenshot 2025-02-09 203920](https://github.com/user-attachments/assets/17f910f5-faec-4b90-a5b3-3f017f5b9233)

Additionally, a Neural Network was used to train the model on the dataset, which resulted in an RMSE of approximately **5.053476.**

![Screenshot 2025-02-09 203920](https://github.com/user-attachments/assets/dfc033ca-dd2f-4e49-954f-0d689a7175d8)
