# AI Email Writer Extension 


Not a web app. Not just a tool. It’s a Chrome Extension that understands your tone and writes professional emails intelligently.

An intelligent Chrome Extension that helps users generate professional and personalized email replies instantly using Google Gemini AI.
The extension analyzes the email context and user writing tone to automatically create smart, human-like email responses directly inside the browser.

Built with React.js, Java Spring Boot, and Google Gemini API.

How It Works
1. User opens email platform (like Gmail)
2. Chrome Extension captures email context
3. Request is sent to Spring Boot backend
4. Backend communicates with Google Gemini API
5. AI generates a smart email response
6. The generated reply is displayed instantly to the user

## Backend Setup (Spring Boot)
cd backend

-> Add your Gemini API key in:

application.properties
gemini.api.key=YOUR_API_KEY

-> Run the backend:
mvn spring-boot:run

## frontend Setup (React)
cd frontend
npm install
npm run dev

## Load Chrome Extension

Open Chrome Browser
Go to:
chrome://extensions/
Enable Developer Mode
Click Load Unpacked
Select chrome-extension folder

## Use Cases
Professional email writing
Quick email replies
Smart response generation
Productivity enhancement
AI-assisted communication

## Future Improvements
Multi-language support
Voice-to-email generation
Gmail direct integration
User authentication
Email history management
AI tone customization

## Demo Video:
https://github.com/user-attachments/assets/736fe570-d5a9-43fb-bb24-4c093c5d9051




