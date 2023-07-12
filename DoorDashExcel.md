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
<img src="images/pieAgeGr.jpg?raw=true"/>
<br><br/>
 Next, I combined the sum of kids and teens at home to be Children at home in a new column. Then I used Pivot table to create a bar graph that shows the age groups and the number of kids living at home and the average amount of money spent using Door dash. Figure 2 shows that the 35-50 year group average amount spent for those with no children at home was the most out of all groups which is $1122.81. Across the age groups, those with no children at home spent more. The age groups 24 to 50 years old who had more than 1 child in the house spent less than the average amount of $400. The age group 51 to 66 plus seem to spend an average $600 with one child living in the house. The assumption is that younger age group may have a smaller budget with more children in the house. The older age group may have less time to cook and spend more or maybe they are retired and have more money to spend. <br><br/>
<img src="images/average amount by age.jpg?raw=true"/>
<br><br/>
So let’s answer the question what is the frequency of the total amount spent on Doordash? In Figure 3, the histogram shows the majority spent under $450 and the least spent between $2250 and $2500. So what else do we want know? What are the income of these customers and how does it relate to spending? 
<img src="images/Frequency of Total Amount Spent on Door Dash.png?raw=true"/>
<br><br/>
Figure 4, a pivot table was used to measure the frequency of what month customers joined. The bar graph shows that most customers joined in January. And in December was the least customers joined. Some assumptions are that during the holiday season of November and December, more people most likely visit family or have events to attend and eat there instead of ordering in. January is the start of a new year and the middle of winter season so many people most likely order in. 
<img src="images/freqMonthjoin.jpg?raw=true"/>
<br><br/>
A scatterplot shows the relationship between two variables. This plot reports the values of the individual data points. You can see in Figure 4, that as the amount of yearly income increases, the total amount spent using Doordash increases. There are two outliers there seen at $0 spending between $1500 and $2000 and then another outlier at $113,734 income spending only $274. This could be from error in data collection. The R squared number is at 67.74% which tells us the strength of the model based on the data points lying around the trend line. The closer to 1 (100%), the model has little variation. 
<img src="images/unfilteredincomevsspent.jpg?raw=true"/>
<br><br/>
**Recommendations**<br><br/>
Based on the information I gathered using excel, the more money the customer made, the more money they spent. Also the age group 36 to 50 year old made up the majority of the customers. The 36 to 50 year olds are the major customers, but the ones who have kids are the least. Advertisements to encourage that ordering-in through the app can be convenient and budget friendly, but make it appear that families young and old can afford to by offering really good discounts or promotions. For promotions, maybe target holiday time for those who don’t feel like going out and staying in. Also, further studies in this dataset to improve promotions is to understand what products people purchase the most and offer deals if those products are included in their order. <br><br/>

Excel spreadsheets are great for doing data analysis on small datasets like this. What else can you gather from this dataset that I may not have gotten to in this analysis? Let’s connect and talk about other powerful tools in excel. 
