# 🍕 Pizza Sales Data Analytics Project

This project explores a pizza sales dataset using Python and SQL to uncover key business insights.
I obtained the dataset from [https://www.kaggle.com/datasets/mexwell/pizza-sales].

Below are the three analytical questions I designed — as if I were working for this pizza company — to support operational and strategic decision-making:




**Question 1 – Highest Revenue Pizza:** <small>Which pizza generates the highest total revenue?</small>



![Project Screenshot](https://github.com/datzmyboy/data_project1/blob/9b1a5c7362d4f8d72cbed320418932b7ed022db9/Screenshot%202025-11-13%20132209.png)
![Project Screenshot](https://github.com/datzmyboy/data_project1/blob/9b1a5c7362d4f8d72cbed320418932b7ed022db9/Screenshot%202025-11-13%20132234.png)

### Highest Revenue Pizza: Which pizza generates the highest total revenue?

The results from the query show the **top 3 best-selling pizzas**:

1. **thai_ckn (large, chicken type)**
2. **five_cheese (large, veggie type)**
3. **four_cheese (large, veggie type)**

As illustrated in the graph, the **thai_ckn large chicken pizza generates the highest total revenue**, amounting to **$29,257.50**, which represents **37.6% of the revenue among the top 3 pizzas**.  

This indicates that the large chicken variant of the Thai chicken pizza is the most popular and contributes the largest portion of sales within the top-selling pizzas. Showing the top 3 pizzas provides context for comparison and highlights other high-performing pizzas.


**Question 2 -  Peak Sales by Month, Day, and Hour**: <small>For the pizza with the highest revenue, in which month, day, and hour does it sell the most?</small>




![Project Screenshot](https://github.com/datzmyboy/data_project1/blob/6a2c0ae24012b025dd4bf90b5eb0d35523818599/Screenshot%202025-11-13%20132209.png)
![Project Screenshot](https://github.com/datzmyboy/data_project1/blob/6a2c0ae24012b025dd4bf90b5eb0d35523818599/Screenshot%202025-11-13%20133649.png)

### Peak Sales by Month: For the Thai Chicken (Large) Pizza

The analysis shows that the **Thai Chicken (Large) pizza** achieves its highest revenue in **July and December**, each generating approximately **₱2,801.25** from **135 orders**.  

This trend suggests that demand increases during **mid-year holidays** and **year-end celebrations**, reflecting seasonal buying behavior. February shows a slight dip, likely due to the post-New Year period, while sales steadily rise from March to July, dip slightly in August, and remain high through December.


![Project Screenshot](https://github.com/datzmyboy/data_project1/blob/392e68c1871e1515a0972f51d29d84e9d7492b96/Screenshot%202025-11-13%20134417.png)
![Project Screenshot](https://github.com/datzmyboy/data_project1/blob/392e68c1871e1515a0972f51d29d84e9d7492b96/Screenshot%202025-11-13%20134459.png)

### Peak Sales by Day: For the Thai Chicken (Large) Pizza

The analysis shows that **Friday** has the highest number of orders (**244 orders**), followed by **Thursday** and **Saturday**.  

This trend suggests that pizza demand rises toward the **weekend**, likely due to end-of-week celebrations or social gatherings. In contrast, **Sunday** and **Monday** have the fewest orders, possibly because customers are resting, preparing for the week ahead, or resuming regular routines.


![Project Screenshot](https://github.com/datzmyboy/data_project1/blob/61b90d40eedefbf87f23ef65dd883afd7290d9bc/Screenshot%202025-11-13%20134417.png)
![Project Screenshot](https://github.com/datzmyboy/data_project1/blob/61b90d40eedefbf87f23ef65dd883afd7290d9bc/Screenshot%202025-11-13%20134459.png)

### Peak Sales by Day: For the Thai Chicken (Large) Pizza

The analysis shows that **Friday** has the highest number of orders (**244 orders**), followed by **Thursday** and **Saturday**.  

This trend suggests that pizza demand rises toward the **weekend**, likely due to end-of-week celebrations or social gatherings. In contrast, **Sunday** and **Monday** have the fewest orders, possibly because customers are resting, preparing for the week ahead, or resuming regular routines.


![Project Screenshot](https://github.com/datzmyboy/data_project1/blob/61b90d40eedefbf87f23ef65dd883afd7290d9bc/Screenshot%202025-11-13%20135222.png)
![Project Screenshot](https://github.com/datzmyboy/data_project1/blob/61b90d40eedefbf87f23ef65dd883afd7290d9bc/Screenshot%202025-11-13%20135510.png)

### Peak Sales by Hour: For the Thai Chicken (Large) Pizza

The analysis shows that pizza orders start increasing around **10 AM**, peaking between **11 AM and 1 PM** as people take lunch or snacks. Orders dip slightly around **2–3 PM** while most customers are at work, then rise again from **4–6 PM** when people leave work. After **6 PM**, orders gradually decline as customers settle at home.  

The **busiest hour** is **1 PM**, generating the highest revenue of approximately **₱3,942.50** from **190 orders**, indicating that customer demand is concentrated during specific hours.  

These patterns provide insights for **inventory planning, staffing, and targeted promotions** to maximize revenue during peak periods.



**Question 3 – Consistency of Sales Peaks**: <small>Based on the pizza with the highest revenue, what are its peak sales hours across all days, and how consistent are those peaks?</small>




![Project Screenshot](https://github.com/datzmyboy/data_project1/blob/61b90d40eedefbf87f23ef65dd883afd7290d9bc/Screenshot%202025-11-13%20135600.png)




![Project Screenshot](https://github.com/datzmyboy/data_project1/blob/61b90d40eedefbf87f23ef65dd883afd7290d9bc/Screenshot%202025-11-13%20135621.png)


### Consistency of Sales Peaks: Thai Chicken (Large) Pizza

The data shows a clear hourly sales pattern across most months. Orders start to increase from **10 AM** and reach their **peak at 1 PM**. After 1 PM, sales decline until around 3 PM, then rise again between **3 PM and 6 PM** before dropping steadily for the rest of the evening.  

Although not all months follow this pattern exactly, the majority display the same trend, indicating a **consistent daily sales rhythm**.  

*Note:* The query was designed in a **pivot-style format**, making it more understandable and intuitive by showing hourly orders for each month in a single table.









