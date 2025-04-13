🏨 CU Hostel Assistant Chatbot
A simple and interactive Flask-based web chatbot designed for Chandigarh University hostel residents. It provides quick responses to frequently asked queries about hostel services, regulations, and support.

🚀 Features
🌐 Web-based chatbot UI

🤖 Predefined menu of 15 hostel-related topics

🏢 Details about Nek Chand Tower and facilities

📞 Emergency contacts and important links

🧠 Built with Flask and deployed on Render

📁 Project Structure
csharp
Copy
Edit
├── app.py                  # Flask backend application
├── requirements.txt        # Python dependencies
├── templates/
│   └── index.html          # Chatbot UI
├── static/
│   └── style.css           # Custom styling (optional)
├── README.md               # Project documentation
🛠️ Installation
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/cu-hostel-assistant.git
cd cu-hostel-assistant
2. Create a Virtual Environment (optional but recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
▶️ Run Locally
bash
Copy
Edit
python app.py
Visit http://localhost:5000 in your browser to start chatting.

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
Flask

gunicorn

(Ensure these are listed in your requirements.txt)

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
This project is for educational and demonstration purposes.
