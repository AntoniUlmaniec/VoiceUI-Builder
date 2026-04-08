# No-Keyboard Interface (AI UI Generator)

A voice and sketch-controlled application for generating React interfaces, utilizing Google Gemini models.

## Initial Setup

**API Key**
An `.env` file must be placed in the root directory of the project. Paste your Gemini API key into it:
```env
API_KEY=[Your key here]
```

## Run Instructions

To run the application, execute the following steps in your terminal:

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Run the generator**
   ```bash
   node generator.js
   ```

3. **Start the application**
   ```bash
   cd src && npm start
   ```

## About the Project
**VoiceUI-Builder** is an innovative, multimodal application designed to generate complete **React** user interfaces using only voice commands and sketches. By leveraging the power of **Google Gemini AI models**, 
this tool eliminates the need for traditional keyboard input during the UI prototyping phase, translating human intentions and rough drawings directly into functional, ready-to-use React code.

## Key Features
* **Voice & Sketch to UI:** Seamlessly converts spoken requirements and hand-drawn sketches into fully functional React components.
* **Powered by Google Gemini AI:** Utilizes advanced AI models to understand natural language and visual inputs, generating accurate and structured code.
* **Node.js Generator Engine:** Features a custom backend script (`generator.js`) that handles API communication and prompt engineering.
* **Rapid Prototyping:** Drastically reduces frontend development time by bridging the gap between an idea and a working prototype.

## Tech Stack
* **Frontend:** React, JavaScript, HTML5, CSS3
* **Backend/Scripts:** Node.js
* **AI & Integration:** Google Gemini API
