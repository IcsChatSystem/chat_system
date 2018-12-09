To solve “address already in use”
Mac :
lsof -i:1112
Kill [PID]

Or

ps -fA | grep python
Kill [PID]