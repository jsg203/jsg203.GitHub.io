## Order-in with Doordash!
<img src="images/FoodAppCoverpag.JPG?raw=true"/>

**Why this Project:** <br><br/>
    Doordash is a popular online food delivery app that changed the way people order in! Before we would call the specific store and speak to an associate to place an order for pickup or delivery. Now Doordash is available to give customers option to choose any store that uses Doordash for food delivery. This is a game changer because some stores did not have an option for delivery. Doordash makes it possible by providing a “Dasher” to pick up your order and deliver it to your location. <br><br/>
    Personally, when I work in NYC, during a group lunch we always order using Doordash because of convenience. At my suburban home we have very limited eatery options and delivery can take longer than expected when it's just easier to just hop in your car and pick up at most 10 minutes away. With two kids, Doordash is only used when necessary such as when meals at home was inedible or simply just not enough time. But it is great to have the option of an online food delivery app. <br><br/>



**The dataset** <br><br/>
    In this study we will look at data originally obtained from [iFoods](https://github.com/nailson/ifood-data-business-analyst-test/blob/master/ifood_df.csv) which is the Brazilian equivalent of Doordash. For educational purposes, the dataset I’ll be using will be slightly modified. The data is collected for year 2014 to 2016. How many people actually use this service? How much money are people actually spending? Do single people use Doordash more? With simple use of Excel spreadsheets these are the key information I got from exploring the data. <br><br/>
•	There are **2205** customers. <br><br/>
•	The **oldest** customer was **80 years old**. <br><br/>
•	The **average money spent was $562.76**. <br><br/>
•	The **total** amount spent **$1,240,896.00** <br><br/>
•	Average amount spent is **positively related to yearly income** <br><br/>

**General Data Statistics**: <br><br/>
Excel spreadsheets will be used to analyze this decent sized data set which as 2205 rows. Simple aggregate descriptive statistics can done using excel formulas.  The total amount spent from 2014 and 2016 in this dataset is $1,240,896.<br><br/>
I used the YEAR formula to extract just the year and then found the MAX and MIN of that Year column to find the minimum and maximum year. Then I used the SUM formula for the amount total column to get the total amount of money spent. The same “MAX” formula can be used in the age column to find the oldest customer. <br><br/>
Let’s look at the demographics and see what age group make up the customers using Doordash in this dataset. The pie chart is great for showing qualitative data such as Age group. Figure 1 shows that 36-50 year olds make up majority of the customers. Surprisingly, the smallest percentage (9.9%) is the 24-35 year group. Age group was created with a new column and using the IF/AND statement to create age group bins. The pivot table was used to create the pie chart by looking at Age group and its count for values. Let’s get into the fun statistics and look at correlations among variables!
<img src="images/average amount by age.jpg?raw=true"/>

### 2. You can add any images you'd like. 

<img src="images/dummy_thumbnail.jpg?raw=true"/>

