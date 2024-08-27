## 🚖 **Taxi Orders Forecasting Project**

### **Project Objective**
The objective of this project is to build and train a machine learning model that can forecast the number of taxi orders in the next hour. The goal is to help the client, ABC, a taxi service provider, anticipate periods of high demand so they can deploy more drivers during peak hours and better satisfy customer demand.

### **Project Description**
The client, ABC, wants to understand the time periods during the day when the number of taxi orders increases. This information will enable the company to attract more drivers during peak hours, ensuring they can meet demand. The project focuses on developing a reliable machine learning model to predict the number of taxi orders for the upcoming hour.

### **Data**
The project utilizes archived data provided by the client, which includes historical taxi order information. The data is resampled by the hour to train the model effectively. The dataset can be accessed [here](https://github.com/ybezginova2016/03_LA_TaxiOrders/blob/main/taxi.csv).

### **Project Methodology**
1. **Data Resampling:** The data is resampled by the hour to create a time series suitable for forecasting.
2. **Data Splitting:** The dataset is split into training, validation, and test samples to evaluate the model's performance.
3. **Model Training:** Various machine learning models are trained with different hyperparameters.
4. **Model Selection:** The best-performing model is selected based on the Root Mean Square Error (RMSE) metric.
5. **Conclusions:** Recommendations are made based on the model's performance, considering both complex and simpler forecasting methods.

### **Quality Metric**
- **RMSE (Root Mean Square Error):** The target value for RMSE is less than or equal to 48, as agreed with the client.

### **Project Outcomes**
- The best model is **Linear Regression** with an RMSE of 45.45.
- The project demonstrates that while complex models like lightGBM can achieve better RMSE scores, simpler models like Linear Regression are worth considering for time series forecasting due to their interpretability and lower complexity.

### **Key Python Libraries**
- `numpy`, `pandas`, `lightgbm`, `seaborn`
- `sklearn.ensemble`
- `sklearn.tree`
- `sklearn.linear_model`
- `sklearn.metrics`
- `sklearn.preprocessing`

### **Code**
The complete code for the project, including data preprocessing, model training, and evaluation, can be found in the Jupyter notebook [here](https://github.com/ybezginova2016/03_LA_TaxiOrders/blob/main/03_LA_taxi_orders_main.ipynb).

### **Feedback**
Your comments and questions are welcome at `ybezginova2021@gmail.com` and on Telegram [@yu_bezginova](https://t.me/ybezginova).
