# Order-Forecast
### DataSet is from https://www.kaggle.com/felixzhao/productdemandforecasting/kernels and I clean it and choose the biggest warehouse:Whse_J for our forecast data

### The loss function : Symmetric mean absoulte precentage error(SMAPE)

### At first, I tried the navie forecast to predict the next month, the next two months, and the next three months.The best is next three months:SMAPE:59.09(Baseline)

### Second, I used stateful LSTM to predict the next month, the next two months, and the next three months.
The best is next three months:SMAPE:44.84(Baseline)
