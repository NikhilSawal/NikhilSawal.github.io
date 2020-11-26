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
4. Continuous Integration (CI)

## Problem Statement
Hedging is a popular concept in investment world. It gives the investors the ability to safeguard their returns against unforeseeable circumstances, by diversifying their portfolio. Basically hedging is *not putting all your eggs in one basket* i.e *not putting all of your money in one industry*.

As we witnessed with the current pandemic situation, could access to certain data and analytics beforehand, help us get a better sense of the financial state of different industries down the line?

## Motivation
When I worked at my most recent employer
1. What if we start collecting News headlines data and keep track of how different keywords in the news headline affect different industries. Eg: If keywords like pandemic or epidemic start to pop up on different news channels, could we have come up with strategies that would have helped us reduce the impact?
2. Can we create a bridge between News data and Stock prices, that can explain the fluctuations in stock prices as a function of word of mouth or popular topics on social media?  

## Current stage of project

I currently have a script ```scrapy.py``` that scrapes the S&P index, Nasdaq & Dow index values from **finance.yahoo.com**.

I have scheduled the script to scrape the opening and closing value of the indexes on weekdays using a Cronjob.

I have also setup a slack bot that would send notifications to my Slack channel after the execution of the script.

> Current Technologies: Python, Scrapy, Slack (for notification), Cronjob
> Future Technologies: PostgreSQL (potential data storage), Jenkins, Docker

<a href="https://github.com/NikhilSawal/investment_portfolio" target="_blank">Github link to project</a>
