### Using `pip` and `venv`
#### Create a Virtual Environment:
```
python -m venv venv
```

#### Activate the Virtual Environment:
**macOS/Linux:**
```
source venv/bin/activate
```

**Windows:**
```
venv\Scripts\activate
```

#### Install Dependencies:
```
pip install -r requirements.txt
```

---

### Using Conda
#### Create a Conda Environment:
```
conda create --name myenv python=3.11
```

#### Activate the Conda Environment:
```
conda activate myenv
```

#### Install Dependencies:
```
pip install -r requirements.txt
```
## Project Layout

### Phase 1 – Create AI Agent
1. Set up API Keys for Groq and Tavily.
2. Configure LLM & tools.
3. Develop the AI Agent with search tool functionality.
```
python ai_agent.py
```
### Phase 2 – Setup Backend (FastAPI)
1. Establish Pydantic models for schema validation.
2. Connect the AI Agent to handle frontend requests.
3. Run the application and explore API endpoints via Swagger UI.
```
python backend.py
```
### Phase 3 – Setup Frontend
1. Build the UI with Streamlit, including components for model selection, system prompt, and query input.
2. Integrate the frontend with the backend via API calls.
```
python frontend.py
```
###Note
##Make sure backend python script is running in a separate terminal
