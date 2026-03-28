🔐 One‑Time Password (OTP) Generator

A simple interactive web application that generates a 6‑digit one‑time password (OTP) with an expiration timer. Built using React, this project demonstrates fundamental JavaScript and React skills including state management, event handling, and timer logic.

🚀 Features
Generates a random 6‑digit OTP code
Displays the OTP to the user on button click
Includes a countdown timer showing how long the OTP remains valid
Disables the generate button while an OTP is active
Displays a message when the OTP expires
Built with React functional components and hooks
🛠️ Technologies Used
React (functional components + hooks)
JavaScript (ES6+)
HTML5
CSS3
🗂 Project Structure
one‑time‑password‑generator/
├── index.html
├── styles.css
├── index.jsx
└── README.md
📦 Installation & Setup
Option 1: Run locally in browser

Clone the repository:

git clone https://github.com/Yasser514/Build-a-One-Time-Password-Generator
Open index.html in your browser.
Option 2: Integrate into a React app (recommended)

Create a React application:

npx create-react-app otp‑generator
cd otp‑generator
npm start
Move OTP component logic into src/App.js
Add styling from styles.css
💡 How It Works
The app uses React’s useState and useEffect to track:
the current OTP code
the countdown timer
whether the generator button is active
When the user clicks Generate OTP:
a new random 6‑digit code is created
a countdown starts (e.g., 5 seconds)
the button is disabled until the timer expires
Once the timer reaches 0, the button re‑enables and the message updates

OTP Generator
565030
OTP expired. Click the button to generate a new OTP.

Generate OTP




🌐 Live Demo


🧠 What I Learned
Managing component state using React hooks
Handling timers and intervals in React
Controlled UI updates with conditional rendering
🔮 Future Improvements
Add configuration for OTP length (e.g., 4 or 8 digits)
Store history of generated codes
Save OTPs and validations in backend (Node.js / Firebase)
Add input field to verify the generated OTP
👤 Author

Yasser
📍 GitHub: https://github.com/Yasser514
