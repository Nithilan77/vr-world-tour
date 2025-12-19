# VR AI Tour Guide 🌍🕶️

A web-based 360° Virtual Reality tour application powered by Artificial Intelligence. Explore famous landmarks and interact with an AI tour guide using voice commands or text.
https://vr-world-tour.vercel.app/
## 🚀 Features

- **Immersive 360° VR Scenes**: Explore the Colosseum, Eiffel Tower, Great Wall of China, and Taj Mahal using [A-Frame](https://aframe.io/).
- **AI Tour Guide**: Powered by **Google Gemini 1.5 Flash**, the assistant answers questions and gives details about the locations.
- **Voice Control**: Navigate and interact hands-free using the **Web Speech API**.
    - *"Take me to the Eiffel Tower"*
    - *"Tell me about the history of this place"*
- **Text-to-Speech**: The assistant speaks the responses back to you for a full guided experience.
- **Full-Stack Implementation**: Node.js/Express backend with a lightweight HTML/JS frontend.

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript, A-Frame (WebVR).
- **Backend**: Node.js, Express.js.
- **AI/ML**: Google Generative AI (Gemini).
- **APIs**: Web Speech API (Recognition & Synthesis).

## 📋 Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- A Google Cloud Project with the **Gemini API** enabled (get an API key from [Google AI Studio](https://makersuite.google.com/app/apikey)).

## 📦 Installation

1. **Clone the repository** (or download code):
   ```bash
   git clone <repository-url>
   cd vr-world-tour
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Configure Environment Variables**:
   Create a `.env` file in the root directory and add your Gemini API Key:
   ```env
   GEMINI_API_KEY=your_actual_api_key_here
   PORT=3000
   ```

## ▶️ Usage

1. **Start the Development Server**:
   ```bash
   npm run dev
   ```
   Or for production mode:
   ```bash
   npm start
   ```

2. **Open the Application**:
   Visit `http://localhost:3000` in your browser.

## 🗣️ Voice Commands Guide

Click the **"🎤 Talk"** button (or allow microphone access) and try saying:

*   **Navigation**:
    *   "Take me to the Colosseum"
    *   "Go to Paris"
    *   "Show me the Taj Mahal"
*   **Questions**:
    *   "Where am I?"
    *   "When was this built?"
    *   "Tell me a fun fact about this place"

## 📂 Project Structure

```
vr-world-tour/
├── public/              # Frontend static files
│   ├── assets/          # 360° images (Colosseum, Eiffel Tower, etc.)
│   ├── index.html       # Main application interface & logic
│   └── style.css        # Styling
├── server.js            # Express backend & Gemini API integration
├── package.json         # Project dependencies & scripts
└── .env                 # Environment variables (not committed)
```

