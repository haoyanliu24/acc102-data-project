Reflection Report for ACC102 Mini Assignment

Name: Haoyan Liu
Date: 8 April 2026

1. Analytical Problem and Target Audience

For my ACC102 mini assignment, I did a simple analysis of AAPL and MSFT stock prices from 2023 to 2026. The main question I wanted to answer is: how have the prices of these two stocks changed in the past few years, and what basic trends can we see?

The target audience is new investors who are just starting to learn about stocks. Because the analysis is simple, anyone can understand the trends without needing deep financial knowledge. This fits the assignment’s requirement of creating a useful data product for real users.

2. Dataset Selection

I used daily stock price data from WRDS CRSP. The data covers AAPL and MSFT from January 2023 to April 2026. I chose this dataset because WRDS is considered reliable in finance studies, and these two stocks are very representative of the US tech sector.

I also selected this dataset because it is easy to work with for a basic analysis. The data includes date, ticker, and price, which is simple enough for my current Python skills. I did not want to use something too complex, as this project is meant to show my understanding of basic data analysis, not advanced models.

3. Python Methods Used

The Python code follows a basic but complete workflow.

First, I connected to the WRDS database using the wrds library. I wrote a simple SQL query to pull data for AAPL and MSFT. Then I used pandas to clean the data—for example, I converted the prices to positive values because CRSP uses negative numbers for split adjustments. I also removed any missing rows to keep the data clean.

Next, I organized the data into a pivot table to make it easier to plot. Finally, I used matplotlib to create a line chart that shows the price trends of AAPL and MSFT. I also printed a simple summary table to show basic statistics.

All these steps are basic, but they show that I can properly load, clean, visualize, and understand financial data. I understand each part of the code and how it contributes to the final results.

4. Main Insights

The analysis shows three clear points:

1. Both AAPL and MSFT prices increased overall from 2023 to 2026.

2. AAPL’s price growth looks steeper than MSFT’s in this period.

3. The line chart makes it easy to see the trend and compare the two stocks.

These results are simple, but they are meaningful for new investors. The visual chart also helps the audience understand the data better than just showing numbers.

5. Limitations

There are also some limits to my project.

First, I only analyzed two stocks, so the results cannot show the whole market. Second, I did not calculate returns or volatility—only price trends. This means the analysis is basic and does not include risk measures. Third, the time period is short compared to real financial research.

In future improvements, I could add more stocks, calculate returns, or use more advanced plotting to make the project more professional.

6. AI Use Disclosure

I used Doubao on 8 April 2026 to help me check the report structure and fix some small English issues. All the analysis, code, and main ideas are my own work. I understand what I did and why I did it.
