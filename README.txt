We have implemented prophet to predict the real-time daily sales and purchases figure for each item through time series forecasting

'Prophet.ipynb' contains charts, diagrams and extra implementation of holidays

'sales_loop.ipynb' generates daily sales figure in 'sales_predict.xlsx' which is in turn used to generate 'SPU_optimized_orders.xlsx' 
with 'SKU_SPU.ipynb' which shows how much each restaurant should be ordering per day to minimise wastage

'purchase_loop.ipynb' generates daily purchase order placements according to the chef's decisions which is used in 'Answer Sheet.xlsx'

'data_analysis.ipynb' contains exploratory data analysis that we have performed on the data given before deciding on our model

video demo contains our gui demo
https://purchase-dashboard.herokuapp.com/

We played around with the parameters and figure out that having training data up to Nov 2020 helps to improve predictions on Dec 2020, 
compared to if we are using yearly trends

The difference in actual and predicted data is due to covid trends and abrupt circumstances that affect the chef's decisions that 
do not follow a regular pattern

The predictions can be more accurate if the data regarding inventory and perishability can be given

