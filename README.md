

# HTML Pong Game

This is a modern, feature-rich Pong game implemented in pure HTML, CSS, and JavaScript.

## Features

- **Mouse-controlled paddle:** You play as the left-side goalkeeper, moving your paddle with the mouse (restricted to the gameplay area).
- **Animated paddles:** Both paddles smoothly grow and shrink in size as you play.
- **AI opponent:** The computer controls the right paddle with basic tracking logic.
- **Health bars:** Both players have health bars at the top. Each goal reduces the opponent's health by 10%. The game ends when a health bar reaches zero.
- **Multiple balls:** After the first goal, a new ball is added for each subsequent goal, with a 1-second delay between each ball's appearance.
- **Ball trail effect:** Each ball leaves a colorful, animated gradient trail for a retro look.
- **Dynamic visuals:** The top bar is a very dark gray, and the game area is black for a classic arcade feel.
- **Game over screen:** Displays the winner in a retro font when the game ends.
- **Responsive and fast:** Works instantly in any modern browser.


## How to Play

1. Open `index.html` in your web browser, or run a local server:
	```
	python3 -m http.server
	```
	Then visit [http://localhost:8000](http://localhost:8000).
2. Move your paddle (left side) using your mouse. The computer controls the right paddle.
3. Score by getting the ball past the computer. Each goal adds a new ball (with a delay) and reduces health.
4. The game ends when either health bar reaches zero.

## Demo

You can see a screenshot below (add your own screenshot as `pong-demo.png`):

<img width="1786" height="1298" alt="Screenshot 2025-09-26 at 12 19 26 PM" src="https://github.com/user-attachments/assets/8bb4cfa7-a4a3-4982-a2d0-1e8f0e319071" />

---
Made with ❤️ using HTML5 Canvas and JavaScript.
