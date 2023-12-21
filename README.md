# Market Reversal Alerts

This code is a custom indicator that identifies potential market reversals based on breakout patterns and price behavior. It is developed by the Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/market-reversal-alerts-review-and-download-the-profitable-forex-software/).

## Input Parameters

1. `breakoutPeriod` (default: 20): Number of candles to consider for breakout identification.
2. `trailPeriod` (default: 10): Number of candles to trail the rectangle.
3. `rectangleWidth` (default: 0.001): Width of the rectangle in percentage of the candle's range.

## Global Variables

1. `prevHigh`, `prevLow`: Previous high and low prices.
2. `breakoutUp`, `breakoutDown`: Flags for breakout identification.
3. `drawRectangle`: Flag to indicate if a rectangle should be drawn.
4. `rectangleTop`, `rectangleBottom`: Rectangle top and bottom levels.

## Indicator Initialization

The `OnInit()` function initializes the indicator by setting the initial values of the global variables and flags.

## Indicator Calculation

The `OnCalculate()` function is called for each new candle in the chart. It iterates through the new candles and performs the following steps:

1. Identifies breakouts by comparing the current high and low prices with the previous high and low prices.
2. Draws a rectangle and trails it if the `drawRectangle` flag is set.
3. Detects price closing above or below the rectangle to identify potential market reversals.
4. Updates the previous high and low prices for the next iteration.

## Product Description

Market Reversal Alerts is a powerful custom indicator developed by the Forex Robot Easy Team. It is designed to help traders identify potential market reversals based on breakout patterns and price behavior.

The indicator uses a combination of breakout identification and rectangle drawing techniques to highlight potential reversal areas on the chart. It calculates the breakout based on a specified number of candles and trails the rectangle for a defined number of periods.

Once a breakout is identified and a rectangle is drawn, the indicator continuously monitors the price action. If the price closes above or below the rectangle, it generates an alert indicating a potential shift in market structure. This can be a valuable signal for traders looking to enter or exit positions.

Market Reversal Alerts is highly customizable, allowing traders to adjust the breakout period, trail period, and rectangle width according to their trading style and preferences. It can be used on any time frame and with any currency pair.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that demonstrates how the indicator works. To find the official developer and access detailed reviews and trading results of this product, please visit the [official website](https://forexroboteasy.com/forex-robot-review/market-reversal-alerts-review-and-download-the-profitable-forex-software/) or use MQL5.
