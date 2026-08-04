# Chatbot ReactJS Project

A simple chat interface built with **React** and **Vite** to practice core React concepts such as state management, component composition, and controlled inputs.

```
## Features
- Clean chat UI with user and bot message bubbles
- Auto-scrolling message container
- Simulated bot responses powered by the `supersimpledev` package
- Built with functional components and React hooks (`useState`, `useEffect`, `useRef`)
```

```
## Tech Stack
- React 19
- Vite
- ESLint
```

## Folder Structure

```
chatbot-project/
├── node_modules/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── ChatInput/
│   │   ├── ChatMessage/
│   │   ├── ChatMessages/
│   ├── App.jsx
│   └── main.jsx
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
└── vite.config.js
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18 or higher
- npm (comes bundled with Node.js)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Umar-Farooq-Afridi/Chatbot-ReactJS-Project.git

# 2. Move into the project folder
cd chatbot-project

# 3. Install dependencies
npm install
```

### Running the App (Development)

```bash
npm run dev
```

The app will start on **http://localhost:5173** (default Vite port) — open it in your browser.

### Building for Production

```bash
npm run build
```

This generates an optimized production build inside the `dist/` folder.

### Previewing the Production Build

```bash
npm run preview
```
