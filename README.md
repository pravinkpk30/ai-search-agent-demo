# ai-search-agent-demo

This is a demo of a search agent using langchain.

# Create virtual environment

```bash
python -m venv venv
source venv/bin/activate
```

# Install dependencies

```bash
pip install -r requirements.txt
```

# Run the demo

```bash
python main.py
```

# Output

```bash
(venv) praveenkumar@Praveens-MacBook-Pro ai-search-agent-demo % python ./main.py
What can i help you research? About whale sea creature and save it in file

> Entering new AgentExecutor chain...
```json
{"topic": "Whales", "summary": "Whales are marine mammals that belong to the order Cetacea. They are divided into two suborders: baleen whales (Mysticeti) and toothed whales (Odontoceti). Whales are found in oceans all over the world and play an important role in marine ecosystems. Many species are threatened or endangered due to hunting, habitat loss, and climate change.", "sources": ["Wikipedia", "Web search"], "tools_used": ["wikipedia", "search", "save_text_to_file"]}
``` 

> Finished chain.
```json 
{'topic': 'Whales', 'summary': 'Whales are marine mammals that belong to the order Cetacea. They are divided into two suborders: baleen whales (Mysticeti) and toothed whales (Odontoceti). Whales are found in oceans all over the world and play an important role in marine ecosystems. Many species are threatened or endangered due to hunting, habitat loss, and climate change.', 'sources': ['Wikipedia', 'Web search'], 'tools_used': ['wikipedia', 'search', 'save_text_to_file']}
```
