ДЗ3_Бажинова_Ірина_Іванівна

1.1_____________________________________
SELECT * FROM products


1.2_____________________________________
SELECT name, phone FROM shippers;


2_____________________________________
SELECT      
AVG(price) AS average_price,     
MAX(price) AS max_price,     
MIN(price) AS min_price 
FROM      
Products;


3_____________________________________
SELECT DISTINCT  category_id, price 
FROM products 
ORDER BY price DESC 
LIMIT 10;


4_____________________________________
SELECT COUNT(*) AS product_count
FROM products
WHERE price BETWEEN 20 AND 100;