# Technology Sales: Project Overview

In this project, I take a data set of technology sales and utilize tools such as Python Pandas and matplotlib to explore the data and answer hypothetical business questions.

## The Data's Contents

Data on purchases from a particular technology store. With each purchase, we got the following:
- Order ID
- Product name
- Quantity Ordered
- Price each
- Order Date
- Purchase Address

## Data Cleaning 


After obtaining data in the form of separate csv's for each month's sales, I had to clean it up so it was analyzable for my goals. I made the following changes and created the following variables:
- Merging 12 months of sales data into a single CSV file
- Drop rows of NaN
- Convert column to correct types (all were as type string)
- Add a month column
- Add a sales column
- Add a city column

## QUESTIONS ANSWERED:

1. What was the best month for sales? How much was earned that month? Worst month?
![image](https://user-images.githubusercontent.com/121086856/211246170-d1d90787-6335-4800-9477-2f728da37035.png)


2. What city had the highest number of sales? Lowest?

![image](https://user-images.githubusercontent.com/121086856/210975840-f923f502-c7b1-4546-829a-f6ae80c4f79d.png)

3. What time should we display advertisements in order to maximize likelihood of customer's buying product?
![image](https://user-images.githubusercontent.com/121086856/210975915-b5ed49b5-62b2-491a-bbbc-890a5e732539.png)

4. What products are most often sold together?

('iPhone', ' Lightning Charging Cable') 1005
('Google Phone', ' USB-C Charging Cable') 987
('iPhone', ' Wired Headphones') 447
('Google Phone', ' Wired Headphones') 414
('Vareebadd Phone', ' USB-C Charging Cable') 361
('iPhone', ' Apple Airpods Headphones') 360
('Google Phone', ' Bose SoundSport Headphones') 220
('Vareebadd Phone', ' Wired Headphones') 143
(' USB-C Charging Cable', ' Wired Headphones') 120
('Vareebadd Phone', ' Bose SoundSport Headphones') 80

5. What product sold the most? Why?

![image](https://user-images.githubusercontent.com/121086856/210976090-7f0eca45-35fc-4777-8c2f-017f84b71273.png)


