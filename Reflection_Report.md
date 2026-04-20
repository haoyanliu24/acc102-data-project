# Reflection Report

This reflection summarises the purpose, process, findings, and personal learning from my ACC102 Python data analysis project. The project focuses on analysing Apple Inc. (AAPL) stock price data to explore trends, return patterns, and volatility using basic Python data skills. The intended audience includes finance students and general investors who want to understand simple quantitative analysis of stock performance.

The dataset used in this project is historical daily stock data for AAPL, downloaded from Yahoo Finance using the yfinance library. The time period ranges from 2020 to 2025. I chose this dataset because it is reliable, widely used in academic and practical finance, and directly related to a business and financial context. It includes open, high, low, close, adjusted close prices and trading volume, which provide sufficient information for descriptive analysis and visualisation.

In terms of Python methods, I used pandas for data loading, inspection, and cleaning. I removed missing values to ensure data quality. I then calculated daily returns using the percentage change function and constructed 50-day and 200-day moving averages to identify long-term price trends. For visualisation, I applied matplotlib to create two charts: one showing stock price with moving averages and another displaying the distribution of daily returns. I also generated descriptive statistics to summarise key features of returns.

The main insights from the analysis are straightforward but meaningful. First, AAPL shows a clear long‑term upward trend during the period. Second, moving averages help smooth short‑term fluctuations and reveal underlying momentum. Third, the distribution of daily returns is concentrated around zero, indicating relatively stable return behaviour for a large‑cap company. These findings support a basic understanding of stock price behaviour without over‑complicating the analysis.

The project also has several limitations. It only analyses a single stock, so results cannot represent the entire market. The analysis relies on descriptive methods rather than predictive models. In addition, external factors such as macroeconomic conditions and company news are not considered. For improvement, I could include more stocks for comparison, add risk indicators, or extend the analysis with simple statistical tests.

From this task, I strengthened my ability to carry out a complete data workflow, including obtaining, cleaning, analysing, and presenting data. I also gained a clearer understanding of how Python can be used in accounting and finance contexts. This project helped me become more confident in handling real data and communicating results in a structured way.

## AI Disclosure
I used AI support to clarify code structure and check grammar. All project design, Python workflow, analysis logic, and this reflection were completed and finalised by myself.
