# Why do we use Pivot Tables in Excel ??

Pivot tables in Excel are indispensable tools for data analysis and summarization, offering a range of powerful features that make handling large datasets efficient and insightful. They enable users to quickly summarize data through calculations such as sums, averages, counts, and percentages without the need for complex formulas. Additionally, pivot tables facilitate data grouping by categories or dates, improving data organization and comprehension. Their dynamic filtering options allow for focused analysis on specific data subsets, and their ability to rearrange or pivot data helps users view information from various perspectives.
# How to use Pivot Tables ?
## Now we will go step by step to grasp some basic information about pivot table :
### 1) We will use the dataset I provided ( it comes from kaggle it contains information about a business that selles bikes , go dive in the columns of the dataset to understand it better )
### 2) Go to Insert -> PivotTable (the goal of the first pivot table is to display the revenue per country, the sum of cost, and the sum of profit of the business in all countries and their states. The second pivot table aims to show the year where the revenue was highest).
### 3) Choose Country and State, and drag and drop them in the Rows area. Then, right-click Country and click on Collapse Entire Field to get the states present in each country in the dataset.
Here is an overview of what you will get after doing the collapse manipulation :<br>
![collapse](https://github.com/user-attachments/assets/2a1988c0-7be2-4ca4-af38-4a4b80fb6257)
### 4) Do not forget to add currency to the columns  Sum of Revenue (you can do that by going to Home in the top of your Excel page, then click on Currency, and tadaaa, the euro sign will appear).
![euro](https://github.com/user-attachments/assets/bbb33c9f-ef69-4691-a165-694578f3c3cf)
### PS: I customized the name of the column Sum_Revenue to Revenue per Country by clicking on it -> Value Field Settings (you can change the name and choose how to display values. I chose the percentage and got the following!).
![revenur per country](https://github.com/user-attachments/assets/9ab44412-2d41-4a18-a43e-1d2a6f857c77)
### 5) Sort the numerical values from largest to smallest (right-click on a row and do it for the country and its states because sorting the values of a country won't sort the values of its states).
![sort](https://github.com/user-attachments/assets/b7b6cfda-80cd-4859-aa40-d2a85d527c12)
### 6) Drag and Drop the cost and profit in values field and make sure that the columns got the euro currency sign.
![profit and cost](https://github.com/user-attachments/assets/09cfa69d-d836-4e71-9b66-8fa068dc27c9)
### 7) Add a calculated field to ensure that the sum of profits is correctly calculated. To do this:<br>
Click on your pivot table.<br>
Go to the PivotTable Analyze tab at the top of your Excel page.<br>
Click on Fields, Items, & Sets.<br>
Select Calculated Field.<br>
In the formula box, enter = Revenue - Cost.<br>
This will ensure the sum of profits is accurately calculated as you have noticed.<br>
![sum of calculated field](https://github.com/user-attachments/assets/1486157e-5444-4f98-9cec-4acb23f5cc74)
### 8) Let's add a filter to display information by gender and determine which gender spends the most on bikes.<br>
Click on your pivot table.<br>
Drag the Gender field into the Filters area.<br>
Analyze Spending by Gender:<br>
Use the filter to select either Male or Female to see the corresponding data.<br>
Check the revenue, cost, and profit values to determine which gender spends the most on bikes.<br>
This will allow you to filter the data by gender and easily see which gender has higher spending on bikes.<br>
![filter1](https://github.com/user-attachments/assets/2f70debb-61ef-403b-886f-62e2a8cef493)
![filter2](https://github.com/user-attachments/assets/57b8ee7b-af09-40f5-b1bf-cc088edbe85f)
The males spend more money than females!
### 9) Let's add another pivot table to see which year the revenue was highest.
![pivot 2](https://github.com/user-attachments/assets/f285501a-488d-4b70-b7e5-69ee33d76424)

As you can see it is 2015 !!
