# SQL
SQL Portfolio 
-- Write a query that orders the items by price 
SELECT item_name
FROM superstore
ORDER BY price ASC; 

SELECT *
FROM superstore 
ORDER BY price;

-- Write a query that shows a STAT about the item prices like: SUM, AVG, MIN, MAX, COUNT 
SELECT AVG(price)
FROM superstore 
WHERE category = "Kitchen Supplies"; 

SELECT stock_quantity
FROM superstore
WHERE item_name = 'Premium Coffee Maker';

SELECT COUNT(item_id)
FROM superstore; 

SELECT MIN(price)
FROM superstore 
WHERE category = "Furnishings"; 



-- Write a query that shows a STAT about the price fr items in the cat "Kitchen Supplies"

-- Write your own questions 
