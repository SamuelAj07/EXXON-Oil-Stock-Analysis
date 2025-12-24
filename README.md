# EXXON-Oil-Stock-Analysis

---
# Table of Content

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Preparation](#data-preparation)

[Data Overview](#data-overview) 

[Tabular Overview](#tabular-overview) 

[Exploratory Data Analysis](#exploratory-data-analysis)

[Analysis Visualization](#analysis-visualization)

[Analytical Insights](#analytical-insights)

[Actionable Recommendations](#actionable-recommendations)

[Portfolio Value](#portfolio-value)

---

## Project Overview

This project delivers an end-to-end Oil Stock Price Analysis conducted using both Microsoft Excel and Power BI, analyzing and visualizing complex relationships across price movements, trading volume, volatility, seasonality, and time-based behaviors.

The analytical objective is to transform historical stock data into clear, actionable insights that support investment decisions, risk assessment, and market timing strategies. This project demonstrates strong capabilities in data preparation, analytical reasoning, visualization design, and business-oriented storytelling

## Data Sources

The primary dataset used for this analysis  was sourced from “Kaggle.com”

## Tools Used

1. Excel (Cross tab, Pivot Charts, Data Cleaning)
   
2. PowerBi (DAX, KPIs, Interactive Visuals)

## Data Preparation

In the initial data cleaning phase, the following tasks were performed:

i. Handled missing values

ii. Standardized text

iii. Consistency Across Datasets

iv. Data Types Corrections

v. Analytical Functions

vi. DAX computation

## Data Overview 

The dataset includes the following columns:

+  Date – Trading day of the stock record.

+ Open – Price at the start of the trading day.
  
+  Close – Price at the end of the trading day.
  
+ Volume – Number of shares traded during the day.
  
+ Symbol - The stock initials for Exxon Company
  
+ High – The highest price reached during the trading day.
  
+  Low – The lowest price reached during the trading day.
  
+ Currency – The monetary unit in which the stock prices are quoted (e.g., USD).

*Analyzed column*

+ % Change – Daily percentage change in closing price.
  
+ Volatility % – Degree of price fluctuation (risk level).
  
+  7Days_MovingAvg – Average close over the last 7 days.
  
+ 30Days_MovingAvg – Average close over the last 30 days.
  
+  Weekdays – Day of the week the stock was traded.
  
+  Month – Calendar month of the trade date.
  
+  Average of Open – Mean opening price over a period.
  
+  Average of Close – Mean closing price over a period.
  
+  Average of Volume – Mean trading volume over a period.
  
+  % Volume Change – Percentage change in trading volume.

## Tabular Overview 

A brief overview of raw tabular datasets to be analyzed. The first 5 Columns are displayed below.

Date	|Symbol	|Open	|High	|Low	|Close|	Volume|	Currency|
|-----|----|-----|-----|-----|----|-----|-----|
1/3/2000|	XOM|	39.75|	40.38|	38.94|	39.16|	13458200|	USD|
1/4/2000|	XOM|	38.69|	39.09|	38.25|	38.41|	14510800|	USD|
1/5/2000|	XOM|	39|	40.88|	38.91|	40.5|	17485000|	USD|
1/6/2000|	XOM|	40.31|	42.91|	40.09|	42.59|	19462000|	USD|
1/7/2000|	XOM|	42.97|	43.12|	42|	42.47|	16603800|	USD|

A brief overview of pre-processed tabular datasets to be analyzed. The first 5 Columns are displayed below.

Date	|Symbol	|Open	|High	|Low	|Close|	Volume|	Currency| Adj_close|Volume|Daily Change| Daily % Change| Price Range | Average Price| Volume Price Ratio | % Volatility| % Volume Change| Month |Weekdays
|-----|----|-----|-----|-----|----|-----|-----|----|----|-----|-----|-----|----|-----|-----|----|----|---|
1/3/2000|	XOM|	39.75|	40.38|	38.94|	39.16|	13458200|	USD|
1/4/2000|	XOM|	38.69|	39.09|	38.25|	38.41|	14510800|	USD|
1/5/2000|	XOM|	39|	40.88|	38.91|	40.5|	17485000|	USD|
1/6/2000|	XOM|	40.31|	42.91|	40.09|	42.59|	19462000|	USD|
1/7/2000|	XOM|	42.97|	43.12|	42|	42.47|	16603800|	USD|




## 🔍Exploratory Data Analysis

 ✒ How has the oil stock performed over time?
 
✒  Are there seasonal or weekday-based price patterns?

✒  How does trading volume influence price movement?

✒  When is the market most volatile?

✒  What strategic decisions can be made from historical behavior?

## Analysis Visualization

Chart Analysis 


## Analytical Insights

### EXCEL ###

1. Long-Term Price Trend (Years vs Average Close)

◻ Exxon’s stock shows a strong long-term upward trend, especially from the late 1990s onward.

◻ Major price accelerations occurred after 2000, aligning with global oil demand growth

◻ The most recent years show new highs, indicating renewed investor confidence and strong market performance.

🔷 **Key Insight**:
Exxon stock has historically rewarded long-term investors despite short-term volatility.

2. Seasonal Price Behavior (Average Close vs Months)

◻ Prices are not evenly distributed across the year.

◻ April to July records the highest average closing prices, peaking around July.

◻ September shows the lowest average close, suggesting a seasonal dip.

◻ End-of-year months (November–December) show a moderate recovery.

🔷 **Key Insight**:
Exxon stock exhibits seasonality, performing better in mid-year and weaker toward late Q3.

 3. Market Volatility Over Time (Average Daily Change % vs Years)
    
◻ Early decades show low daily price movement, indicating a more stable market.

◻ Volatility increases significantly after the 1990s, reflecting globalization and oil market sensitivity.

◻ Extreme positive and negative spikes appear during crisis periods, especially around 2020.

🔷 **Key Insight**:
Exxon stock has become more reactive to global events, highlighting higher risk but also higher trading opportunities.

4.  Trading Activity by Quarter (Volume Average by Year Quarter)

◻ Q1 has the highest average trading volume (27%), indicating strong start-of-year investor activity.

◻ Q2 and Q4 are balanced, each accounting for about 25%.

◻ Q3 has the lowest activity (23%), possibly due to market slowdowns or reduced investor engagement.

🔷 **Key Insight**:
Investor participation is strongest at the beginning of the year and weakest in Q3.

5. Total Trading Volume Over Time (Total Volume vs Years)
   
◻ Trading volume was very low in early decades, reflecting limited market participation.

◻ A massive surge in volume appears from the late 1990s to early 2010s

◻ Recent years maintain high but more controlled volumes.

🔷 **Key Insight**:
Volume spikes act as a market stress indicator, often signaling uncertainty or major news.

6. Price Growth Confirmation (Average Price % vs Years)

◻ Confirms a steady increase in Exxon’s valuation over time.

◻ Periodic declines occur, but each recovery tends to reach a higher level than before.

🔷 **Key Insight**:
Exxon demonstrates strong long-term capital appreciation, despite cyclical downturns.

### POWER-BI ###

1. Overall Market Snapshot (KPI Cards)
   
Metrics Analyzed:

◻ Max Close: 125.37

◻ Min Close: 1.44

◻ Max Volume: 118M

◻ Average Volatility: 1.74%

◻ 7-Day Moving Average: 106.47

◻ 30-Day Moving Average: 109.69

🔷 **Key Insight**:
The stock shows strong long-term growth with moderate volatility. The 30-day moving average above the 7-day average indicates a short-term pullback within a broader bullish trend.

2. Monthly Price Behavior (Average Open vs Average Close)

◻ Prices remain stable between 33–35 across most months.

◻ April to July records slightly higher averages.

◻ No extreme monthly price swings observed.

🔷 **Key Insight**: 
The stock exhibits predictable seasonality, making it suitable for structured entry and exit strategies.

3. Weekday Price Performance (Sum of Close)

◻ Wednesday records the highest cumulative closing values.

◻ Monday and Friday show relatively lower contributions.

🔷 **Key Insight**: Mid-week sessions reflect stronger price positioning than start- or end-of-week trading.

4.  Trading Volume by Weekday

◻ Friday has the highest trading volume.

◻ Monday also shows elevated volume, reacting to weekend news.

🔷 **Key Insight**: Liquidity peaks at the beginning and end of the trading week, improving trade execution quality.

5. Moving Average Trends (30-Day MA by Month)

◻ Monthly 30-day moving averages remain stable (~0.14–0.15M).

◻ Indicates sustained trend strength without speculative spikes.

🔷 **Key Insight**: The stock trend is steady and supported by consistent market participation.

6. Short-Term Momentum (7-Day MA by Weekday)

◻ Tuesday shows the strongest short-term momentum.

◻ Momentum gradually declines toward Friday and Monday.

🔷 **Key Insight**: Early-to-mid week sessions are optimal for short-term trading strategies.

7. Volume vs Price Relationship (Weekday Analysis)

◻ Higher trading volumes correlate with higher average closing prices.

◻ Monday records the lowest volume-price combination.

🔷 **Key Insight**: Volume acts as a confirmation signal for price movement rather than a standalone trigger.

8. Monthly Volume Change vs Price

◻ Months with high volume percentage changes often align with price increases.

◻ Volume spikes precede price movements.

🔷 **Key Insight**:Monitoring volume helps anticipate market direction early.

9. Volatility by Weekday

◻ Wednesday has the highest volatility.

◻ Friday shows the lowest volatility.

🔷 **Key Insight**:
Mid-week sessions offer higher risk and reward, while end-week trading suits conservative strategies.


## Actionable Recommendations

### EXCEL

1. Timing & Entry Strategy
   
◻ Recommendation: i) Prioritize stock accumulation between August–September, when average prices are historically lowest.
ii) Reduce aggressive buying during April–July, when prices tend to peak.

2. Long-Term Investment Strategy

◻ Recommendation:
 Maintain Exxon as a core long-term holding rather than a short-term speculative asset.

3. Volatility Risk Management

◻ Recommendation:
 Preparation should be made for sharp price movements during global economic or energy crises.

4. Volume-Based Trading Signals

◻ Recommendation:
Treat abnormal volume surges as early warning or opportunity signals.

5. Crisis-Period Opportunity Playbook

◻ Recommendation:
Treat major price crashes as structured buying opportunities, not panic exits.

6. Executive & Business-Level Decisions

◻ Recommendation:
Align corporate planning and forecasting with mid-year price strength and late-Q3 weakness.


### POWERBI

1.  Entry & Exit Timing

◻ Recommendation:

Accumulate positions during low-volatility months (e.g., February).

Take profits or re-balance during high-momentum months (April).

 2. Trend-Based Decision Making

◻ Recommendation:

Reduce buying when the 7-day MA falls below the 30-day MA.

Maintain long-term positions while the 30-day MA trends upward.

3. Weekday Optimization

◻ Recommendation:

Execute major trades Tuesday–Wednesday.

Avoid heavy trading on Mondays.

4. Volume-Driven Strategy

◻ Recommendation:

High volume + rising price → trend confirmation.

High volume + falling price → potential reversal.

 5. Volatility Risk Control

◻ Recommendation:

Use tighter stop-losses mid-week.

Increase position stability toward Fridays.

6. Liquidity Management

◻ Recommendation:

Rebalance portfolios on Fridays to reduce slippage.



## Portfolio Value 

📌 This project demonstrates my ability to:

📌 Translate raw financial data into insights

📌 Design executive-ready dashboards

📌 Generate strategic, data-backed recommendations

📌 Communicate complex analytics in human-friendly language

💻 📊
