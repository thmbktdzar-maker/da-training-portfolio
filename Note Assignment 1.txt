# First Look at the Data (no analysis yet)


## customers.csv
- Rows: 3404 
- Columns: customer_id, first_name, last_name, email, phone, zone, signup_date, acquisition_channel
- One row represents: one customer

## orders.csv
- Rows:6075
- Columns:order_id,customer_order, order_ts, channel, fulfilment, zone, promo_code, discount_amount, delivery_fee, status, delivery-T, promised_at
- One row represents: one order


## products.csv
- Rows:19
- Columns:product_id, product_name, category, list_price, unit_cost
- One row represents:one product

## reviews.csv
- Rows:1561
- Columns: review_id, order_id, review_date, rating, comment
- One row represents: one review

## orders_items.csv
- Rows:10071
- Columns:order_item, order_id, product_id,qty, unit_price
- One row represents: one order item
 
## Questions for the client
1.the first 1/1/2025
and last order date 6/30/2026

### a pivot table of orders per month. How many months does the data cover, and which month has the most orders?

Orders per month: see the pivot table below.
- Months covered: 18 (Jan 2025–Jun 2026)
- Month with the most orders: Dec 2025, with 596 orders
Month	Orders
Dec-25	596
May-26	479
Feb-26	414
Apr-26	378
Jun-26	377
Mar-26	371
Jan-26	349
Sep-25	348
May-25	339
Oct-25	313
Nov-25	310
Feb-25	291
Mar-25	281
Aug-25	261
Jun-25	261
Apr-25	260
Jul-25	231
Jan-25	216

#### two things in the data that surprised you or that you do not yet understand
1. December 2025 had 596 orders, the highest monthly total. Was there a holiday promotion, a large one-time order, or another event that explains the spike?
2. Orders were much higher in 2026 than in many earlier months—for example, 349 in January 2026 versus 216 in January 2025. Did the business, its marketing, or its order-recording process change?
