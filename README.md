# Bitcoin Algorithmic Trading Strategy

This repository contains a **Bitcoin algorithmic trading strategy** built using Python. The strategy leverages **Ichimoku Cloud, technical indicators, market trends, and risk management principles** to automate trading decisions efficiently.

## ✨ Key Features

- **Real-time Market Data Processing**: Fetches and analyzes Bitcoin price data for informed decision-making.
- **Technical Indicators**: Utilizes `pandas_ta` and `ta` for comprehensive trend analysis.
- **Ichimoku Cloud Strategy**: Implements Tenkan-sen, Kijun-sen, and cloud structure to generate trade signals.
- **Backtesting Capabilities**: Simulates historical performance for strategy evaluation.
- **Risk Management**: Employs stop-loss mechanisms and leverage control to mitigate risk.
- **Trade Execution**: Integrates `untrade-sdk` for seamless order placement.

## 📈 Performance Highlights

### **Backtest Results (2018 - 2024)**

- **Total Trades**: 160
- **Win Rate**: 55%
- **Net Profit**: \$7,941.98
- **Maximum Drawdown**: 13.72%
- **Sharpe Ratio**: 6.58
- **Sortino Ratio**: 35.10
- **Benchmark Return**: 628.94%

### **Compound Statistics**

- **Final Balance**: \$676,836.69 (starting with \$1,000)
- **Profit Percentage**: 67,583.67%
- **Maximum Portfolio Balance**: \$678,990.92
- **Total Fee Paid**: \$26,181.54

## 💡 How It Works

1. **Data Preprocessing**: Loads and formats historical BTC price data.
2. **Ichimoku Cloud Computation**: Calculates Tenkan-sen, Kijun-sen, Senkou Span A & B to confirm trends.
3. **Indicator Computation**: Applies RSI, MACD, moving averages, and other indicators for additional validation.
4. **Trade Execution**: Places buy/sell orders based on predefined trade signals.
5. **Performance Evaluation**: Computes key metrics, including returns, risk-adjusted ratios, and drawdowns.

## ⚡ Installation

```sh
pip install ta pandas_ta tqdm
pip install ./untrade-sdk/.
```

## 🔧 Usage

To backtest and evaluate the strategy, run the Jupyter Notebook:

```sh
jupyter notebook BTC_strategy.ipynb
```

## 🎯 Final Remarks

This algorithmic trading strategy has demonstrated **exceptional performance** over the backtest period. Starting with an initial investment of **$1,000**, the strategy grew the portfolio to an impressive **$676,836.69**, achieving a **67,583.67% profit**. 

By leveraging **Ichimoku Cloud signals**, smart risk management, and a well-calibrated trading framework, this strategy has shown a strong ability to capture profitable opportunities while managing downside risks. While past performance is not indicative of future results, this strategy highlights the potential for **significant returns** when deployed effectively.

## ⚠ Disclaimer

This strategy is for **educational purposes only**. 

---

