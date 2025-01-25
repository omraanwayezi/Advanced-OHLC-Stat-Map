# Advanced-OHLC-Stat-Map
Tradingview indicator coded in pinescript V5 that projects statistical OHLC levels for traders to refer to


This indicator is designed to assist traders in identifying significant price levels and potential market behaviors using historical weekly or daily data. It provides a structured approach to understanding price movements through customizable visualizations and precise calculations.

Key Features:
1. Weekly and Daily Levels

2. Displays key levels for either the weekly or daily timeframe, depending on user settings. Offers clear insights into market structure and potential turning points.

3. Adjustable Lookback Period

4. Allows users to set the lookback period for historical data analysis.
Levels are calculated using a mean average, ensuring a balanced view of past market behavior.
Customizable Visualizations

5. Provides fully customizable level lines, enabling users to adjust colors, thickness, and style to suit their preferences and chart aesthetics.
Candle Open and Market Behavior Levels

6. Marks the open price for the current daily candle, providing a reference point for intraday analysis.

7. Identifies potential manipulation and distribution levels, offering insights into possible reversals and trend continuations.

How It Works:
The indicator uses historical price data to calculate levels based on patterns and movements observed over specific periods.

Level Calculations:

For daily levels, the tool analyzes historical data (e.g., the last 60 Mondays for a Monday's levels).
It splits each day into its open, high, low, and close (OHLC) values.
It evaluates how far the price moved against the final direction of the day (manipulation levels) and with the final direction (distribution levels).

Exclusion of Non-Valid Data:

To maintain accuracy, certain edge cases—such as candles without wicks—are excluded from calculations.

When using the indicator on Futures charts please make sure to use ONLY the continuous chart so that there is enough data for the calculations.
