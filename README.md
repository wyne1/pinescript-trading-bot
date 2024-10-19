

# Custom Timeframe Comparison Indicator
![Tradingview](https://img.shields.io/badge/-TradingView-131622?style=flat&logo=tradingview&logoColor=white)
![Prinescript](https://img.shields.io/badge/-Pine%20Script-00B453?style=flat&logo=pinescript&logoColor=white)


## Overview

This Pine Script indicator for TradingView compares price action between two user-defined timeframes, providing visual cues and potential alert conditions based on various price relationships. It's designed to help traders identify potential trading opportunities by analyzing how lower timeframe price movements interact with higher timeframe levels.

## Features

- Compares a lower timeframe (15, 30, or 60 minutes) with a higher timeframe (4 hours, daily, weekly, or monthly)
- Analyzes multiple price relationships between the two timeframes
- Provides visual indicators on the chart for easy identification of conditions
- Includes potential alert conditions for automated notifications

## Installation

1. Open TradingView and navigate to the chart you want to add the indicator to.
2. Click on "Pine Editor" at the bottom of the screen.
3. Delete any existing code in the editor.
4. Copy and paste the entire script into the Pine Editor.
5. Click "Save" and give your indicator a name.
6. Click "Add to Chart" to apply the indicator.

## Usage

### Timeframe Selection

- Lower Timeframe: Choose between 15, 30, or 60 minutes
- Higher Timeframe: Choose between 4 hours (4H), daily (D), weekly (W), or monthly (M)

### Conditions Analyzed

The indicator analyzes several conditions comparing the lower timeframe to the higher timeframe:

1. Lower timeframe close/open vs. Higher timeframe open
2. Lower timeframe close/open vs. Higher timeframe previous high
3. Lower timeframe close/open vs. Higher timeframe previous low
4. Lower timeframe close/open vs. Higher timeframe previous close
5. Additional comparisons between current lower timeframe and higher timeframe levels

### Visual Indicators

The script plots shapes on the chart to indicate when various conditions are met:

- Green shapes above bars indicate bullish conditions
- Red shapes below bars indicate bearish conditions

Shape meanings:
- Triangle: Condition 1
- Circle: Condition 2
- Square: Condition 3
- Diamond: Condition 4

### Alerts

While the script includes code for alert conditions, they are currently commented out. To enable alerts:

1. Uncomment the desired `alertcondition()` lines in the script.
2. Save and reload the indicator.
3. Set up alerts in TradingView using the newly available alert conditions.

## Customization

You can customize the indicator by modifying the script:

- Change the available timeframe options
- Adjust the conditions being checked
- Modify the visual indicators (colors, shapes, sizes)
- Enable or disable specific alert conditions

## Disclaimer

This indicator is for informational and educational purposes only. Always conduct your own analysis and consider your risk tolerance before making trading decisions.
