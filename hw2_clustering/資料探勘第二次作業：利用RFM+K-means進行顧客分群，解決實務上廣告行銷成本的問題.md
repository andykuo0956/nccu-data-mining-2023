# 資料探勘第二次作業：利用RFM+K-means進行顧客分群，解決實務上廣告行銷成本的問題

## 構想動機：



## 文本介紹：
資料來源：UCI Machine Learning Repository 的 Online retail.csv

資料集介紹：Online retail is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

資料筆數：541909
特徵數：6,包括 IovoiceNo,StockCode,Description,Quantity,InvoiceDate,UnitPrice,CustomerID

## Data Preparation：
Step1 : 移除資料中缺失值
Step2 : 計算每個顧客的Recency,Frequency,Monetary值
Step3 : 移除outlier值
Step4 : 進行正規化，減少資料之間的將不同特徵的數值範圍縮放到相同的尺度或範圍來提高模型的性能

## Data Analysis：
1. Model採用K-means
2. 利用兩種方法決定最適合的分群數量K:Elbow-curve and Silhouette analysis -> 適合分3群


## Data Visualization：


