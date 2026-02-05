# Tic Tac Toe – React Game

A small React project focused on clean component structure, predictable state management, and readable game logic.

The repository serves as a **portfolio project** demonstrating front-end fundamentals, with an emphasis on component design, state flow, and separation of concerns.

---

## Live Preview

```
https://tic-tac-toe-react-nine-sooty.vercel.app/
```

---

## Features

- Classic Tic Tac Toe gameplay
- Two-player turn-based logic (X / O)
- Game over detection (win & draw)
- Move history log
- Player name editing
- Game reset functionality

---

## Tech Stack

- **React** (functional components)
- **Vite** (fast development environment)
- **JavaScript (ES6+)**
- **CSS**

---

## Project Structure

```text
src/
├── components/
│   ├── GameBoard.jsx
│   ├── GameOver.jsx
│   ├── Log.jsx
│   └── Player.jsx
├── assets/
├── winning-combinations.js
├── App.jsx
├── index.jsx
└── index.css
```

**Highlights:**
- Reusable, focused components
- Game logic separated from UI
- Winning logic extracted into a standalone module
- Predictable data flow via props and state

---

## Key Concepts Demonstrated

- React component composition
- Lifting state up
- Conditional rendering
- Immutable state updates
- Clean separation of concerns
- Basic game logic implementation

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/MatejMicikas/tic-tac-toe-react.git
cd tic-tac-toe-react
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the development server

```bash
npm run dev
```

The app will be available at:

```
http://localhost:5173
```

---

## Possible Improvements

- Single-player mode with AI
- Score tracking
- Animations / transitions
- Mobile-first layout refactor
- Unit tests

---

## 👤 Author

Matej Micikáš  
Front-end / JavaScript developer  
Interested in clean React architecture and maintainable code

---

## License

This project is open source and available under the [MIT](LICENSE) License.