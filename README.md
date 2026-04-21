💸 FinAdvise – AI-Powered Personal Finance Assistant
FinAdvise is a LangGraph-based AI agent system designed to help users manage personal finance through intelligent conversations.

🚀 Features


🧠 Intent detection (profile, stock, budget, advice)


💾 Memory management (short-term & long-term)


📈 Real-time stock data via Alpha Vantage API


🤖 Personalized financial advice using LLM


⚠️ Human-in-the-Loop for high-risk queries


💬 Interactive chat UI using Streamlit



🧠 Architecture
Built using LangGraph, enabling:


State-based workflows


Multi-node AI pipelines


Conditional execution


Modular agent design



🛠 Tech Stack


Python


LangGraph


LangChain


Groq (LLaMA 3 Model)


Streamlit


Alpha Vantage API


dotenv



📂 Project Structure
finadvise/├── app.py├── requirements.txt├── .env├── README.md

⚙️ Setup Instructions
1. Clone Repo
git clone <repo-url>cd finadvise
2. Create Virtual Environment
python -m venv envenv\Scripts\activate   (Windows)
3. Install Dependencies
pip install -r requirements.txt
4. Add API Keys (.env)
GROQ_API_KEY=your_keyALPHA_VANTAGE_API_KEY=your_key
5. Run App
streamlit run app.py

💬 Example Queries


“What is AAPL stock price?”


“Add $50 for groceries”


“Show my budget”


“How should I save money?”



⚠️ Notes


Alpha Vantage free tier: 5 requests/minute


HITL triggers for sensitive financial decisions


Designed for educational/demo purposes



📈 Future Improvements


Multi-agent system (Planner + Executor)


Portfolio optimization


API integrations with financial platforms



🤝 Connect
Feel free to connect and collaborate on AI & Data Science projects.
📖 Full Project Article

👉 Read the detailed Medium blog explaining architecture, design, and workflow:
https://medium.com/@Ifthiyaz_Ahamed/building-finadvise-an-ai-powered-personal-finance-assistant-using-langgraph-llms-3bacc92b379c

🔗 Project Links
💻 Source Code: https://github.com/ifthiyaz/finadvise-ai-agent](https://github.com/Ifthiyaz/FinAdviser-ai-agents
📝 Medium Blog: https://medium.com/@Ifthiyaz_Ahamed/building-finadvise-an-ai-powered-personal-finance-assistant-using-langgraph-llms-3bacc92b379c
🎥 LinkedIn: https://www.linkedin.com/in/ifthiyazahamed

🤝 Connect With Me

🔹 LinkedIn
https://www.linkedin.com/in/ifthiyazahamed

🔹 GitHub
https://github.com/ifthiyaz

🔹 Medium (Full Article)
https://medium.com/@ifthiyaz

🔹 Personal Website
https://ifthiyaz.com
