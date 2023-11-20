# Uni Bot MT4

Uni Bot MT4 is an expert advisor developed by the Forex Robot Easy Team. It is a trendy neural network forex software designed for professional traders. This code is a sample implementation of the Uni Bot MT4 strategy.

## Functionality

The Uni Bot MT4 expert advisor analyzes market trends and executes trades based on the following conditions:

- If the moving average value, RSI value, and MACD value are all positive, a buy order is opened.
- If the moving average value, RSI value, and MACD value are all negative, a sell order is opened.

The expert advisor also monitors open positions and manages exits, as well as records trade history.

## Usage

To use the Uni Bot MT4 expert advisor, follow these steps:

1. Include the necessary libraries: Trade.mqh, MovingAverages.mqh, RSI.mqh, and MACD.mqh.
2. Define the constants according to your preferences: SYMBOL, TIMEFRAME, LOT_SIZE, STOP_LOSS, and TAKE_PROFIT.
3. Create objects for the moving averages, RSI, MACD, and trade functions.
4. Initialize the indicators and set their parameters in the OnInit() function.
5. In the OnTick() function, calculate the indicator values and check the trading conditions. Open buy or sell orders accordingly.
6. Monitor open positions and manage exits using the MonitorPositions() function.
7. Record trade history using the RecordTradeHistory() function.
8. Clean up resources in the OnDeinit() function.
9. Initialize trade functions in the OnStart() function and run the expert advisor in a loop.

Please note that this code is a sample implementation and may need to be modified according to your specific needs and trading strategy.

## Disclaimer

ForexRobotEasy is not the official developer of Uni Bot MT4. We only provide sample code that can work as described in the product. For detailed reviews and trading results of this product, please visit [https://forexroboteasy.com/forex-robot-review/uni-bot-mt4-review-a-trendy-neural-network-forex-software-for-professional-traders/](https://forexroboteasy.com/forex-robot-review/uni-bot-mt4-review-a-trendy-neural-network-forex-software-for-professional-traders/). To find the official developer of this product, please use MQL5.
