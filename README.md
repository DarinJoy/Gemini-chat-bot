
# Gemini Chatbot

The Gemini Chatbot is a simple AI-powered chatbot built using Google's Gemini API. It provides a user-friendly and responsive chat interface with chat bubbles for a seamless conversation experience. The chatbot is designed to handle user messages and generate intelligent responses in real-time.





## Features

- 🤖 **AI-powered responses** using Gemini API  
- 💬 **Chat bubble UI** for a clean and modern conversation layout  
- 📱 **Fully responsive** design for desktop and mobile  
- 🚀 **Easy to set up** with minimal dependencies  

## **Tech Stack**  

The **Gemini Chatbot** project is built using the following technologies:  

### *Frontend:*  
- **HTML** – Structure of the chatbot interface  
- **CSS** – Styling for the chat UI, including chat bubbles and responsiveness  
- **JavaScript** – Handles user interactions and sends requests to the backend  

### *Backend:*  
- **Node.js** – Server-side runtime environment  
- **Express.js** – Web framework for handling API requests  
- **Body-Parser** – Middleware for parsing JSON request bodies  
- **CORS** – Enables cross-origin requests  
- **Node-Fetch** – Handles API requests to Google's Gemini AI  

### *AI Integration:*  
- **Google Gemini API** – AI-powered text generation for chatbot responses  

### *Other Tools & Libraries:*  
- **npm** – Package manager for handling dependencies  
- **Postman** (optional) – For API testing  

### **📥 Installation Guide**  

#### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/DarinJoy/Gemini-chat-bot.git
cd gemini-chatbot
```

#### **2️⃣ Install Dependencies**  
Run the following command in the project directory:  
```bash
npm install
```

#### **3️⃣ Set Up API Key**

#### Get Your Google Gemini API Key
- Go to Google AI Studio: https://aistudio.google.com/
- Sign in with your Google account
- Navigate to API Keys
- Click Generate API Key and copy it
- Since we are directly using the API key in the `server.js` file, ensure that your file contains:  
```javascript
const GEMINI_API_KEY = "YOUR_API_KEY_HERE"; // Replace with your actual API key
```

> ⚠ **Warning:** Hardcoding API keys is not recommended for security reasons. Consider using environment variables for production.

#### **4️⃣ Start the Server**  
Run the server using:  
```bash
node server.js
```
OR  
```bash
npm start
```
You should see:  
```
Server running on port 3000
```

#### **5️⃣ Open in Browser**  
Go to:  
```
http://localhost:3000
```
Start chatting with the Gemini AI chatbot! 🚀  

---
## License

This project is open-source and available under the [MIT](https://choosealicense.com/licenses/mit/) License

---

💡 *Happy Chatting!* 🌱

Let me know if you want any modifications! 🚀
