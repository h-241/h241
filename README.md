# h241

```python
import h241

client = h241.Client(account_api='..')


...


agent = SomeLangchainAgent()
agent.add_tool(client.hire_worker)
```
