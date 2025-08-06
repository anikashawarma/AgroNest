# 🌾 AI-Powered Farming Assistant Platform

An innovative and integrated farming platform designed to **empower farmers**, **streamline agricultural operations**, and **boost productivity** through modern technology. This system provides a seamless combination of traditional farming tools with cutting-edge digital solutions.

## 🚀 Key Features

* **Tool Rental System**: Farmers can rent essential farming tools and equipment through a user-friendly interface.
* **E-Commerce Module**: Buy and sell seeds, fertilizers, and other agricultural supplies online.
* **AI-Driven Crop Disease Detection**: Utilizes deep learning and computer vision to detect crop diseases from images in real-time.
* **Real-Time Weather Updates**: Integrates weather APIs to help farmers plan activities with accurate local forecasts.
* **Smart Chatbot Assistant**: AI-powered chatbot deployed using Flask and JavaScript to offer 24/7 support, guidance, and answers to common farming-related queries.

## 🧠 Tech Stack

* **Frontend**: React.js, HTML, CSS, JavaScript
* **Backend**: Node.js, Express.js, Python (Flask for chatbot and ML models)
* **Database**: MongoDB
* **Machine Learning**: PyTorch for deep learning models
* **NLP**: NLTK for intent recognition and chatbot training
* **Deployment**: Flask API + standalone JavaScript frontend

## 🔧 Chatbot Deployment Instructions

The chatbot is built using PyTorch and deployed with Flask and JavaScript. It offers two flexible deployment options:

1. **Integrated Flask App** – Embeds the chatbot into the Flask app using Jinja2 templates.
2. **Standalone Frontend** – Allows frontend applications to consume the chatbot API independently via RESTful routes.

### 🛠 Setup Instructions

```bash
# Clone the repo and set up the environment
git clone https://github.com/<your-username>/chatbot-deployment.git
cd chatbot-deployment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install Flask torch torchvision nltk

# Download required NLTK data
python
>>> import nltk
>>> nltk.download('punkt')
```

### 🧪 Train Chatbot

Modify `intents.json` as per your use case (crop queries, weather, etc.) and run:

```bash
python train.py
```

This will create `data.pth`, which can be tested via:

```bash
python chat.py
```

### 🌐 Deploy Chatbot with Flask + JavaScript

Follow the video tutorial to implement `app.py` and `app.js`.
Watch here: [https://youtu.be/a37BL0stIuM](https://youtu.be/a37BL0stIuM)

For standalone deployment, refer to the `/standalone-frontend` folder for ready-to-integrate frontend files.

---

## 👩‍💻 Developed By

This project was proudly built by a passionate student team:

* **Jatin Sinha**
* **Anika Sharma**
* **Satyam**
* **Mannat Aggarwal**

---

## 📌 Credits

The chatbot structure and frontend were originally inspired by:

* [PyTorch Chatbot Tutorial by Python Engineer](https://github.com/python-engineer/pytorch-chatbot)
* Frontend chat interface: [https://github.com/hitchcliff/front-end-chatjs](https://github.com/hitchcliff/front-end-chatjs)

---
