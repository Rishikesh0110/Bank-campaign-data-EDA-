
# Exploratory Data Analysis on Bank Marketing Dataset

Finded the best strategies to improve for the next marketing campaign. How can the financial institution have a greater effectiveness for future marketing campaigns? Inorder to answer this,we have to analyze the last marketing campaign the bank performed and identify the patterns that will help us find conclusions inorder to develop future strategies.



## About the data
DataSetInformation: https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset
This data set extracted from kaggle.com
## Used tools and techniques to perform this EDA
For withdraw insights from the data ,we must have the following python liberies installed to analyse data deeply.

Numpy: NumPy (Numerical Python) . https://numpy.org/doc/stable/user/absolute_beginners.html

Pandas: https://pandas.pydata.org/docs/

Seaborn: https://seaborn.pydata.org/

Matplotlib: https://matplotlib.org/

Sklearn: Simple and efficient tools for predictive data analysis https://scikit-learn.org/stable/

Google Analytics Colab
## Questions that derived
1. How many peoples took part in last campaign, and how many males and females among them?
2. What is the profession of the people who took part in campaign & How many are unemployeed & students?
3. Marital status of people like who are marrid ,Unmarried & Divorece?
4. How many defaulters there who took part in campaign?
5. What is the education level of the peoples, And how many peopls have housing loans or any type of laons?
6. Which of months are best for campaign?
7. The number of people who took deposit as yes or as no.
There are more verirty of similer kind of Questions which are answered in the notebook ,which definatly help marketing team to implant new effective strategies for next campaigns?
## Method and techniques
1. **Loaded the required libraries**
1. Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn
3. **Load the dataset**
1. By help of pandas as pd.read_filetype("Path_name"),load the dataset.
2. Reat the first 5 rows and last 5 rows by help of head() and tail() functions.
4. Stistical anlysis of data**
1. After checking lenght and columns of dataset i did the Stistical analysis by help of describe() function for both numerical and categorical columns which give 5 point analysis.
2. Than checked shape of data to get the actual lengh of rows and columns
3. Than Checked stistical analysis for string or categorical columns bu df.describe(include="O")
4. Than also returns the each column names and stored as list seperatly as categorical columns and numerical colums.

5. **Exploratory data analysis**
So after extracting the structure of data, Now started the EDA part to mining the data by visualization of each columns.

6. Ananlysis of each numerical columns and categorical columns to derive insights by using diffrents pandas and numpy functions, which able to give us the different usefull insights.
7. By help of Histogram, Distribution plot , Box plot i successfully derived insights about each numerical columns , and by help of pie charts & count plots able to visualize categorical columns indivisually.
8. After combining numerical and categorical columns by help of bar diagrame, scatter plot, line plot, successfully extracted insights from data.
9. Visualiing those insights to make it interactive by diffrent techniques of Seaborn and Matplotlib by charts such as Histogram,Distribution plot ,Box plots for each nuerical columns and countplots for each categorical colums.

10. Sucessfully derive all the possible insights from the data with multiple trends ,that how the bbuisiness is going and how we can improve in functions.

11. Tried to derived correlation b/w some of columns to find relationships by using Heatmaps and regplots.

#**Data wranggling**
13. **Handled mssing values**
14. Removing np.nan values of missing values by replecing with specific mean or median of the column.
15. **Dropping duplicates**
16. Than checked for duplicates by trying to find the shape of dataset again after applied drop_duplicates().
17. **Outliers handling**
18. Than handled outliers for each numerical columns the make the data more accurate and need to set the column to represent by their mean.
#**Standrization**
19. Standrization of each categorical and numeical columns that can help us in model building part.
20. Handling columns of Standrization of each numerical and categorical columns

21. Than handled categorical columns by One hot encoding pd.get_dummies() and numerical columns by minmax scaler and stadard scaler to standarize numerical columns.
## Conclusion
Luckily , we have such tools, by using them i perfomed and extracts such factors which can definatelly help campaign team to perform better in next campaign.