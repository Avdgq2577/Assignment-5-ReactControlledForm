# Assignment 5 - React Controlled Form

An interactive form application built with React and Vite demonstrating Controlled Components and real-time state synchronization using the `useState` hook.

## 🚀 Live Demo
- **Live URL:** [https://Avdgq2577.github.io/Assignment-5-ReactControlledForm/](https://Avdgq2577.github.io/Assignment-5-ReactControlledForm/)
- **Repository:** [https://github.com/Avdgq2577/Assignment-5-ReactControlledForm](https://github.com/Avdgq2577/Assignment-5-ReactControlledForm)

---

## 📌 Features
- **Controlled Components:** Every form field (`name`, `email`, `phone`, `message`) derives its value from component state.
- **Single Source of Truth:** Changes are captured through `onChange` event handlers, ensuring the React state is always the authoritative source.
- **Real-Time Live Preview:** Instant feedback section dynamically re-renders as the user types into any input.
- **Multi-Input Handling:** Handles multiple input types including text inputs, email inputs, and textareas.

---

## 🛠️ Tech Stack
- **React (v19):** `useState` Hook and synthetic event handling.
- **Vite:** Next-generation frontend build tooling.
- **CSS3:** Form styling, responsive container, and structured output card.

---

## 📂 Project Structure
```text
Assignment-5-ReactControlledForm/
├── .github/
│   └── workflows/
│       └── deploy.yml    # GitHub Actions workflow for GitHub Pages
├── src/
│   ├── App.css           # Form and live preview layout styling
│   ├── App.jsx           # Controlled form component with useState
│   └── main.jsx          # React DOM root entry point
├── index.html            # Vite HTML template
├── vite.config.js        # Vite build configuration (base: './')
├── package.json          # Project dependencies & scripts
└── README.md             # Project documentation
```

---

## 💻 Getting Started Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Avdgq2577/Assignment-5-ReactControlledForm.git
   ```

2. **Navigate to the directory:**
   ```bash
   cd Assignment-5-ReactControlledForm
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Start the local development server:**
   ```bash
   npm run dev
   ```

5. **Build for production:**
   ```bash
   npm run build
   ```

---

## 🌐 Deployment
Automated via **GitHub Actions** (`.github/workflows/deploy.yml`) on every push to `main`.
