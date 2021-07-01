# Time Series Prediction
Supply chain demand forecasting

---
## Summary

Demand forecasting is a crucial component in supply chain processes. It’s the essential factor that drives most of the supply chain decisions. It improves efficiencies, reduces waste, and optimizes inventories. Customer satisfaction is a very important metrics in retail industries, having enough to meet demands can improve customer satisfaction, thus increasing market shares. With the right demand forecasting methods, business performance (KPIs) can be improved. 

Demand forecasting is generalized as the use of existing data to predict the quantity of products in the future. Generally, more data leads to improved accuracy and better pattern recognitions. There are many demand-forecasting models in the industry. For example: traditional statistical methods such as time-series analysis as well as machine learning algorithms such as linear regression.

In this project, one method from each type is used to forecast the order quantities. **Moving Average method (MA)** and **Linear Regression (LR)** method are applied in this case. The purpose of this project is to predict order quantities for different materials based on historical clients’ orders histories. Date, client number, material number, and order quantity are given in a csv data file.

The data will be imported into an ipynb notebook. Exploratory data analysis will be performed to visualize the order quantity trends and distribution. Then two methods will be coded so the below function can be achieved:

The user can enter any given date, client number and material number, the models will return a suggested order quantity or also known as the forecast value.  If the user only enters the date and material, the prediction will be based on the aggregated sum forecast of this material from all clients. If the user only enters date and client, the prediction will be based on the aggregated sum forecast of all materials from this client. If the user enters all parameters: date, client, and material, then forecast will then be based on all available data. 

---
## How to use

The function user_func is for the user to interact with the program we have developed. Both the moving average method and the linear regression method are wrapped in the same function, and the user can select which one s/he would like to use. Note that the user_func makes predictions based on the entire dataset.

To start, users can type in user_func() in the coding block and run the block. The program prompts the user to enter what prediction method is preferred, client number, material number and date that they wish to make a prediction of. If any of the information is not incorrect, then the program will print the reason why they are incorrect, and prompt the user to re-enter the information. If all information are correct, the program will print the prediction result.
