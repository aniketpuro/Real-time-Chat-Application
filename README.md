# 💬 Real-time Chat Application

A robust and responsive real-time chat application built using **Flask-SocketIO**, **JavaScript**, and **Bootstrap**. This project supports public and private chat rooms, user login, and real-time message broadcasting.

## 🚀 Features
- 🔐 User authentication with session management
- 💬 Real-time messaging using WebSockets (Flask-SocketIO)
- 🔒 Private and public room functionality
- 🕒 Message timestamping for better context
- 🐳 Dockerized setup for streamlined deployment
- ☁️ Hosted on Heroku for easy access and scalability

## 🛠 Tech Stack
- **Backend:** Flask, Flask-SocketIO
- **Frontend:** Bootstrap, JavaScript (vanilla)
- **Deployment:** Docker, Heroku

## 📁 Folder Structure
```bash
├── app.py               # Main Flask application
├── templates/           # HTML templates
├── static/              # Static assets (CSS, JS)
├── requirements.txt     # Python dependencies
├── Dockerfile           # Container configuration
└── README.md            # Project documentation
```

## 📦 Getting Started
### Prerequisites
- Python 3.8+
- Docker (for deployment)

### Local Development
```bash
git clone https://github.com/yourusername/flask-chat-app.git
cd flask-chat-app
pip install -r requirements.txt
python app.py
```
Navigate to `http://localhost:5000` to use the chat application.

## 🚢 Deployment
Deploying on Heroku using Docker:
```bash
heroku container:login
heroku create your-app-name
heroku container:push web
heroku container:release web
heroku open
```
> 📝 Make sure to set up any required environment variables in Heroku before deployment.

## 📸 Screenshots
Coming soon!

## 📄 License
[MIT License](LICENSE)

---

Let me know if you want to include `.env.example`, Heroku config guide, or CI setup!
