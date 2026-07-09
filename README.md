# 🛍️ NextExpress

A simple web application demonstrating communication between a Flask backend and a JavaScript frontend.

## 🚀 Features

- Display product details dynamically
- Flask REST API
- Frontend built with HTML, CSS, and JavaScript
- Fetch API for backend communication
- CORS enabled using Flask-CORS

## 🛠️ Tech Stack

- Python
- Flask
- Flask-CORS
- HTML
- CSS
- JavaScript

## 📁 Project Structure

```
NextExpress/
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   └── venv/
├── frontend/
│   ├── products.html
│   ├── index.js
│   └── index.css
└── README.md
```

## ▶️ Run the Project

```bash
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py
```

Open `frontend/products.html` using **Live Server** and the frontend will fetch product data from the Flask backend.

## 📚 Learning Outcomes

- Building REST APIs with Flask
- Connecting a frontend to a backend using Fetch API
- Working with virtual environments
- Handling CORS in Flask