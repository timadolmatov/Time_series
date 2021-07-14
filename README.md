# Данные
Мы имеем данные от компании «Чётенькое такси» о заказах такси в аэропортах. 
- часы (по дате);
- количество заказов такси в час.
# Задача
Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания.Значение метрики RMSE на тестовой выборке должно быть не больше 48.
# Библиотеки
- *pandas*
- *math (sqrt)*
- *sklearn*
  - *train_test_split*
  - *LinearRegression*
  - *DecisionTreeRegressor*
  - *mean_absolute_error*
  - *mean_squared_error*
  - *StandardScaler*
  - *TimeSeriesSplit*
- *statsmodels*:
  - *seasonal_decompose*
  - *adfuller*
- *seaborn*
- *statsmodels.tsa.stattools (adfuller)*
