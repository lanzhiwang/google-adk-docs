```bash

docker run -ti --rm -v "$(pwd)":/app -w /app python:3.12.1-bullseye bash

pip install google-adk==1.22.1 litellm==1.81.0 black[jupyter]==26.1.0

$ adk create agent_team
Choose a model for the root agent:
1. gemini-2.5-flash
2. Other models (fill later)
Choose model (1, 2): 1
1. Google AI
2. Vertex AI
Choose a backend (1, 2): 1

Don't have API Key? Create one in AI Studio: https://aistudio.google.com/apikey

Enter Google API key: YOUR_GOOGLE_API_KEY

Agent created in /app/learn/01/agent_team:
- .env
- __init__.py
- agent.py

$

```