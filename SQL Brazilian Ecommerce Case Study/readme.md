# SQL Brazilian Ecommerce Case Study

## Project Overview

This project performs SQL-based case study analysis on a Brazilian e-commerce dataset using Databricks.

The goal is to analyze customer behavior, order trends, payment patterns, freight cost, delivery performance, and regional business activity. The analysis is structured around case study questions and converts SQL results into actionable business insights.

## Tools Used

- Databricks
- SQL
- Delta Tables
- GitHub

## Dataset

The original CSV files were uploaded into Databricks and created as managed Delta tables under the `ecommerce_analysis` schema.

The analysis uses the following Databricks tables:

- `customer` — customer location and customer ID details
- `geolocation` — zip code, city, state, latitude, and longitude information
- `orders` — order status, purchase date, delivery dates, and estimated delivery dates
- `order_items` — product-level order items, price, freight value, and seller information
- `payments` — payment type, payment installments, and payment value
- `order_reviews` — customer review scores and review timestamps
- `products` — product category and product attributes
- `sellers` — seller location and seller ID details

The source CSV files are not stored directly in this repository because of file upload and size limitations.

The case study questionnaire is included in the project under the `case study Questionnaire/` folder.

