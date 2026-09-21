# Pine Script Trading Bot

This repository is open to feedback from developers experienced with **Pine Script, TradingView strategies, technical analysis, alerts, and algorithmic trading**.

> **Disclaimer:** This project is for educational and research purposes only. It is not financial advice. Trading involves significant risk, and past performance does not guarantee future results. Always test carefully using TradingView’s replay and paper-trading features before considering live use.

## Project Goals

The goals of this project are to:

- Develop and test this Pine Script trading strategy
- Improve the accuracy and reliability of entry and exit conditions
- Create useful TradingView alerts
- Understand the difference between backtesting and real-time execution
- Reduce repainting and other common strategy problems
- Learn from experienced Pine Script developers
- Build code that is easier to understand, test, and maintain

## Current Status

This project is currently under development.

I am looking for help with:

- Reviewing the Pine Script code
- Improving strategy logic
- Fixing errors and unexpected behavior
- Understanding TradingView strategy results
- Checking for repainting or lookahead problems
- Improving alert conditions
- Making the code more efficient and reliable
- Explaining Pine Script concepts and best practices

## How to Use

1. Open the Pine Script file in this repository.
2. Copy the code.
3. Open [TradingView](https://www.tradingview.com/).
4. Open the **Pine Editor**.
5. Paste the code into a new script.
6. Save the script.
7. Add it to a chart.
8. Test it using historical data, Bar Replay, and paper trading.

Before using the script, review all inputs, entry conditions, exit conditions, position-sizing rules, and alert settings.

## Information Needed When Requesting Help

When opening an Issue or Discussion, please include as much of the following information as possible:

- Pine Script version, such as Pine Script v5 or v6
- The name of the file or section causing the problem
- The exact error message
- What you expected the script to do
- What the script actually does
- Whether the problem occurs during:
  - Historical backtesting
  - Bar Replay
  - Real-time chart execution
  - TradingView alerts
- The chart timeframe and symbol used
- Relevant indicator or strategy settings
- A screenshot, if it helps explain the issue
- A small, reproducible code example when possible

Please remove private information before posting code or screenshots. Do not share API keys, passwords, webhook secrets, broker credentials, or private account information.


## Known Areas for Review

The following areas may need review and improvement:

- Entry and exit conditions
- Stop-loss and take-profit calculations
- Position sizing
- Commission and slippage settings
- Repainting and lookahead behavior
- Use of `request.security()`
- Bar confirmation and real-time calculations
- `alertcondition()` and strategy alerts
- Duplicate alerts
- Signals appearing differently in backtesting and live conditions
- Timezone and session handling
- Performance across different symbols and timeframes


## Contributing

Contributions, suggestions, bug reports, and code reviews are welcome.

Before submitting a change:

1. Explain what problem the change solves.
2. Keep changes focused and easy to review.
3. Test the script in TradingView.
4. Check both historical and real-time behavior where possible.
5. Explain any changes to trading logic.
6. Include screenshots or test results when useful.
7. Do not include private credentials or secrets.

For larger changes, please open an Issue or Discussion first so the approach can be reviewed before code is changed.

## Questions and Discussions

If you have experience with Pine Script or TradingView strategies, your help is welcome.

Useful areas of expertise include:

- Pine Script development
- TradingView strategy testing
- Technical indicators
- Algorithmic trading
- Trading alerts and webhooks
- Repainting prevention
- Backtesting methodology
- Risk management
- Code organization and debugging

Please be respectful and explain the reasoning behind suggested changes. Educational explanations are especially helpful because they make it easier to understand and maintain the project.

## Risk Warning

This script can produce incorrect signals, unexpected results, or losses. It may contain bugs and may not work correctly in all market conditions, symbols, or timeframes.

Never rely on this script without performing your own testing and evaluation. Do not risk money you cannot afford to lose.

