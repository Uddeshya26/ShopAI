# 🛒 ShopAI – E-commerce Intelligent Assistant

**Conversational insights from your data. Just upload and ask.**

---

## 📌 About the Project

ShopAI is an AI-powered assistant that helps e-commerce businesses explore their sales, inventory, and customer data using natural language.

---

## 🚀 Features

- Upload CSV datasets (sales, products, returns, etc.)
- Ask questions like:
  - "What are my top 5 selling products?"
  - "How did electronics perform last quarter?"
- Get instant:
  - Answers
  - Charts
  - Summaries

---

## ⚙️ Tech Stack

- **Frontend:** Streamlit / React
- **Backend:** Python, Pandas, FastAPI
- **LLM:** OpenAI GPT / LLaMA2 + LangChain
- **Charts:** Plotly / Matplotlib
- **Storage:** Local or Firebase (optional)

---

## 🧠 How It Works

1. User uploads a CSV file
2. LLM interprets natural language query
3. Query gets translated to Pandas code
4. Results are shown as tables, charts, or summaries

---

## 📁 Folder Structure

See the project structure in the `/ecommerce-intelligent-assistant` directory.

---

## 🛠️ Setup Instructions

```bash
git clone https://github.com/Uddeshya26/ShopAI.git
cd ecommerce-intelligent-assistant
pip install -r requirements.txt
streamlit run app/main.py
