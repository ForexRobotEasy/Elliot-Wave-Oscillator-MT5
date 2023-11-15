# Elliot Wave Oscillator

This code is an example implementation of the Elliot Wave Oscillator, which is a custom indicator used in trading strategies. The indicator calculates the difference between a fast exponential moving average (EMA) and a slow EMA, with a smoothing period applied to the result.

## Parameters
- `fast_ema_period`: The period used for the fast EMA calculation (default value: 5).
- `slow_ema_period`: The period used for the slow EMA calculation (default value: 35).
- `smoothing_period`: The period used for smoothing the difference between the fast and slow EMAs (default value: 5).

## Trading Strategy
The code also includes a trading strategy parameter (`trade_strategy`) that can be set to three different values:
- `TRADE_STRATEGY_HOLD`: This is the default strategy and does not implement any specific trading actions.
- `TRADE_STRATEGY_SCALPING`: This strategy can be implemented to perform scalping trades.
- `TRADE_STRATEGY_SWING`: This strategy can be implemented to perform swing trades.

## Custom Functions
The code includes several custom functions that can be used for additional functionality:
- `SendAlert`: This function can be used to send alerts to the MT5 Terminal and mobile phones.
- `SendNotification`: This function can be used to send notifications to the MT5 Terminal and mobile phones.

## Additional Information
This code is an example and not an exact copy of the original product developed and published on the MQL5 website by forexroboteasy.com. For detailed reviews and trading results of the official product, please visit [here](https://forexroboteasy.com/forex-robot-review/review-elliot-wave-oscillator-mt5-a-powerful-forex-software-for-accurate-wave-counts/).

Please note that this code serves as an approximate description of the necessary parameters for the operation of the product, based on the original product description.
