# Clock App (React) - NxtWave Assignment

A dynamic digital clock application built with **React JS**. This project focuses on managing component state, lifecycle methods, and updating the UI in real-time.

## 🚀 Features

  * **Live Digital Display:** Shows current time updated every second.
  * **Lifecycle Management:** Efficiently sets up and clears intervals to prevent memory leaks.
  * **Component Architecture:** Follows a modular structure with a dedicated `Clock` component.
  * **Responsive UI:** Styled with CSS-in-JS/CSS modules for a modern look.

## 🛠️ Tech Stack

  * **React JS:** For building the user interface.
  * **JavaScript (ES6):** Logic and interval handling.
  * **CSS3:** Layout and styling.

## 📋 Project Structure

Based on the current source code:

```text
src/
├── components/
│   └── Clock/
│       ├── index.js      # Clock component logic (State & Lifecycle)
│       └── index.css     # Clock-specific styles
├── App.js                # Root component (Toggles Clock visibility)
├── App.css               # Main application styles
└── index.js              # Entry point
```

## 💡 Key React Concepts

This assignment demonstrates the use of:

1.  **`this.state` / `useState`:** Storing the current time object.
2.  **`componentDidMount`:** Initializing the `setInterval` when the clock is added to the DOM.
3.  **`componentWillUnmount`:** Using `clearInterval` to stop the timer when the clock is hidden (Crucial for performance).
4.  **Conditional Rendering:** Toggling the clock display using a "Show/Hide" button in `App.js`.

## ⚙️ How to Run

0.   Clone the repository:
    `git clone https://github.com/Sarvesh-Mohite/Clock-Using-React.git`
2.  Navigate to the project folder:
    `cd clock-rjs`
3.  Install dependencies:
    `npm install`
4.  Start the development server:
    `npm start`
5.  Open [http://localhost:3000](https://www.google.com/search?q=http://localhost:3000) to view it in the browser.

### ✍️ Author

**Sarvesh Mohite**
NxtWave Intensive Learner

## SCREENSHOTS:

<img width="598" height="426" alt="image" src="https://github.com/user-attachments/assets/f8b29ead-bbb8-414f-b6b0-f805b3ddc200" />
