AI Research Agent 

An intelligent research assistant built using LangChain, OpenAI GPT-4, and custom tools.  
This agent can perform research tasks, use tools, and generate structured research responses.

->Features

- Tool-calling AI agent
- Structured output using Pydantic
- Custom tools integration (Search, Wiki, Save)
- Modular architecture
- Environment-based configuration
- Easy to extend

 Tech Stack

- Python 3.12
- LangChain
- OpenAI GPT-4
- Pydantic
- dotenv

---

## 📂 Project Structure
AIAGENTS/
│
├── main.py # Main agent logic
├── tools.py # Custom tools
├── requirements.txt # Dependencies
├── .gitignore
└── README.md


->Setup Instructions:

->Clone Repository
git clone https://github.com/pavaniravalkol/AIAGENTS.git
cd AIAGENTS

->create virtual environment:
python3 -m venv venv
source venv/bin/activate   # Mac
 
->install dependencies:
pip install -r requirements.txt

->Set Environment Variables:
Create a .env file:
OPENAI_API_KEY="key"

->Run the Agent:
python main.py

