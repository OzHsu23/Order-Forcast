# Order-Forecast
### DataSet:https://www.kaggle.com/felixzhao/productdemandforecasting/kernels 
I clean it  and choose the biggest warehouse:Whse_J for our forecast data: Whse_J_sort_out_index.csv

### The loss function : Symmetric mean absoulte precentage error(SMAPE)

### At first, I tried the navie forecast to predict the product:Category_007-Product_0138 on  next month, next two months, and next three months.
The best is next three months:SMAPE:59.09(Baseline)

### Second, I used stateful LSTM to predict same product on next month, next two months, and next three months.
The best is next three months:SMAPE:44.84(It's better than our baseline)
