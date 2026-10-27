# coursework
Step 1: The product category that is making the most losses
- Using SQL, we found that 'Tables' have the highest loss

| sub_category | total_sales | total_profit | profit_margin |
|--------------|-------------|--------------|---------------|
| Tables | 755993.19 | -62888.15 | -8.32 |
| Fasteners | 83061.63 | 11453.67 | 13.79 |
| Labels | 73254.17 | 14980.01 | 20.45 |
| Supplies | 242482.96 | 22471.02 | 9.27 |
| Envelopes | 170793.58 | 29583.16 | 17.32 |

Questions:
- Which products and markets should management prioritise?
- Which transactions are causing the losses?
- What pricing changes would be required to restore profitability?
- How much additional revenue would those changes require, and what happens if demand falls
- Should certain products be repriced, reviewed, or discontinued?

Step 2: The market where Tables are losing the most money
- Using SQL, we found that EU has the highest profit loss, while APAC has the highest sales. These sales could potentially improve the profit margin.

| market	|total_sales	|total_profit	|profit_margin|
|-|-|-|-|
|EU	|105381.38	|-20998.42	|-19.93|
|APAC	|224050.08	|-18933.51	|-8.45|
|US	|206965.53	|-17725.48	|-8.56|
|LATAM	|144880.33	|-12305.85|	-8.49|
|Canada	|849.36	|300.18	|35.34|
|EMEA	|39333.92	|2764.25	|7.03|
|Africa	|34532.60|	4010.69|	11.61|

# Which country in EU, Tables are losing the most money?
# Why is Germany Tables losing so much money?

| discount|	number_of_transactions	|quantity	|total_sales	|total_profit	|profit_margin	|price_per_unit|	original_price_per_unit	|cost_per_unit	|break_even_discount	|profit_per_unit|
|-|-|-|-|-|-|-|-|-|-|-|
|0.3500	|18|	66	|21421.61	|-3203.89	|-14.96	|324.57	|499.34	|373.11	|0.25	|-48.54|
|0.4500	|2	|11	|2546.43|	-1103.19	|-43.32	|231.49	|420.90	|331.78|	0.21|	-100.29|
|0.8500	|2	|10	|796.84	|-3068.66	|-385.10	|79.68	|531.23	|386.55	|0.27	|-306.87|

