# snake_game
🐍 Snake Game (Java Swing)

A simple Snake Game built using Java Swing. Control the snake using your arrow keys, eat food to grow, and avoid running into yourself or the game boundaries. The game displays your current score and stops when you lose.

🎮 Features

Classic snake movement with arrow keys

Random food placement

Score tracking

Game over detection

Grid-based rendering

Simple and lightweight implementation

🛠️ Technologies Used
Technology	Description
Java	Programming language
Java Swing	GUI Framework
AWT	Graphics & Event Handling
🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/your-username/snake-game.git
cd snake-game

2️⃣ Compile the Game
javac snakeGame.java

3️⃣ Run the Game
java snakeGame

🔑 Controls
Key	Action
⬆️ Up Arrow	Move Up
⬇️ Down Arrow	Move Down
⬅️ Left Arrow	Move Left
➡️ Right Arrow	Move Right
📂 Project Structure
snake-game/
│
├── snakeGame.java   # Main game implementation
└── README.md        # Project documentation

🧩 Known Issues

paintcomponent should be paintComponent (capital "C")

snakePart in the move() method is declared incorrectly as Object

Boundary check for boardheight uses the wrong variable (boardheight instead of boardHeight)

📌 Suggested Improvements

✔️ Fix typos (e.g., paintcomponent, boardheight, snakePart type)
✔️ Add restart functionality
✔️ Increase game difficulty over time
✔️ Add sound effects or UI score panel

📄 License

This project is licensed under the MIT License – feel free to use and modify.

🤝 Contributing

Contributions are welcome!
Feel free to fork, open an issue, or submit a pull request.

💡 Author

Your Name
GitHub:Guptanayanog
