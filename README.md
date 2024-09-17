## **Overview :**

The Adventure Works company represents a bicycle manufacturer that sells bicycles and accessories to global markets.
The management of the company wants to track it’s key performance indicators (sales, profits, revenues and returns).

The goals were to:

Compare regional performance.

Analyze product level trends.

Identify high value customers.

## **About data :**

The data was stored in 3 separate tables, with 56,046 rows of sales data, 1,809 rows of returns data and 293 rows of product data.


## **Project Highlights :**

The pbx file has four pages, one for the executive team, one that had the geographical data, one that analyzed the products and finally a page for the customers.

**1) Executive Dashboard** — A high level summary of the entire data set.



   ![image](https://github.com/user-attachments/assets/8952e8c9-02f3-4c56-b698-9093e726196e)


   

   The executive page is a summarized view of the company’s KPIs, with 24.9 million dollars in revenue, 25,200 orders, 10.5 million dollars in revenue and a return rate of 2.2 percent. The accessories product category led by amount of orders, followed by bikes and finally clothing. We can also see a simple matrix of the leading ten products showing the orders, revenue and the return rate. The page can be further filtered to show these metrics by region and year.

   I was able to incorporate some drill through functionality. This means that if you click on a specific product you can go to a separate dashboard (The Product Detail Dashboard) and view more details on just this specific product. 

   

   **2) Map** — A nice simple visualisation to learn about using geospatial data & tooltips.
   





   ![image](https://github.com/user-attachments/assets/e7af5c36-c943-4580-bb31-b8ce32b99e55)




   
   

   **3) Product Details** - All the product specific KPIs.

   Used Numerical range parameter for checking how price adjustment will impact profit.
   
   Used Field parameter to dynamically change the metrics in the same visual.
   
   The top of the dashboard contains KPI performance against targets for orders, Revenue and Profit of the selected product.
   
   

   ![image](https://github.com/user-attachments/assets/91b7431f-5aea-4532-9479-8e88b8641239)




   

   **4) Customer Details** — All the customer specific KPIs.
   

   ![image](https://github.com/user-attachments/assets/66053eb9-0c2b-4591-b130-909936ff356d)




