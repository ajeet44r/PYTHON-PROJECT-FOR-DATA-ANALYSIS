# PYTHON-PROJECT-FOR-DATA-ANALYSIS
Performed EDA using Pandas , Matplotlib and Seaborn libraries
Improved customer experience by identifying potential customers across different states ,occupation , gender and age groups 
Improved sales by identifying most selling product categories and products which can help to plan inventory and hence meet the demands 

PROJECT DETAILS :

* PYTHON DIWALI SALES DATA 

>IMPORTING LIBRARIES here i have used different libraries like 
 numpy , pandas ,matplotlib ,seaborn 

>IMPORTING CSV FILE then i have to import csv file which is 
 diwali sales data 

>here a company given data of diwali sales and they want that we 
 analyse there data for every columns and values and share a 
 summary so that they enhance their customer experience 

>improve customer experience by analyzing sales data

>increase revenue

>df.shape - it shows how many rows and columns

>df.head()

>df.info() - it will give all information that how many rows and 
             columns and also gives the detailed about the columns

>DATA CLEANING - removes null values , renames the columns name 
                 df.drop() ,to delete the columns which contains null values 
                 pd.isnull(df) -to check the null values 
                 pd.isnull(df).sum() it will give the sum of null 
                                      values in every columns
                 df.dropna() to remove null values 
                 df['columnname'] = df['columnname'].astype('int') to change the datatype of the column
                 df['columnname'].dtypes
                 df.columns
                 df.rename(columns={'previous colname':'newcolname'})
                 df.describe()- description of the data                 
   
>EDA -then exploratory data analysis on different values and columns
       
     *using countplot and barplot i can see here that on the basis of 
      gender column ,female purchasing order is more as compared
      to male 

     *using countplot and barplot i can see here that on the basis of
      age column , most of the buyers are of age group b/w 26-35yrs female

     *using countplot and barplot i can see here that on the basis of 
      state column , most of the orders are from UP ,MAHARASTRA and 
      KARNATKA respectively

     *using countplot and barplot i can see here that on the basis
      marital status ,most of the buyers are married(women) and 
      they have high purchasing power

     *using countplot and barplot i can see here that on the basis
      occupation column , most of the buyers are working in IT, 
      AVIATION and HEALTHCARE SECTOR

     *using countplot and barplot i can see here that on the basis
      product category column , most of the sold product are from 
      FOOD , FOOTWEAR and ELECTRONICS category

>CONCLUSION -
      married women age group 26-35 yrs from UP,MAHARASTRA and 
      HEALTHCARE are more likely to buy products from FOOD,CLOTHING
      and ELECTRONICS category
