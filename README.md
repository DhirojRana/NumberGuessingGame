# NumberGuessingGame

## About the Project

This is a browser-based number guessing game built using HTML, CSS, JavaScript, and jQuery. The application generates a random number between 1 and 100, and the user attempts to guess it in as few tries as possible.

The project demonstrates fundamental front-end concepts including DOM manipulation, event handling, state management, and the use of session storage.

---

## Features

* Random number generation within a defined range (1–100)
* Tracks number of attempts per game
* Maintains best score (minimum attempts)
* Counts total number of games played
* Displays guess history
* Prevents duplicate guesses
* Provides real-time feedback for each guess
* Allows resetting the game at any time
* Allows clearing all stored statistics

---

## How to Play

1. Enter a number between 1 and 100 in the input field.
2. Click the "Submit Guess" button or press Enter.
3. The application will respond with feedback:

   * "Too low" if the guess is below the target number
   * "Too high" if the guess is above the target number
4. Continue guessing until the correct number is found.
5. Upon success, the game records the number of attempts and updates the best score if applicable.

---

## Game Rules

* Only integers between 1 and 100 are accepted.
* Repeated guesses are not allowed.
* The objective is to guess the correct number using the fewest attempts.

---

## Controls

| Action       | Description                       |
| ------------ | --------------------------------- |
| Submit Guess | Validates and checks the input    |
| New Game     | Starts a new round                |
| Clear Stats  | Resets all stored game statistics |

---

## Data Storage

The application uses sessionStorage to store:

* Best score
* Number of games played

This means:

* Data persists during the browser session
* Refreshing the page retains data
* Closing the browser clears all stored values

---

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* jQuery

---

## Notes

* A new random number is generated for each game.
* Clearing statistics also resets the current game state.
* The project is intended for learning and practice purposes.

---

## Possible Improvements

* Replace jQuery with modern vanilla JavaScript
* Add difficulty levels
* Use localStorage for persistent data
* Improve accessibility and mobile responsiveness
* Introduce additional UI enhancements or scoring metrics

---

## Author

Developed as a practice project to strengthen front-end development fundamentals.
