# guess-my-number
A classic guess my number game using javascript

-----

## 🔢 Guess My Number Game

### Overview

Welcome to **Guess My Number**\! This is a classic, simple, and fun game built entirely with **HTML**, **CSS**, and **JavaScript**. The objective is straightforward: guess the secret number chosen by the computer within a set range, using the least number of attempts.

It's a great project for beginners looking to solidify their understanding of **DOM manipulation**, **event handling**, and basic **game logic** in JavaScript.

-----

## 🚀 Features

  * **Random Secret Number Generation:** The computer selects a random number between 1 and 20.
  * **Input Validation:** Checks if the player's guess is within the allowed range.
  * **Hint System:** Provides feedback on whether the guess is **too high** or **too low**.
  * **Score Tracking:** Keeps track of the remaining guesses (the initial **score**).
  * **Highscore Tracking:** Saves the best score achieved in the current session.
  * **'Again\!' Button:** Allows the player to reset the game and start a new round.
  * **Visual Feedback:** Changes the background color and displays messages to guide the player.

-----

## ✨ How to Play

1.  The game starts with a random **secret number** hidden behind the '?' mark.
2.  Your initial **Score** will be displayed (usually 20).
3.  Enter a number between **1 and 20** in the input field.
4.  Click the **"Check\!"** button.
5.  The game will tell you if your guess is:
      * **Correct:** You win\! The secret number is revealed, the background turns green, and your current score becomes the new **Highscore** if it's better than the previous one.
      * **Too High:** Your score decreases, and you get another try.
      * **Too Low:** Your score decreases, and you get another try.
6.  If your score reaches **0**, you lose the game\!
7.  Click the **"Again\!"** button to start a completely new game with a new secret number.

-----

## 🛠️ Technologies Used

  * **HTML5:** For the structure and content of the game.
  * **CSS3:** For styling and basic layout.
  * **JavaScript (ES6+):** For all the core game logic, DOM manipulation, and interactivity.

-----

## 📂 Project Structure

The project follows a simple, clean structure:

```
guess-my-number/
├── index.html       # The main structure of the game
├── style.css        # All the styling for the game
└── script.js        # The core game logic and functionality
```

-----

## ⚙️ Local Setup

To run this game locally:

1.  **Clone the repository:**
    ```bash
    git clone [Your-Repo-URL]
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd guess-my-number
    ```
3.  **Open `index.html`:** Simply double-click the `index.html` file in your file explorer, or open it in your preferred web browser.

-----

## 🤝 Contribution

Feel free to **fork** this repository, open an **issue**, or submit a **pull request** if you have suggestions for new features, bug fixes, or improvements\!

