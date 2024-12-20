# Futures Contract Calculator

A simple web-based tool to calculate the maximum number of futures contracts you can trade based on your account buffer, fallback days, and stop loss. The tool ensures you stay within your risk limits while trading.

## Features

- **Contract Selection**: Choose from various futures contracts like MNQ, NQ, MGC, etc., with predefined tick values.
- **Stop Loss Flexibility**: Input your stop loss in ticks or points, dynamically converted to dollars.
- **Risk Management**: Calculates the maximum contracts you can trade based on your account buffer and fallback days.
- **Dynamic Output**: Provides total stop loss in dollars and highlights the recommended number of contracts or suggests "Do Not Trade" if the risk exceeds your limit.
- **User-Friendly Design**: Modern UI using TailwindCSS, with results displayed in a clean modal popup.

## How to Use

1. Open the `index.html` file in any modern browser.
2. Fill in the following fields:
   - **Contract**: Select the futures contract you're trading.
   - **Buffer**: Enter your account buffer in dollars.
   - **Fallback Days**: Input the number of days you want your buffer to sustain.
   - **Stop Loss**: Enter your stop loss in ticks or points.
3. Click **Calculate** to view results in a popup.
4. The tool will suggest the maximum contracts you can trade or indicate if trading is too risky.

## Example

### Input:

- Contract: MNQ
- Buffer: $2,500
- Fallback Days: 7
- Stop Loss: 20 ticks

### Output:

- Tick Value: $0.50
- Total Stop Loss: $150.00
- Daily Max Loss: $357.14
- **Max Contracts**: 2

## Technology Used

- **HTML5**: For structure.
- **TailwindCSS**: For modern, responsive styling.
- **JavaScript**: For interactive calculations and dynamic updates.

## License

This project is open-source and free to use.
