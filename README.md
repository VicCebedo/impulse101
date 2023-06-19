# impulse101
A cryptocurrency Buy and Sell signal indicator:
https://www.tradingview.com/script/4KGwTg9e-VCC-Impulse-101/

---

> BUY SIGNAL (green background) is triggered if Buy Score (black line) reaches (4) Points.

1 Point is added to Buy Score if:
- The Closing Price is above all Moving Averages (7, 21, 50, 100, and 200), and
- If the 200MA is above the other Moving Averages (7, 21, 50, 100).

1 Point is added to Buy Score if:
- MACD is greater than MACD Signal, and
- MACD is greater than zero, and
- MACD Signal is greater than zero, and
- MACD is greater than previous value.

1 Point is added to Buy Score if:
- SMI is greater than zero, and
- SMI is greater than previous value.

1 Point is added to Buy Score if:
- RSI is greater than 50.

--- 

> The SELL SIGNAL (red background) is triggered if
> EITHER Ethereum Sell Score (purple line)
> OR Bitcoin Sell Score (red line), reaches (-3) Points.

2 Points is deducted from the Ethereum Sell Score if:
- The number of Ethereum Short positions is greater than the Longs.

1 Point is deducted from the Ethereum Sell Score if:
- The Ethereum RSI is greater than 75.

2 Points is deducted from the Bitcoin Sell Score if:
- The number of Bitcoin Short positions is greater than the Longs.

1 Point is deducted from the Bitcoin Sell Score if:
- The Bitcoin RSI is greater than 75.
