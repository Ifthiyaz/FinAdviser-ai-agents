# 💸 FinAdvise – AI-Powered Personal Finance Assistant

FinAdvise is a **LangGraph-based AI agent system** designed to help users manage personal finance through intelligent conversations.

---

## 🚀 Features

- 🧠 Intent detection (profile, stock, budget, advice)  
- 💾 Memory management (short-term & long-term)  
- 📈 Real-time stock data via Alpha Vantage API  
- 🤖 Personalized financial advice using LLM  
- ⚠️ Human-in-the-Loop (HITL) for high-risk queries  
- 💬 Interactive chat UI using Streamlit  

---

## 🧠 Architecture

Built using **LangGraph**, enabling:

- State-based workflows  
- Multi-node AI pipelines  
- Conditional execution  
- Modular agent design  

---

## 🛠 Tech Stack

- Python  
- LangGraph  
- LangChain  
- Groq (LLaMA 3 Model)  
- Streamlit  
- Alpha Vantage API  
- python-dotenv  

---

## 📂 Project Structure

```bash
finadvise/
├── app.py
├── requirements.txt
├── .env
├── README.md
```

---

## ⚙️ Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/Ifthiyaz/FinAdviser-ai-agents
cd FinAdviser-ai-agents
```

### 2. Create Virtual Environment
```bash
python -m venv env
env\Scripts\activate   # Windows
# source env/bin/activate  # macOS/Linux
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Add API Keys (.env)
```env
GROQ_API_KEY=your_key
ALPHA_VANTAGE_API_KEY=your_key
```

### 5. Run Application
```bash
streamlit run app.py
```

---

## 💬 Example Queries

- “What is AAPL stock price?”  
- “Add $50 for groceries”  
- “Show my budget”  
- “How should I save money?”  

---

## ⚠️ Notes

- Alpha Vantage free tier: 5 requests/minute  
- HITL triggers for sensitive financial decisions  
- Designed for educational/demo purposes  

---

## 📈 Future Improvements

- Multi-agent system (Planner + Executor)  
- Portfolio optimization  
- Integration with financial APIs  

---

## 📖 Full Project Article

👉 Read the detailed Medium blog:  
https://medium.com/@Ifthiyaz_Ahamed/building-finadvise-an-ai-powered-personal-finance-assistant-using-langgraph-llms-3bacc92b379c

---

## 🔗 Project Links

- 💻 Source Code: https://github.com/Ifthiyaz/FinAdviser-ai-agents  
- 📝 Medium Blog: https://medium.com/@Ifthiyaz_Ahamed/building-finadvise-an-ai-powered-personal-finance-assistant-using-langgraph-llms-3bacc92b379c  
- 🎥 LinkedIn: https://www.linkedin.com/in/ifthiyazahamed  

---

## 🤝 Connect With Me

🔹 LinkedIn  
https://www.linkedin.com/in/ifthiyazahamed  

🔹 GitHub  
https://github.com/ifthiyaz  

🔹 Medium  
https://medium.com/@ifthiyaz  

🔹 Personal Website  
https://ifthiyaz.com  

---

## ⭐ Support

If you found this project useful:

- ⭐ Star the repo  
- 🔁 Share on LinkedIn  
- 🤝 Connect for collaboration  
