---
title: Northwind EDA based on SQL
summary: This project consists on answering different business questions based on the Northwind Database
tags:
- SQL
- Data Base
- EDA
date: "2022-12-20T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo extracted of Microsoft Access
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  link: https://github.com/MiguelAlvRed
url_code: "https://github.com/MiguelAlvRed/Northwind_SQL_EDA.git"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---

At this project I'm going to answer different business questions based on the Northwind Database, this DB was create on PostgreSQL so, first of all, I have to connect to my local host and then launch the queries.

To make it possible I used the following libraries:

  * Pandas: To store the created dataframes
  * Pandas.io.sql: To read the SQL queries into dataframes
  * Psycog2: To connect the notebook to the PostgreSQL engine
  * Warnings: To make expections on warnings

**Business Questions:**

  * What is the total number of clients per country?
  * What is the total number of orders per country?
  * What is the average price per order per country?
  * What is the total invoice for each country?
  * What is the total profit for each country?
  * What are the 10 most ordered products?
  * What are the 10 most expensive products?
  * What are the 10 products with the highest invoice?
  * What are the 10 products with the highest unit profit?
  * What are the 10 most profitable products?


**Conclussions about the Analysis**

Once this EDA has been carried out, a series of conclusions are drawn:

  * The countries with the highest number of clients are USA, Germany, France and Brazil.
  * The countries with the highest number of orders are USA, Germany, Brazil and France.
  * The countries with the highest average order income are Austria, Ireland, Denmark and Germany.
  * The countries with the highest total income are USA, Germany, Austria and Brazil.
  * The countries with the highest total profit are USA, Germany, Austria and Brazil.

According to the information extracted about the different countries and markets, it can be corroborated that the most developed and stable markets are USA, Germany and Brazil.

  * The most expensive product doubles the price of the previous product on the list.
  * The most expensive product, despite its high price, generates the higher income.
  * Surprisingly, the most expensive product is also the one with the highest profit, both on a unit and overall basis.

If you want to check the JupyterNotebook where I develop this project you will find it at the *Code* button at the top of the page.


