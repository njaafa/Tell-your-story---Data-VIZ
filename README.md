
Telling a story with your data should arguably take precedence over anything else. 

The best insights, dashboards, charts and machine learning models will not create impact unless you are able to effectively communicate with your stakeholders. 

In this mini project/task, i'll re-create a chart to understand the mix of the most profitable companies in the Fortune 1,000,i.e., Which industries are the most prevalent?” -

Original chart and notebook by Data Science Dojo https://datasciencedojo.com/ as curated and presented by Gregory Kamradt https://www.linkedin.com/in/gregkamradt/

## Project steps
1. import pandas and plotly.express libraries to help deal with tabular data and chars respectively 
2. In order to access the Fortune 1K dataset, I used the .read_csv() method to import the file from it's online respository in google drive
3. Used df_full.head() to preview the imported dataset
4. Sliced the returned dataset to pull up only the columns to be used in the chart 
5. Selected colums included: 'company', 'revenue', 'profit', 'sector', 'Market Cap'
6. Created two extra columns ('color' and 'is_top_industry') to assist in colors and labels to be used in the chart 
7. created the chart using the plotly.express package
8. Finally displayed the top companies as reflected in the chart (df.sort_values(by='profit', ascending=False).head())

Note: The project was created using Google Colab https://colab.research.google.com/
