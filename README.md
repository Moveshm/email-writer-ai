📧 Email AI Assistant

An AI-powered Email Assistant that integrates with your email via a Chrome Extension and helps you manage emails faster. It adds a “Generate Reply” button inside your email, which uses Google Gemini API to create context-aware smart replies instantly.

🚀 Features

✨ Generate Smart Replies – One-click reply generation inside the email.

📝 Summarize Emails – Quickly get short summaries of long email threads.

📌 Priority Classification – Mark important emails automatically.

😊 Sentiment Analysis – Detect tone for better context-aware responses.

🔔 Smart Reminders – Get reminders for pending replies.

🌐 Chrome Extension – Direct integration inside your email UI.

🛠️ Tech Stack

Backend: Spring Boot

AI Model: Google Gemini API

Frontend: React + Material UI

API Communication: Axios

Browser Integration: Chrome Extension

📂 Project Structure
Email-AI-Assistant/
│── backend/         # Spring Boot backend
│── frontend/        # React + Material UI frontend
│── extension/       # Chrome Extension code
│── README.md        # Project documentation


⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/email-ai-assistant.git
cd email-ai-assistant

2. Backend (Spring Boot)

Navigate to backend/

Configure application.properties with your Gemini API Key

Run:

mvn spring-boot:run

3. Frontend (React + Material UI)

Navigate to frontend/

Install dependencies:

npm install


Start frontend:

npm start

4. Chrome Extension

Go to Chrome → chrome://extensions/

Enable Developer Mode

Click Load unpacked → select the extension/ folder

Extension will appear in the browser

🎯 How It Works

Open any email in Gmail/Outlook.

Click the “Generate Reply” button inside the email.

The request is sent to Spring Boot backend, which connects to Gemini API.

AI generates a context-aware smart reply and shows it in the email UI.
