# 🛒 Sales Dashboard with Chatbot (Flask + Power BI)

This project is a powerful combination of **Flask**, **LLM-based Chatbot**, and a **Power BI Sales Dashboard**. It allows users to interactively explore sales data using a natural language chatbot interface and visualize business insights via Power BI.

---

## 🚀 Features

- 💬 Chatbot built using **Groq API (LLaMA 3 model)**
- 📊 Interactive **Power BI Dashboard**
- 📈 Ask questions like:
  - *"Top 5 products by revenue?"*
  - *"Total sales by region?"*
- 🔐 Secure environment using `.env` for API keys
- 🧠 Context-aware prompt templating
- 🎨 Clean and responsive UI using Bootstrap

---

## 📂 Project Structure

```bash
Sales-Dashboard-With-Chatbot/
│
├── app.py                     # Flask backend application
├── SuperStore_Sales_Dataset.csv  # Sales dataset (CSV format)
├── prompt_template.txt        # System prompt instructions for chatbot
├── requirements.txt           # Python dependencies list
├── .env                       # Environment variables (contains API keys - not committed to Git)
│
├── PowerBI/
│   └── dashboard.pbix         # Power BI dashboard file
│
├── templates/
│   └── index.html             # HTML template for the web UI
│
│
└── README.md                  # Project documentation (this file)
```

---

## 🧪 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/Sdia1029/Sales-Dashboard-With-Chatbot.git
cd Sales-Dashboard-With-Chatbot
```

### 2. Create a virtual environment (optional but recommended)

```bash
python -m venv venv
venv\Scripts\activate  # On Windows
# source venv/bin/activate  # On Linux/Mac
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set environment variables

Create a `.env` file in the root directory:

```env
GROQ_API_KEY=your_groq_api_key_here
FLASK_SECRET_KEY=your_flask_secret
```

---

## ▶️ Run the Flask App

```bash
python app.py
```

Then open [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

---

## 📊 Power BI Dashboard

The Power BI dashboard file is located inside the `PowerBI/` folder.  
You can open `dashboard.pbix` using **Microsoft Power BI Desktop** to explore visual analytics on the same dataset.

---

## 🙋‍♀️ Author

**Sadia Eman**  
 Data Science  


