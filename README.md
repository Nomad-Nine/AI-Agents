# AI-Agents
MAS and Agentic systems Demo.
Notebooks:
- `it_incident_multi-agent.ipynb`: Basic Multi-Agent System (MAS)
- `it_incident_agentic.ipynb`: Agentic System with single agent.

These notebooks were developed using the [Databric Free Edition](https://www.databricks.com/learn/free-edition), but they can be run in other platforms. The only required change would be the model:

```
from databricks_langchain import ChatDatabricks

llm = ChatDatabricks(
    endpoint="databricks-meta-llama-3-3-70b-instruct", 
    temperature=0,
)
```

To display notebooks in Github, use the [nbviewer](https://github.com/jupyter/nbviewer) or open the files with github.dev. 

The  associated article is available [here](https://medium.com/@tsiciliani/ai-agents-for-real-time-it-incident-response-3ce62dad43b0) and [here](https://tsicilian.wordpress.com/).
