#### Analysis-of-electrical-power-consumption-for-individual-households   

## **Abstract:**
**Dataset Title: Individual household electric power consumption Data Set**    
**URL: https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption**   

This archive contains 2075259 measurements gathered in a house located in Sceaux (7km of Paris, France) between December 2006 and November 2010 (47 months).   

**Notes**:  
1.(global_active_power*1000/60 - sub_metering_1 - sub_metering_2 - sub_metering_3) represents the active energy consumed every minute (in watt hour) in the household by electrical equipment not measured in sub-meterings 1, 2 and 3.   
2.The dataset contains some missing values in the measurements (nearly 1,25% of the rows). All calendar timestamps are present in the dataset but for some timestamps, the measurement values are missing: a missing value is represented by the absence of value between two consecutive semi-colon attribute separators. For instance, the dataset shows missing values on April 28, 2007.

**Problem Statement:**: Use of time series data by performing regression and clustering to detect correlation among time, voltage imbalance, waste power and the energy usage for different types of appliances used in a household.

**Data Set Information:** 

Number of instances: 2075259   
Number of Attributes: 9  
Data Set Characteristics: Multivariate, Time-Series   
Attribute Characteristics: Real    
Associated Tasks: Regression, Clustering  

The repository contains executable python program performing machine learning LSTM Methods for acheiving the prediction.
