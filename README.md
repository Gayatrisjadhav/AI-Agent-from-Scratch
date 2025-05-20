# AI-Agent-from-Scratch

# 🧠 AI Agent from Scratch

A minimal and modular AI Agent built using [LangChain](https://www.langchain.com/), [Groq](https://groq.com/), and DuckDuckGo for web search. This project demonstrates how to build a tool-using autonomous agent that can retrieve live information from the web and respond with structured summaries.

---

## 🚀 Features

- 🔍 Web search capability via DuckDuckGo
- 🧠 Language reasoning powered by Groq's Mixtral or LLaMA models
- 🛠 Tool-calling agent architecture with structured outputs
- 📦 Modular design using LangChain tool interfaces

---

## 🏗 Project Structure

AI-Agent-from-Scratch/
├── main.py # Entry point for the agent
├── tools.py # Custom tools like DuckDuckGo search
├── utils.py # Optional helpers (not required initially)
├── README.md # Project documentation
└── requirements.txt # Python dependencies


---

## 🧑‍💻 Usage

### 1. Install Dependencies

git clone https://github.com/Gayatrisjadhav/AI-Agent-from-Scratch.git
cd AI-Agent-from-Scratch
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
pip install -r requirements.txt

GROQ_API_KEY=your_groq_api_key_here

# Run the Agent

python main.py run



  
