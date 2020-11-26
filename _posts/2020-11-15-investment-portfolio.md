---
title: "Investment Portfolio"
date: 2020-11-15
tags: [machine learning, data science, web scraping, database, python, time-series forecasting]
header:
excerpt: "End-to-end project for real-time stock price predictions."
---

This is an end-to-end data science project, which is my attempt to learn different technologies and concepts involved in productionizing an ML concept. It tries to cover the following 4 aspect of a Data science project:

1. Web scraping data from internet
2. Data storage
3. Model building & evaluation
4. Continuous integration (CI)

## Current stage of project

I currently have a script ```scrapy.py``` that scrapes the S&P index, Nasdaq & Dow index values from **finance.yahoo.com**.

I have scheduled the script to scrape the opening and closing value of the indexes on weekdays using a Cronjob.

I have also setup a slack bot that would send notifications to my Slack channel after the execution of the script.

> Current Technologies: Python, Scrapy, Slack (for notification), Cronjob

> Future Technologies: PostgreSQL (potential data storage), Jenkins, Docker

<a href="https://github.com/NikhilSawal/investment_portfolio" target="_blank">Github link to project</a>
