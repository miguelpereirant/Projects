## **Categorical Feature Encoding Challenge II**

This dataset on Kaggle is a criative and didatic way to perform various skills of machine learning, such as feature encoding of binary, nominal, ordinal features
and cyclical, low or high cardinality.
The goal is reach best acurracy with creative feature engineering and best pratice of classifier techniques.

### **• File Description**

___

train - train dataset

test - test dataset


### **• Columns Description**

___

Binary Features: bin_0; bin_1; bin_2; bin_3; bin_4.

Nominal Features: nom_1; nom_2; nom_3; nom_4; nom_5; nom_6; nom_7; nom_8; nom_9.

Ordinal Features: ord_0; ord_1; ord_2; ord_3; ord_4; ord_5.

Cyclical Features: day; month. 


### **• Exploratory Data Analysis**

___

The cleaning process was made starting with de identification of null values per column, after that a couple of null visualizations (heatmap and missingno matrix)
for better unsderstanding. This time, i choose to fill columns with mode all features.

Also, i did an correlation analisys on a heatmap, and for each type of feature, an independent distribution analisys.


### **• Pre Processing and Data Treatment**

___

Null values re-check. No need to drop any variable.

Normalization and Label Encoder required.


### **• Training and Evaluation Model**

___

For this project I've used the following algorithms: Logistic Regression, Random Forest and XGBoost.

The last method was chosen due to the best peformance, therefore the one submitted on Kaggle.
