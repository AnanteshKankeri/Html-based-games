# Neon Tennis Pong

Welcome to **Neon Tennis Pong**, an exciting game where players test their reflexes, progress through levels, and avoid dynamic hurdles! This game features vibrant neon effects, increasing difficulty, and engaging gameplay mechanics.

## Features

- **Neon Design:** A sleek, glowing aesthetic with animated border effects.
- **Dynamic Gameplay:** 
  - Ball speed increases with each level.
  - Randomly placed hurdles add challenge as you progress.
- **AI Opponent:** The computer paddle adjusts its movement based on the ball's position.
- **Interactive Controls:** Players control their paddle with arrow keys.

---

## How to Play

1. Open the game in your browser.
2. Click the **Start Game** button to begin.
3. Use the arrow keys to move your paddle left (`←`) or right (`→`).
4. Hit the ball with your paddle to keep it in play and score points.
5. Avoid the hurdles as they deflect the ball's movement.
6. Progress through levels to increase the challenge.
7. The game ends if the ball escapes your paddle's reach.

---

## Controls

| Key          | Action              |
|--------------|---------------------|
| `Arrow Left` | Move paddle left    |
| `Arrow Right`| Move paddle right   |

---

## Installation

1. Clone the repository or download the `HTML` file.

   ```bash
   git clone https://github.com/your-username/3d-tennis-pong.git
   ```

2. Open the `index.html` file in any modern web browser.

---

## Code Highlights

- **Canvas Rendering:** The game uses the HTML5 `<canvas>` element for smooth 2D rendering.
- **Level Progression:** 
  - Ball speed increases by 10% each level.
  - New hurdles are generated randomly for added difficulty.
- **AI Paddle Movement:** The AI paddle uses proportional control to track the ball's movement.

---

## File Structure

```plaintext
.
├── index.html    # Main HTML file containing game logic and styles
└── README.md     # Game documentation
```

---

## Gameplay Mechanics

1. **Ball Movement:** The ball moves in a diagonal direction and bounces off walls, paddles, and hurdles.
2. **Player Paddle:** Controlled by the player to hit the ball back toward the computer's paddle.
3. **Hurdles:** Static obstacles that deflect the ball's path when hit.
4. **AI Paddle:** Automatically adjusts to the ball's position to add competition.

---

## Future Enhancements

- Add multiplayer mode for competitive play.
- Introduce power-ups and penalties for more dynamic gameplay.
- Include a scoring system with a leaderboard.

---

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

---

Enjoy playing **Neon Tennis Pong**! Let us know your feedback and suggestions for future updates.
