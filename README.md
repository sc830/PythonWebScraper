# Python Stock Scraper

## Description

This Python script utilizes web scraping and Discord webhooks to provide users with customized alerts based on their stock portfolio and analyst ratings. I created this scraper to more easily manage and summarize my portfolio and keep up with market changes. While building this script, I learned about Discord server integration with webhooks, authorization tokens, and using BeautifulSoup to scrape and read HTML.

## Technologies

Developed in Visual Studio Code as a Python notebook file. Also uses BeautifulSoup for web scraping and searching/reading HTML, Discord API for webhook integration. Price data sourced from google.com/finance, analyst data and ratings sourced from wallstreetzen.com.

## Installation

StockScraper1.2.ipynb must be downloaded and run through a Python environment. Users must have already run "pip install beautifulsoup4" and "pip install discord.py" to execute this script.

## Usage

Replace webhook variables with webhooks to user's Discord server, with different webhooks for each channel.
Currently, this file is presented as a Jupyter Notebook file, and must be edited manually to adjust the user's stock portfolio and purchase prices. Eventually, I hope to design a GUI to make this process easier and more attractive.

## Versions

Version 1.2: Scrapes prices from Google instead of WallStreetZen for more current prices.
Version 1.1: Scrapes stock prices, sends price alerts, and formats/sends daily summaries to secondary channel/webhook.
Version 1.0: Minimum viable product, scrapes stock prices and sends price alerts to one Discord channel based on preset requirements.
