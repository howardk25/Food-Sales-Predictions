# Food-Sales-Predictions
The goal behind this analysis was to find sales trends and Big Marts various outlets and to improve overall sales

![image](https://user-images.githubusercontent.com/77650918/111381616-8ec79800-866b-11eb-9040-b427bde42d6b.png)

One of the first things I did was dig into the distribution of different types of items sold at Big Mart. The image above shows us the distribution of sales numbers between each type of item sold through Big Marts Outlets.
The data shows us that most of the items sold are non-consumables with food and drinks following respectively.
What we can gain from this, is to put more marketing efforts to increase sales in beverages.
To do this, we can increase product visibility by having more areas in the stores that have beverages in them and more advertising through out the store.

![image](https://user-images.githubusercontent.com/77650918/111381846-dea65f00-866b-11eb-9d83-eb0586311873.png)

Next, I wanted to look at the distribution between tier types. The data shows us that most of the outlet location types are tier 3, so that's where most of the sales will be coming from.

![image](https://user-images.githubusercontent.com/77650918/111381876-e9f98a80-866b-11eb-979c-b14c41c36d1f.png)

The above image shows the distribution of the breakdown of each type of products solds sales frequency. Fruits and vegetables as well as snack foods seem to be the most sold items in the outlets on average. 

![image](https://user-images.githubusercontent.com/77650918/111381944-ff6eb480-866b-11eb-9266-d6e43fe32389.png)

This boxplot image above shows us that stores are selling an average of 2000 items per year. 

![image](https://user-images.githubusercontent.com/77650918/111381974-05649580-866c-11eb-9c8f-48c5559b2775.png)

The heatmap image above shows the level of correlation between each variable. According to this heatmap, The highest correlated variable to our target variable, which is item sales, is the items MRP. This is followed by item weight and outlet establishment year
![image](https://user-images.githubusercontent.com/77650918/111835030-0985f280-88ba-11eb-9f50-92dbebeef190.png)

The above image shows the results of the Random Forest Regressor model. Item MRP, Outlet Type, and Item Visibility seem to be the most important variables related to sales. 
