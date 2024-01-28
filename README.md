# E-Commerce Transactions
Here is the final SQL project that I have completed after participating in the Data Analysis: Fullstack Intensive Bootcamp organized by MySkill. The provided dataset originates from one of the e-commerce platforms in Indonesia (not real data). In this final project, I will explain the approach to querying the data and provide insights and solutions obtained from the dataset.

## Dataset
The data used is sourced from an E-Commerce dataset (not real data). Regarding the dataset explanation, it is as follows:

order_detail:
* id → unique number of the order/id_order
* customer_id → unique number of the customer
* order_date → date when the transaction took place
* sku_id → unique number of the product (SKU stands for stock keeping unit)
* price → price listed on the price tag
* qty_ordered → quantity of items purchased by the customer
* before_discount → total price value of the product (price * qty_ordered)
* discount_amount → total discount value for the product
* after_discount → total price value of the product after deducting the discount
* is_gross → indicates whether the customer has not paid for the order
* is_valid → indicates whether the customer has made the payment
* is_net → indicates that the transaction is completed
* payment_id → unique number of the payment method

sku_detail:
* id → unique number of the product (can be used as a key when joining)
* sku_name → name of the product
*base_price → price of the item listed on the price tag / price
*cogs → cost of goods sold / total cost to sell 1 product
* category → product category

customer_detail:
* id → unique number of the customer
* registered_date → date when the customer started registering as a member

Payment_detail:
* id → unique number of the payment method
* payment_method → payment method used

Table Schema :





