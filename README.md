# Japan-Analysis

資料集：針對日本各都道府縣（縣市級行政區）的人口遷移行為進行分析的資料集，具備時間序列 + 各縣交叉分析（Panel Data）的結構。
- 時間範圍：2006～2018年
- 地理單位：日本47個都道府縣
- 目標變數：人口淨遷移率

1. 應用 XGBoost Regression、PCA、Random Forest 和 Lasso 進行特徵篩選
2. 以 XGBoost、Linear Regression、LSTM 作為模型預測，並以 RMSE 和 MAPE 作為評估指標
