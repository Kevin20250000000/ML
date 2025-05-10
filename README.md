## **Quant Trading - ML Using Support Vector Machine & Random Forest & and Neural Network**

### **Strategy Overview:**

1. Pair the 30 stocks in the Dow Jones Industrial Average and identify the 10 pairs with the highest cointegration (i.e., the smallest p-value) as investment targets.

2. Train a model using the Support Vector Machine (SVM) method and calculate the annualized return.

3. Train a model using the Random Forest (RF) method and calculate the annualized return.

4. Train a model using the Neural Network (NN) method and calculate the annualized return.

The average annual return from these three methods is then calculated for comparison.


### **Data:**
[DJI](https://github.com/Kevin20250000000/Quant-Trading-ML-Using-Support-Vector-Machine-Random-Forest-Neural-Network/blob/main/dji_stocks.csv)

[Top 10 cointegrated pairs](https://github.com/Kevin20250000000/Quant-Trading-ML-Using-Support-Vector-Machine-Random-Forest-Neural-Network/blob/main/top10_cointegrated_pairs.csv)


### **Strategies:**

### **I. Support Vector Machine (SVM)**
[SVM - Code](SVM)


#### **1. Top 10 Most Significant Cointegrated Stock Pair Spreads:**


![image](https://github.com/user-attachments/assets/ff6664c2-3dd4-4151-aaf0-b1b9d7534b52)


#### **2.The Heatmap of Top 10 Strongest Cointegrated Pairs**
![image](https://github.com/user-attachments/assets/ba776324-9c3c-4d31-87cb-945642ffccb0)



#### **3. The Mean Annualized Return of the SVM Model for the Top 10 Pairs is 59.02%.**


![image](https://github.com/user-attachments/assets/fd19b143-856f-4750-9e88-ef0673510f51)



#### **4. Cumulative Returns of SVM Strategy for Top 10 Pairs:**


![image](https://github.com/user-attachments/assets/1248e099-5dd7-43eb-bf61-184670116a75)



### **II. Random Forest (RF）**
[RF - Code](RF)

#### **The Mean Annualized Return of the Random Forest Model for the Top 10 Pairs is 59.54%.**


![image](https://github.com/user-attachments/assets/dbc12406-ed98-4acd-952b-9f9775165126)



### **III. Neural Network (NN)**
[NN - Code](NN)

#### **The Mean Annualized Return of the Neural Networkt Model for the Top 10 Pairs is 41.77%.**


![image](https://github.com/user-attachments/assets/ece90a88-798f-4aa9-9fb7-ec8e2dc683ab)









