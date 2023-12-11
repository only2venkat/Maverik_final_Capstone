## Business Problem and project Objective :
A retail convenience chain, Maverik, fuels adventures in more than 380 locations across 12 western states. Maverik is known for premium BonFire food, diesel and unleaded fuel, and in-store merchandise. The company is on an expansion spree and as part of its growth, it recently acquired “ Kum & Go” nearly doubling its store count.
The company is planning to open 30 new stores yearly in a new market, and it needs to forecast daily sales for the new store. This is crucial for financial planning and return on investment (ROI) assessment for these new stores. 
The challenge lies in predicting the first-year sales for these newly acquired stores accurately. By using currently available historical dataset to address analytical problems , the objective is to identifying trends and patterns in sales data, understanding the relationship between sales and other factors, and identifying outliers and anomalies. By addressing these analytical problems, we plan to build a sales forecasting model.
## Our Solution:
We have developed a sales forecasting model that can accurately predict daily sales for the new store. for any given number of days from the store opening days. We have used a variety of forecasting methods, such as XGB model, Prophet model, ARIMA/SARIMA Models and ETS model. The model performances are evaluated by comparing its prediction to actual sales data from a holdout dataset. We have also prepared the performance indices in line Maverick benchmark indices and observed to be very good. Each model is evaluated with industry-standard metrics such as Forecast Accuracy Metrics (e.g. MAE, MAPE, RMSE) and its ability to update forecasts dynamically in response to new data.
## My Contribution to the project:
I have actively contributed for the successful completion of project at all stages from EDA to model development to final presentation. I have performed various EDA activities such as time series dataset cleaning and enriching, Store features dataset cleaning , creation of  merged dataset, label encoding, identification of correlations and finding out the top contributing factor for each target variable. 
## The business value of the solution:
Our forecasting solution holds several advantages for Maverik. It allows the company to allocate resources efficiently, optimize staffing and inventory management, and make data-driven decisions about marketing and promotions. By creating precise financial plans and ROI documents, Maverik can confidently evaluate the return on its investments in new stores, ensuring a more informed and strategic approach to expansion.
## Difficulties we encountered along the way.
Creating a time series model for sales forecast presented both challenges and valuable learning opportunities. While we achieved favorable metrics compared to benchmark values in predicting sales, we faced several obstacles. Initially, understanding the dataset and business objectives took a substantial amount of time. Additionally, developing a model for each of the four target variables posed a significant challenge. Feature engineering proved to be demanding due to substantial variability in the fields. Experimenting with different models was time-consuming, and clustering the stores based on their characteristics proved to be quite challenging.
## Learnings from the project
The time-series models offered valuable insights into managing intricate datasets, feature engineering, and understanding time series modeling concepts. We acquired proficiency in evaluating models through pertinent metrics and grasped the nuances of hyperparameter tuning. Furthermore, the practical implementation of the model showcased its tangible impact on enhancing risk management strategies and generating sales forecasts for efficient budgeting. These lessons will serve as a guiding framework for future projects, enabling the precise and effective application of predictive analytics to address diverse business challenges in various industries.
