# Basic LLM Chatbot (LangGraph + OpenAI)

A simple CLI chatbot using LangGraph and LangChain OpenAI.

## Features
- Command-line chat loop
- LangGraph state graph
- Uses OpenAI chat model via `ChatOpenAI`

## Setup

### 1) Clone the repo
```bash
git clone <https://github.com/Subhaga2000/llm-chatbot.git>
cd llm-chatbot
```

### 2) Create and activate a virtual environment
```bash
#Windows (PowerShell)
python -m venv venv
venv\Scripts\activate

#Mac/Linux
python -m venv venv
source venv/bin/activate
```
### 3) Install dependencies
```bash
pip install -r requirements.txt
```

### 4) Add your OpenAI API key
```bash
##Create a .env file in the project root:
OPENAI_API_KEY=your_openai_key_here
```

### 5) Run
```bash
python agent1.py
```
