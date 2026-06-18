# Decode Labs Trading Engine
## Project 1: Technical Analysis & Price Action

A systematic trading engine built during my Decode Labs internship.
The engine analyzes stock market data using technical indicators and 
a 3-gate decision system to identify high-probability entry points.

## How It Works
The engine runs every data point through 3 gates:
- Gate A: Is price at a support or resistance level?
- Gate B: Is the 50 EMA above the 200 EMA? (Bullish regime)
- Gate C: Is RSI above 50? (Momentum confirmed)

All three gates must pass before a trade signal is generated.

## Indicators Built
- Wick-to-Body Ratio (R_wb) — measures price rejection strength
- 50 and 200 day EMA — trend direction and regime detection
- Golden Cross and Death Cross — structural regime transitions
- RSI (14) — momentum confirmation

## Tech Stack
- Python
- Pandas
- yfinance

## Author
Stephanie — BSc Business Computing, JKUAT Kenya
