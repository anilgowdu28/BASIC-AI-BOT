# Gemini AI Chatbot using Flask

A simple **AI chatbot web application** built using **Python, Flask, HTML, CSS, JavaScript, and Google Gemini API**.
The chatbot allows users to send messages through a web interface and receive AI-generated responses in real time.

---

## 📌 Features

* AI powered chatbot using **Google Gemini API**
* 
* Simple **Flask backend**
* Interactive **chat interface**
* Real-time response generation
* Error handling for API failures
* Clean and lightweight project structure

---

## 🛠 Technologies Used

* **Python**
* **Flask**
* **HTML**
* **CSS**
* **JavaScript**
* **Google Gemini API**

---

## 📂 Project Structure

```
Gemini-Chatbot/
│
├── app.py
│
├── templates/
│   └── index.html
│
└── README.md
```

---

## ⚙ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/gemini-chatbot.git
cd gemini-chatbot
```

---

### 2. Install dependencies

```bash
pip install flask
pip install google-generativeai
```

---

### 3. Add your Gemini API key

Replace the API key inside **app.py**

```python
genai.configure(api_key="YOUR_API_KEY")
```

You can get an API key from:

https://ai.google.dev/

---

### 4. Run the application

```bash
python app.py
```

---

### 5. Open in browser

```
http://127.0.0.1:5000
```

---

## 💬 How It Works

1. User enters a message in the chat interface.
2. JavaScript sends the message to the Flask backend.
3. Flask sends the message to the **Gemini AI model**.
4. Gemini generates a response.
5. Flask returns the response to the webpage.
6. The chatbot displays the response in the chat window.

---

## 🚀 Future Improvements

* Chat history
* Dark mode UI
* User authentication
* Voice input support
* Deploy to cloud (Render / Heroku / AWS)

---

## 📷 Example Interface

Simple chatbot interface with user messages on the right and bot responses on the left.

---

## 📄 License

This project is open-source and available under the **MIT License**.
---
