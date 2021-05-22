# (Amazon_men`s_clothing)
## by (Mostafa khalil)


## Dataset

> Amazon is one of the largest e-commerce sites in the world and the Arab world, and includes many categories such as men's clothing, women's clothing, games, accessories and other categorie,By analyzing a category of these categories, you can find out the most popular products. If you want to create your own e-commerce project in your country or region, you can by analyzing the products on the Amazon website you know the most popular and sought-after products and the highest rating,So I did scrape For menswear<And I collected more than 14,000 products to analyze them and find out the average prices, the most expensive, the cheapest, the most wanted and the highest rated..

- What is the structure of your dataset?
>  this dataset about mens clothing from 300 pages on amazon website 48 result per page. it contain over 14000 rows with 6 columns
1. product : the name of product in amazon
2. rating : from 1 to 5 stars mean 5 is very good
3. no_review : the number of people who Participate in the classification
4. price : price of each product
5. image : url of product images
6. product_url : page of each product on amazon


## Summary of Findings

> the average price is 43 dollar , the highest product`s price is filson lined wool packet 750 dollar,the lowest product`s price is hanes mens short sleeve 4.80 dollar , the most frequent products are Anchor MSJ Men's 50s Male Clothing Rockabilly Style Cotton Mens Shirts with 11 times then Funny Guy Mugs Men's Hawaiian Print Button Down Short Sleeve Shirts with 8 times.

> rating is so dependendable on the no_review ,if the number of reviews is higher the rating will be above 4 stars but there are some products have highe rating but the it`s number of review is very low.

> we can predict the best product by finding the products that their number of review greater than(average) 1161 and their price are less than (average) 43 dollar  and they are 253 products

## Key Insights for Presentation

>  the distribution of price over the data We conclude that the product price from 4 dollar to 50 dollar are most popular in this data and also this group are less than the average price (43 dollar) This means that most of the products are inexpensive , i provided this insights by using histogram plot

>  the relationship between price  and number of reviews , We can conclude that The number of reviews will be more higher in the products whose price is less than 150 dollar , and the lower the price, the greater the number of reviews, and it peaks in the products of less than 50, noting that the average price is 43