# CAP-Zone-Recovery-EA-Pro-MT5

# Creating a Readme text for the Cerberus Equity Watcher MQL5 code

readme_text = """
# Cerberus Equity Watcher

## Overview
Cerberus Equity Watcher is a Forex software tool designed for risk management in Forex trading. It actively monitors account equity, offering protection against significant drawdowns caused by faulty Expert Advisors (EAs) or emotional trading decisions.

## How It Works
- Monitors the account's equity in real-time.
- Automatically flattens all positions and kills all EAs if the equity reaches pre-set minimum or maximum values.
- Sends notifications to the user's mobile phone and displays messages on the screen.
- Performs checks on user inputs and current status of automatic trading to ensure correct operation.

## Setup and Configuration
- **MaxEquity**: Set the maximum equity threshold.
- **MinEquity**: Set the minimum equity threshold.

Modify these input parameters in the EA's settings as per your trading requirements.

## Usage
1. Attach the EA to a single chart of your choice in the MT5 platform.
2. Ensure that the EA has permissions to trade and access to the internet for sending notifications.

## Dependencies
This software requires the MetaTrader 5 platform to run.

## Safety and Testing
- Thoroughly backtest the EA on a demo account before using it on a live account.
- Adjust the equity thresholds according to your risk tolerance and account size.

## Feedback and Support
Users are encouraged to share their experiences and insights. For independent testing results and updates, visit [ForexRobotEasy](https://forexroboteasy.com/forex-robot-review/review-cap-zone-recovery-ea-pro-mt5-turn-losing-trades-into-winning-trades/).

## Disclaimer
Trading Forex involves substantial risk and there is always the potential for loss. Your trading results may vary. This tool is not a guarantee of future performance and is for educational purposes only.
"""

# Save the text to a README file
path = '/mnt/data/Cerberus_Equity_Watcher_README.md'
with open(path, 'w') as file:
    file.write(readme_text)

path
