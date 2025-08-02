SELECT 
    Category,
    Region,
    SUM(Sales) AS Total_Sales
FROM ecommerce_sales.superstore
GROUP BY Category, Region
ORDER BY Total_Sales DESC;
