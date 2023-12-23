# IMA Finder MT5 ReadMe File

This ReadMe file provides a brief overview of the IMA Finder MT5 code. It explains the purpose of the code, its input parameters, and how it functions as a custom indicator in MetaTrader 5 (MT5).

## Description

The IMA Finder MT5 is a custom indicator designed to identify when the Moving Origin indicator surpasses the current price. It can send signals in the form of alerts, emails, or notifications to notify the user when this event occurs.

For detailed reviews and trading results of this product, visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/ima-finder-mt5-review-optimize-forex-trading-with-real-time-alerts/). Please note that Forex Robot Easy is not the official developer of this product. They only provide sample code that demonstrates how the product works.

## Indicator Input Parameters

The IMA Finder MT5 has the following input parameters:

- `SymbolName` (string): The symbol name.
- `Timeframe` (ENUM_TIMEFRAMES): The timeframe.
- `Period` (int): The period.

## Signal Sending Parameters

The IMA Finder MT5 can send signals based on the following parameters:

- `SendSignals` (bool): Enable or disable signal sending.
- `SignalType` (int): Specify the type of signal (1 - alert, 2 - email, 3 - notification).
- `SignalMessage` (string): The message to be sent as a signal.

## Global Variables

The IMA Finder MT5 uses the following global variables:

- `iMA_Buffer` (double[]): Buffer for storing Moving Origin indicator values.

## Custom Indicator Initialization Function

The `OnInit()` function is responsible for initializing the Moving Origin indicator. It sets the indicator's properties and parameters, such as the short name, levels, digits, buffers, and colors.

## Custom Indicator Iteration Function

The `OnCalculate()` function is the main calculation function of the indicator. It calculates the Moving Origin indicator values and checks if the current price surpasses the last indicator value. If it does, it sends the specified signal and prints a signal information message.

## Product Description

The IMA Finder MT5 is a custom indicator that helps traders optimize their forex trading by providing real-time alerts when the Moving Origin indicator surpasses the current price. It can be used with any symbol and timeframe in MetaTrader 5.

To use the IMA Finder MT5, simply attach it to a chart in MT5 and configure the input parameters according to your preferences. You can enable or disable signal sending, choose the type of signal (alert, email, or notification), and customize the signal message.

Please note that Forex Robot Easy is not the official developer of the IMA Finder MT5. They only provide sample code for demonstration purposes. To find the official developer of this product and access its full features and support, please refer to the MQL5 community.

For detailed reviews and trading results of this product, visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/ima-finder-mt5-review-optimize-forex-trading-with-real-time-alerts/).
