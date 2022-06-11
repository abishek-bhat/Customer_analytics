# Customer_analytics
# 👩‍👩‍👦Customer Market Segmentation
Customer segmentation is the practice of dividing a company's customers into groups that reflect similarity among customers in each group. The goal of segmenting customers is to decide how to relate to customers in each segment in order to maximize the value of each customer to the business.

![image](https://user-images.githubusercontent.com/60037478/173194393-676fcac9-b754-4f21-8fc5-1938310613df.png)



### 🧐Attributes Description

Variable | Description
--------------|-----------
Variable |	Definition
ID |	Unique ID
Gender|	Gender of the customer
Ever_Married	|Marital status of the customer
Age	|Age of the customer
Graduated|	Is the customer a graduate?
Profession|	Profession of the customer
Work_Experience	|Work Experience in years
Spending_Score|	Spending score of the customer
Family_Size|	Number of family members for the customer (including the customer)
Var_1	|Anonymised Category for the customer

* Based on the attributes group Segment of the customer

## Context
An automobile company has plans to enter new markets with their existing products (P1, P2, P3, P4 and P5). After intensive market research, they’ve deduced that the behavior of new market is similar to their existing market.

## Content
In their existing market, the sales team has to classify all customers into different number of segments. Then, they can perform segmented outreach and communication for different segment of customers.

# 📌Concepts and Techniques used in the Project 

![image3](https://user-images.githubusercontent.com/65475928/123808512-732c8880-d90e-11eb-8a9e-8e4e5eb8543e.png)

## 🪁Data Wrangling
Data wrangling is the process of cleaning, structuring and enriching raw data into a desired format for better decision making in less time.
This includes - 
   - Basic Cleaning
   - Getting information about attributes
   - Data manipulation
   - Organising of Data

## 🪁Missing Values Treatment
If the missing data is Present in -
* Continuous variable feature - Fill Median or mean based on the distriution of feature variale
* Categorical Variable feature - Fill mode of the column in place of missing data

## 🪁Exploratory Data Analysis



**1. Variable Identification**
* Categorical 
     - Ordinal
     - Nominal
* Continuous 

**2. Univariate Analysis**
* For Categorical Variable - 
    - Count of data present in the dataset for particular variable
* For Continuous Variable - 
    - Find the Distribution of feature using Histogram
    - Outlier detection using Box Plot

**3. Bi-Variate Analysis**
* Categorical - Continuous Variables ---> Bar Graph
* Continuous - Continuous Variables ---> Scatter Plot to see relationship

**4. Outlier Detection**
* Box plot are the best statistical Measure for Outlier detection

**5. Missing value Treatment**
* Depending upon the dataset the missing value treatment can be done before EDA or after EDA process

## 🪁Data Preprocessing

**1. Feature Engineering**
* After analysing the dataset and based on the insights we add or remove some attributes so that our model performs good.

**2. Feature Encoding**
* Since the Machine learning model accepts only Numerical values so the categorical variables which have 'object' data types are converted into numerical values depending upon the type of variable
   - *Ordinal Categorical variable* - Label Encoding
   - *Nominal Categorical Variable* - One Hot Encoding

**3. Feature Scaling**
* Features are scaled to give the good output for some algorithms which depends on some similiarty function like - 
    - K-Means Clustering algorithm
    - K-NN algorithm
    - Principal Component Analysis 

## ✂Clustering Technique

* The K-means clustering algorithm is used to find groups which have not been explicitly labeled in the data. This can be used to confirm business assumptions about what types of groups exist or to identify unknown groups in complex data sets
* Find Number of Clusters - 
     - Using Elbow Method
     - Understanding Business requirements
   
*Note: here after applying K-means clustering we use Principal Component Analysis (PCA) technique*
 
 ## ✂Principal Component Analysis (PCA) technique
 * To Perform Dimensionality Reduction
 * Data Visualization
 
![image](https://user-images.githubusercontent.com/78917605/129529378-a4deeda1-5f8c-4b42-9fca-9c6a2a1bf672.png)
