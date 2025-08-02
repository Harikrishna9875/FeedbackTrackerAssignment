📋 Feedback Tracker
A simple full-stack feedback tracker built using HTML, CSS, JavaScript (Frontend) and Python Flask (Backend). Users can submit feedback, and all submitted feedback appears on the same page in a scrollable list.

📁 Folder Structure
pgsql
Copy
Edit
feedback_tracker/
│
├── backend/
│   ├── app.py
│   └── feedback.json
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── README.md
🧰 Requirements
Make sure you have Python 3 installed. Then install the required Python packages:

bash
Copy
Edit
pip install flask
▶️ How to Run the App
1. Start the Backend
cd backend
python app.py
This will start the Flask server at http://127.0.0.1:5000.

2. Open the Frontend
You can open the frontend/index.html file directly in your browser:
Right click → Open with → Your browser

You don’t need to serve the frontend through a server, but for full functionality (especially if browser restricts local file requests), use a simple local server like:
cd frontend
python -m http.server 8000
Then go to: http://localhost:8000

💬 Features
Submit feedback via a simple form
View submitted feedback instantly
Scrollable and responsive layout
Clean, modern design

📝 Notes
All feedback is stored in backend/feedback.json locally.

This app is for learning/demo purposes. Do not use it in production as-is.

