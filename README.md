# Project Title: Higher-Lower Game

## Description
This Python script brings you the exciting Higher-Lower guessing game! Test your knowledge of famous people and their social media followings. Can you correctly predict who has more followers, round after round, to rack up a high score?

## Features
- Interactive gameplay with clear user prompts.
- Immersive ASCII art for the game logo and "vs" separator (requires **art** library).
- Dynamically retrieves data on famous people and their follower counts using an external file (**game_data.py**).
- Randomly selects two celebrities for each comparison, ensuring variety.
- Formats celebrity data into a user-friendly presentation, including name, description, and country.
- Evaluates user guesses ("A" or "B") against follower counts to determine if they bet correctly.
- Provides feedback on each guess, indicating if the answer was right or wrong.
- Tracks the player's score and displays it after each round.
- Offers a seamless user experience with a clear screen function (**clear()**) for readability.
- Continues the game until the player gets a guess wrong, then displays the final score.

## How to Play:
**1- Run the Script:** Execute the script using python **"higher_lower_game.py"** in your terminal.

**2- Start Guessing:** The game displays two celebrities with their descriptions and countries.

**3- Who Has More Followers?:** Decide and type "A" or "B" to guess who has a higher follower count.

**4- Receive Feedback:** The script reveals whether your guess was correct, updating your score.

**5- Continue or End:** If correct, you move on to a new comparison round. If wrong, the game ends, showing your final score.

## Example Gameplay:

Compare A: Albert Einstein, a theoretical physicist, from Germany.
Against B: Ariana Grande, an American singer and actress.

Who has more followers? Type 'A' or 'B': a
You're right! Current score: 1.

... (continue guessing through more rounds)

Sorry, that's wrong. Final score: 3

## Contributing
Feel free to contribute to this project by:

- Expanding the celebrity data set (**game_data.py**) with more famous people.
- Implementing difficulty levels with varying follower count differences between celebrities.
- Adding visual elements for the celebrities (e.g., using libraries like Pillow).
- Integrating sound effects for correct guesses and game events.
- To contribute, fork the repository on GitHub and create a pull request with your proposed changes.



## Dependencies
This script relies on two external files:

- **game_data.py:** Contains data on the celebrities, including follower counts.
- **art library (optional):** Provides ASCII art elements for the logo and "vs" separator. Install it with **pip install art** before playing.
