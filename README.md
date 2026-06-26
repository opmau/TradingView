# TradingView Pine Scripts

A collection of custom TradingView Pine Script indicators, strategies, and libraries.

## Overview

[Pine Script](https://www.tradingview.com/pine-script-docs/en/v5/Introduction.html) is TradingView's domain-specific language for writing custom technical analysis indicators, strategies, and libraries directly on the TradingView platform.

## Repository Structure

```
TradingView/
├── indicators/        # Custom technical indicators
├── strategies/        # Backtestable trading strategies
└── libraries/         # Reusable Pine Script libraries
```

## Getting Started

1. Open [TradingView](https://www.tradingview.com/) and navigate to a chart.
2. Click **Pine Editor** at the bottom of the screen.
3. Copy the contents of any `.pine` file from this repository into the editor.
4. Click **Add to chart** to apply the script.

## Indicators

| Script | Description |
|--------|-------------|
| [Simple Moving Average](indicators/simple_moving_average.pine) | Plots configurable SMA with optional EMA overlay |
| [RSI with Signals](indicators/rsi_with_signals.pine) | Relative Strength Index with overbought/oversold signals |

## Strategies

| Script | Description |
|--------|-------------|
| [SMA Crossover Strategy](strategies/sma_crossover_strategy.pine) | Long/short entries based on fast/slow SMA crossovers |

## Libraries

| Script | Description |
|--------|-------------|
| [Math Utils](libraries/math_utils.pine) | Common math helper functions for Pine Script |

## Pine Script Version

All scripts in this repository target **Pine Script v5** unless otherwise noted in the script header.

## Contributing

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/my-script`.
3. Add your `.pine` script to the appropriate directory.
4. Include a comment header in your script with a description, version, and author.
5. Update `README.md` to reference your new script.
6. Open a pull request.

### Script Header Convention

```pine
// @version=5
// @description My Script Description
// @author YourName
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
