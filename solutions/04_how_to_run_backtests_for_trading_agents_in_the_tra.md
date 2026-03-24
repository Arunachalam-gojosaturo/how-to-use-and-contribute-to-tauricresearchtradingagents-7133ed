# How to run backtests for trading agents in the TradingAgents repository

_Use the `backtest` command to run backtests for trading agents_

## Steps

1. Navigate to the TradingAgents repository using `cd TradingAgents`
2. Activate the virtual environment using `source venv/bin/activate` on Linux/Mac or `venv\Scripts\activate` on Windows
3. Run the backtest command using `python backtest.py --agent agent_name --start_date 2020-01-01 --end_date 2020-12-31`
4. View the backtest results using `python backtest.py --agent agent_name --start_date 2020-01-01 --end_date 2020-12-31 --plot`
5. Adjust the backtest parameters, such as the start and end dates, to suit your needs

## Pitfalls

- Not specifying the correct agent name, which can cause the backtest to fail