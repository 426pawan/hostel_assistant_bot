# 🏨 CU Hostel Assistant Chatbot
Link:https://cu-hostel-assistant-bot.onrender.com
---
A simple and interactive Flask-based web chatbot designed for Chandigarh University hostel residents.  
It provides quick responses to frequently asked queries about hostel services, regulations, and support.

---

## 🚀 Features

- 🌐 Web-based chatbot UI  
- 🤖 Predefined menu of 15 hostel-related topics  
- 🏢 Details about Nek Chand Tower and facilities  
- 📞 Emergency contacts and important links  
- 🧠 Built with Flask and deployed on Render  

---

## 📁 Project Structure

cu-hostel-assistant/ ├── app.py # Flask backend application
├── requirements.txt # Python dependencies
├── templates/ │ └── index.html # Chatbot UI
├── static/ │ └── style.css # Custom styling (optional)
├── README.md # Project documentation


---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/cu-hostel-assistant.git
cd cu-hostel-assistant

python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

pip install -r requirements.txt
python app.py

🌐 Deployment on Render
Environment Variables
On Render, set the following environment variable:

Name	Value
FLASK_SECRET_KEY	YourSecureSecretKey123
Start Command for Render
bash
Copy
Edit
gunicorn app:app
📦 Dependencies
Ensure these are listed in your requirements.txt:

Flask

gunicorn

💬 Chatbot Menu Options
Hostel General Information

Events & Notices

Maintenance & Service Requests

Hostel Regulations & Guidelines

Emergency Contacts & Procedures

Mess and Cafeteria Information

Room Allotment & Accommodation

Visitor Policies

Student Welfare Support

Health and Safety

Roommate Guidelines

Security & Surveillance

Hostel Payments & Fees

Hostel Feedback & Complaints

Other Inquiries

👨‍💻 Author
Pawan Kumar
Computer Science (AI & ML)
Chandigarh University

📄 License
This project is intended for educational and demonstration purposes only.


You can **copy** this entire block and **paste it directly** into your **README.md** file without worrying about formatting! Let me know if everything looks good now!
