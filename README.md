# Superstore-visualization
The big Super-Market chains have been trying to understand different parameters to increase the profits for decades such as the predictive analysis of consumer behaviour. But to make important business decisions, they need to understand the basic monthly sales trends, relation between profit & sales, or the number of products sold is very important. This data can be anormous and only visualizations can help them gain insights from it.

Therefore, in this project, I have analyzed a superstore sales data with various visualization techniques. Some of the business problems I have considered to resolve using these visualizations are -

1. Identify high-demand products to avoid stockouts and low-demand products to reduce overstock and storage costs.   
    
2. Evaluate whether the monthly revenue goals are achieved and if external event (such as holidays or economical fluctuations) are affecting the business.    

3. Decide whether to discontinue, promote, or reposition low-performing products (total sales < 20k)
    
4. Determine whether higher sales consistently lead to higher profits or if there are inefficiencies in pricing, cost structures, or other factors.

## **Visualizations and Analysis**

1. Product Orders Visualization:

    Objective: Represent the number of orders for each product in the superstore.

    Technique: Applied the caseswap() function to standardize the product names, ensuring consistency in the analysis.

    Insight: Provides a clear overview of the order distribution for each product.
   
![image](https://github.com/priyankaa370/Tableau-visualization/assets/81320366/9067a42d-9a5e-4386-aa08-7baa26240282)



2. Monthly Sales Trend Analysis:

    Objective: Visualize monthly sales trends over the year.

    Technique: Used a line chart to showcase the sales pattern throughout the year.
 
    Insight: Highlighted the consistency in sales patterns, even when scaling the entire sales column by a factor of 5.
   
![image](https://github.com/priyankaa370/Tableau-visualization/assets/81320366/1e582e27-e781-4b2e-88e1-8b506f7432af)



3. Product Classification by Total Sales:

    Objective: Classify products based on total sales, using different colors for clarity.

    Technique: Utilized a Boolean field to determine if total sales are greater than or equal to 20k (orange) or less than 20k (blue).

    Insight: Offers a visual categorization of products and provides the total sales amount for each.
   
![image](https://github.com/priyankaa370/Tableau-visualization/assets/81320366/64730627-6b76-4d14-a955-b6cec9b7ca2e)

  

4. Scatterplot and Regression Analysis:

    Objective: Analyze the relationship between sales and profit using scatterplots and regression lines.

    Technique: Created a scatterplot of sales vs profit and another with a regression line.

    Insight: Derived the regression line equation with a slope of 0.182 and an intercept of -17.76, demonstrating the correlation between sales and profit.

![image](https://github.com/priyankaa370/Tableau-visualization/assets/81320366/c540238a-461a-42d3-8ac6-cbdd12ab4017)

## **Tabpy**
TabPy is a framework that enables Tableau to execute Python code. It allows users to run Python scripts within Tableau’s calculated field or deploy functions on the TabPy server using Python API.  

## **Steps for running Tabpy in Tablaue**
1.	In the anaconda prompt, type – ‘pip install tabpy’.
2.	Type – ‘tabpy’. It should show – ‘listening to port 9004’. 
3.	Then open Tablaue, in the help section,
4.
![image](https://github.com/priyankaa370/Superstore-visualization/assets/81320366/58c6eb59-15fd-4134-9c4d-072611f45a66) ![image](https://github.com/priyankaa370/Superstore-visualization/assets/81320366/032fa178-d484-4e14-a72c-9af9e74f578b)

5.	The dataset is taken from the Tableau community website which can be found here – ‘https://community.tableau.com/s/topic/0TO4T000000Rc9wWAC/superstore’


