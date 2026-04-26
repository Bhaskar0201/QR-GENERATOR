📌 QR Code Generator Web App (Flask)

A lightweight web application built using Flask that allows users to generate QR codes from any text or URL in real time.

This project demonstrates core backend concepts such as request handling, dynamic content generation, and integration of external Python libraries.

🚀 Overview

The application takes user input (text or link), processes it on the server, and generates a QR code image dynamically. The generated QR code can be viewed and downloaded instantly.

✨ Features
🔹 Generate QR codes from text or URLs
🔹 Real-time processing using Flask backend
🔹 Download QR code as an image (PNG)
🔹 Simple and responsive user interface
🔹 Basic input validation


🛠️ Tech Stack
Backend: Python, Flask
Frontend: HTML, CSS
Libraries:
qrcode → QR code generation
Pillow → Image processing


⚙️ How It Works
User enters text or a URL in the input field
The request is sent to the Flask server
The server processes the input using the qrcode library
A QR code image is generated dynamically
The image is displayed on the webpage and can be downloaded



📂 Project Structure
qr-code-generator/
│
├── app.py               # Main Flask application
├── requirements.txt    # Project dependencies
├── templates/
│   └── index.html      # Frontend UI
├── static/
│   └── style.css       # Styling
└── README.md           # Project documentation


🧪 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/qr-code-generator.git
cd qr-code-generator
2️⃣ Create Virtual Environment (Recommended)
python -m venv venv
venv\Scripts\activate   # On Windows
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run the Application
python app.py
5️⃣ Open in Browser
http://127.0.0.1:5000/



📌 Example Use Cases
Share website links quickly
Encode contact details
Generate QR codes for notes or messages
Use in small business or personal projects
🚧 Future Enhancements
🎨 Customize QR colors and styles
🖼️ Add logo inside QR code
💾 Save QR history using database (SQLite)
🌐 Deploy application online (Render / Heroku)
📱 Generate QR for WiFi credentials
🧠 Key Learnings
Understanding Flask routing and request handling
Working with third-party Python libraries
Handling user input securely
Generating dynamic content in web apps

<img width="442" height="444" alt="Screenshot 2026-04-26 120953" src="https://github.com/user-attachments/assets/da4f386f-d306-4462-8c49-26b2033b4c61" />



📄 License

This project is open-source and available under the MIT License.
