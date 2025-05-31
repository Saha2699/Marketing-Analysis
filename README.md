# Marketing-Analysis
Problem Statement:
ShopEasy, an online retail business, is facing reduced customer engagement and conversion rates despite launching several new online marketing campaigns. They are reaching out to you to help conduct a detailed analysis and identify areas for improvement in their marketing strategies.

Fetching the Data:
We fetched the data from MS SQL Server and CSV file(created using python).

Data Transformation:
We have used SQL for the data transformation,means after loading the tables we used query folding technique to transform data from the source
itself.
1.Removed duplicates by using windows functions
2.Joined tables
3.Separated "no of views" and "no of likes" in engagement table into two separate columns
4.Replace null values in "duration" column with avg duration.

Sentimental Analysis:
I performed sentimental analysis of the "reviews" received from the customer_reviews.Python will analyse the reviews and will assign a sentiment score which will help us unerstand that whether the customer has positive or negative review irrespective of the rating .

libraries used:Pandas,Pyodbc,Vader,SentimentIntensityAnalyzer

Modelling:
Now after doing all the transformation build the relationship between all the seven tables using star schema.
cardinality used:
One to One
One to Many

Visualization:
We have created a report of four pages:
1.Overview:
It gives a overall representation of how the company and its products are performing,so that stackholders can get a quick insights.

2.Conversion_Details:
Conversion means how many percentage of people purchased a product after viewing.In this page you will get a detail analysis like 
what is month,product wise conversion rate etc.

3.Social Media:
Here we analysed total views,likes,clicks by different products as well as by content type(ex-Blog,Social Media,Video)

4.Customer_Review_Details:
This report will convey that how avg rating is behaving across the months also we will get to know that which rating is prefered most by the customers

charts used:-Bar chart,Line Chart,Pie Chart,Matrix,Table,Field,Slicers,Scatter Chart

Dax Functions:Caleneder,Format,Avg,Count,SUM,Filter,Calculate

Along with that i have also used Bookmarks and Field Parameters.

Conclusions:
1.Conversion rate is decreasing every year,january has the highest conversion rate of 18.5%
2.Most of the views is coming from Blogs(Content type) around 27.88%.
3.Views is decreasing every month but "no of likes" and "no of clicks" remains constant which means users are interacting but they are not purchasing the product
4.61% of reviews are positive but during initial months of the year the sentiments are negative. 








