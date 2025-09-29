# Tic-Tac-Toe

A simple and modern Tic-Tac-Toe game built with React and Vite. This project is designed as a learning exercise and demonstrates React fundamentals, state management, and component-based architecture.

## Demo

![Game Screenshot](public/game-logo.png)

## Features
- Playable Tic-Tac-Toe game (Player vs Player)
- Responsive and clean UI
- Game log and move history
- Game over detection and winner announcement
- Easy to reset and replay

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Bismythium/Tic-Tac-Toe.git
   cd Tic-Tac-Toe
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:5173](http://localhost:5173) in your browser to play.

## Usage
- Click on any cell to make your move.
- The game will automatically detect a win or draw.
- Use the reset button to start a new game.

## Technologies Used
- React
- Vite
- JavaScript (ES6+)
- CSS

## Folder Structure
```
├── public/
│   └── [assets]
├── src/
│   ├── App.jsx
│   ├── index.jsx
│   ├── index.css
│   ├── winning-combinations.js
│   ├── assets/
│   └── components/
│       ├── GameBoard.jsx
│       ├── GameOver.jsx
│       ├── Log.jsx
│       └── Player.jsx
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](LICENSE)

## Future Implementations
- Keep score between Player 1 and Player 2 across multiple game rounds
- Use mathematical logic to determine winning combinations instead of hardcoded values
- Host the game on an ngrok server and implement session management to allow gameplay across two different screens
