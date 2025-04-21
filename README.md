# 💼 Finance Bot

A smart financial assistant built using **LangGraph**. This bot helps users make informed investment decisions by gathering data, generating insights, and delivering professional recommendations via email.

---

## 🔧 Features

- 📬 **Email Integration:** Generates and sends investment recommendation emails using Gmail integration.
- 🤖 **LLM-Powered Responses:** Uses LLM to understand user queries and create context-aware answers.
- 🧠 **Simple ReAct Agent:** Utilized for structured reasoning and response generation.
- 🔁 **Router-Based Flow (Explored):** Future-ready design with conditional routing for task-specific handling.

---

## 📩 Email Functionality

The bot can:
- Analyze financial information using an LLM.
- Draft professional investment recommendation emails.
- Send or draft emails directly using the Gmail API.

---

## 🛠️ Tech Stack

- **Python**
- **LangGraph**
- **LangChain**
- **OpenAI API**
- **Gmail API** (via `GmailToolkit`)

---

## 🚀 Getting Started

1. Clone the repository:
   
   ```bash
   git clone https://github.com/your-username/finance-bot.git
   cd finance-bot
2. Create and Activate Virtual Environment:
   
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
3. Install Dependencies:
   
   ```bash
   pip install -r requirements.txt

## 🚀 How to Use

### Using the Bot Programmatically

You can invoke the bot directly using the following code:

```python
app.invoke({"input": "I should invest in Reliance or not?"})

