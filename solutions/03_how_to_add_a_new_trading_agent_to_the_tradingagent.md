# How to add a new trading agent to the TradingAgents repository

_Create a new class for the trading agent and add it to the repository_

## Steps

1. Create a new file for the trading agent class using `touch agents/new_agent.py`
2. Define the new trading agent class in the file, inheriting from the base `Agent` class
3. Implement the necessary methods for the trading agent, such as `buy` and `sell`
4. Add the new trading agent to the `agents` dictionary in the `main.py` file
5. Test the new trading agent using `python main.py --agent new_agent`

## Pitfalls

- Not following the existing coding style and conventions in the repository