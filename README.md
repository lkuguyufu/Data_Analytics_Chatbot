# 🤖📊 Data Analytics Chatbot

Welcome to the **Data Analytics Chatbot** – an intelligent assistant designed to help you analyze datasets using natural language! Whether you're a data analyst, student, or just data-curious, this chatbot transforms your plain-text queries into powerful insights and visualizations.

---

## 🚀 What is This?

The Data Analytics Chatbot is an AI-powered assistant that:
- Understands **natural language questions**
- Reads and analyzes **CSV datasets**
- Provides **descriptive statistics**, trends, summaries, and data visualizations
- Utilizes **Gemini**, Google's powerful large language model, for deep understanding and interaction

It’s your personal data analyst packed into a conversational bot!

---

## 🧠 Key Features

✨ **Natural Language Understanding**  
Talk to the chatbot like you’d talk to a colleague:  
> "What's the average value in the revenue column?"

📊 **Insightful Analysis**  
From simple summaries to identifying outliers or generating correlation matrices — the bot can do it all.

📈 **Data Visualizations**  
Ask for graphs, and the bot can generate meaningful charts using Python's rich data visualization libraries.

📂 **Custom Dataset Support**  
Use the built-in `sample_dataset.csv` or plug in your own dataset to explore.

🤖 **Powered by Gemini**  
Natural language parsing is driven by the Gemini model, making query understanding smarter and more contextual.

---

## 🛠 Project Structure

```
zp/
├── app.py                # Entry point for running the chatbot
├── chatbot_logic.py      # Core logic for handling user queries and processing data
├── gemini_handler.py     # Manages interaction with Gemini LLM
├── utils.py              # Utility functions for parsing and formatting
├── sample_dataset.csv    # Example dataset for testing and demo
└── requirements.txt      # Python dependencies
```

---

## 📦 Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/data-analytics-chatbot.git
cd data-analytics-chatbot/zp
```

### 2. Setup Your Environment

It's best to use a virtual environment:

```bash
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## 🧪 Using the Chatbot

Run the chatbot using:

```bash
python app.py
```

You’ll be prompted to enter your query. For example:
- “Show me the mean of the ‘age’ column.”
- “Plot a histogram of sales.”
- “Find the correlation between income and expenses.”

Behind the scenes, the chatbot processes your request, interprets it using Gemini, and returns an intelligent response — often with visual output!

---

## 🔍 Example Use Case

You upload a dataset of monthly sales. You ask:

> "What’s the best-performing product line in Q2?"

The bot:
- Parses your CSV
- Filters Q2 data
- Aggregates sales by product line
- Returns a summary with a chart 📈

---

## 🤝 Contributions

Pull requests, suggestions, and feature ideas are welcome! Create an issue or fork the repo to get started.

---

## 📜 License

Licensed under the MIT License. See `LICENSE` for details.

---

## 🌟 Future Enhancements

- Integration with multiple datasets at once
- Support for Excel and SQL databases
- Exporting visualizations as PNG/PDF
- Web-based interface for non-technical users
- Voice input 🎙️ and chat history

---

Ready to turn your questions into data-driven answers? Let’s chat with your data! 💬📉
