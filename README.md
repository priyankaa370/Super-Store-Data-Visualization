# Superstore-visualization
To understand data of a sample superstore by visualizations using Tabeau


## **Tabpy**
TabPy is a framework that enables Tableau to execute Python code. It allows users to run Python scripts within Tableau’s calculated field or deploy functions on the TabPy server using Python API.  

## **Visualizations and Analysis**

1. **Bar Chart**
   
![image](https://github.com/priyankaa370/Tableau-visualization/assets/81320366/9067a42d-9a5e-4386-aa08-7baa26240282)

**Analysis** : This visualization represents the Number of orders for each product. Also, I have used the caseswap() function to change all the uppercase letters to lowercase and vice versa in the products column. This chart clarifies how many orders are there for each product.

2. **Line Chart**
   
![image](https://github.com/priyankaa370/Tableau-visualization/assets/81320366/1e582e27-e781-4b2e-88e1-8b506f7432af)

**Analysis** : Here, the monthly sales obtained over the year can be seen. This line chart is helpful to understand the trend of the sales over the whole year. Also, we can understand the pattern does not change even when we multiply the whole sales column by 5.  

3. **Bar Chart**
   
![image](https://github.com/priyankaa370/Tableau-visualization/assets/81320366/64730627-6b76-4d14-a955-b6cec9b7ca2e)

**Analysis** : This chart is to classify the products by having total sales more than and equal to 20k and between 10k to 20k with different colors. As we can see in the title section, orange denotes total sales more than or equal to 20k and blue is denoted for total sales less than 20k. This coloring was achieved by using Boolean field where if it is true, it is greater than or equal to 20k (hence, orange), or else, if it is false, it is less than 20k (and hence, blue). We can also see the total sales amount for each product in this visualization.  

4. **Scatter Plot**

![image](https://github.com/priyankaa370/Tableau-visualization/assets/81320366/c540238a-461a-42d3-8ac6-cbdd12ab4017)

**Analysis** : •	Here is a visualization of a scatterplot with sales vs profit and another with sales vs regression line. We are getting the slope as 0.182 and the intercept point as -17.76. The top graph shows us the scatter plot of the profit values based on the sales. In the bottom graph, a regression line is obtained by using the slope and intercept whose values are as mentioned above. It gives us a graph of a regression line according to the sales values.  

## **Steps for running Tabpy in Tablaue**
1.	In the anaconda prompt, type – ‘pip install tabpy’.
2.	Type – ‘tabpy’. It should show – ‘listening to port 9004’. 
3.	Then open Tablaue, in the help section,
4.
![image](https://github.com/priyankaa370/Superstore-visualization/assets/81320366/58c6eb59-15fd-4134-9c4d-072611f45a66) ![image](https://github.com/priyankaa370/Superstore-visualization/assets/81320366/032fa178-d484-4e14-a72c-9af9e74f578b)

5.	The dataset is taken from the Tableau community website which can be found here – ‘https://community.tableau.com/s/topic/0TO4T000000Rc9wWAC/superstore’


