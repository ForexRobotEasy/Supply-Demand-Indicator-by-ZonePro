# Supply Demand Indicator

## Description

The Supply Demand Indicator is a custom indicator developed by the Forex Robot Easy Team. This indicator is designed to identify supply and demand zones in the market, which can be used by traders to make informed trading decisions.

## Features

- The indicator considers multiple higher timeframes to identify supply and demand zones.
- Different colors are used to distinguish fresh, tested, broken, old, and nested zones.
- Alerts can be enabled to receive notifications when zones are identified.
- Repainting can be enabled to update the zones in real-time.

## Installation

To install the Supply Demand Indicator, follow these steps:

1. Download the indicator file.
2. Open your MetaTrader platform.
3. Click on 'File' in the menu and select 'Open Data Folder'.
4. Open the 'MQL5' folder and then the 'Indicators' folder.
5. Copy the downloaded indicator file into the 'Indicators' folder.
6. Restart your MetaTrader platform.

## Usage

Once the indicator is installed, you can add it to the chart by following these steps:

1. Open the desired chart.
2. Click on 'Insert' in the menu and select 'Indicators'.
3. Navigate to the 'Custom' tab and select the Supply Demand Indicator.
4. Adjust the input parameters according to your preferences.
5. Click 'OK' to apply the indicator to the chart.

The indicator will then display the supply and demand zones on the chart using different colors.

## Customization

The Supply Demand Indicator provides several input parameters that can be customized:

- **higherTimeframes**: Number of higher timeframes to consider.
- **freshZoneColor**: Color for fresh zones.
- **testedZoneColor**: Color for tested zones.
- **brokenZoneColor**: Color for broken zones.
- **oldZoneColor**: Color for old zones.
- **nestedZoneColor**: Color for nested zones.
- **alertsEnabled**: Enable or disable alerts.
- **repaintEnabled**: Enable or disable repainting.

## Trading Logic

The indicator also includes custom trading functions and trading logic that can be used to develop trading strategies based on the identified supply and demand zones. These functions include:

- **drawFreshZone**: Drawing code for fresh zone.
- **drawTestedZone**: Drawing code for tested zone.
- **drawBrokenZone**: Drawing code for broken zone.
- **drawOldZone**: Drawing code for old zone.
- **drawNestedZone**: Drawing code for nested zone.
- **isZoneTouched**: Check if zone is touched.
- **isZoneEntered**: Check if zone is entered.
- **isZoneBroken**: Check if zone is broken.
- **isCandleReversal**: Check if reversal candle leaves the zone.
- **getPipSize**: Calculate pip size for nested zone.
- **getPreviousTouches**: Get number of previous touches on the zone.

## Disclaimer

Please note that the Forex Robot Easy Team is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please refer to the MQL5 website.

## Reviews and Trading Results

For detailed reviews and trading results of this product, please visit [Forex Robot Easy's review](https://forexroboteasy.com/forex-robot-review/zonepro-forex-software-review-of-reliable-supply-demand-indicator/).
