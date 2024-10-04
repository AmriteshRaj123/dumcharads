# dumcharads
🎬 Dumcharades - Movie Guessing Game 🎥

## Introduction

Dumcharades is a movie guessing game developed in React that brings the classic charades game to life. In this game, players are given a movie description and hints. They have to guess the movie within a limited number of attempts. The game is filled with popular Bollywood movie references, making it entertaining for movie buffs!

## Features

Interactive Gameplay: Players receive hints and can submit their guesses, trying to match the movie title.
Hint System: Players can request additional hints if they are stuck, enhancing their chances of guessing the correct movie.
Score Tracking: The game tracks the player’s score based on the number of correct answers.
Feedback System: Players get personalized feedback and emojis based on their performance.
Persistent User Experience: User data such as name and score is saved using local storage to maintain the experience across sessions.
Responsive Design: The game is styled using CSS modules, ensuring that it looks good on various devices.

## Project Structure

Home Component: This is the landing page where users input their name and start the game. The user data is stored in localStorage for later use.

Game Component: This is the core gameplay component. It displays a movie description and allows the user to input their answer. The user can also request hints to make an informed guess. Once all questions are answered, the game ends, and the score is displayed.

Greeting Component: This component provides feedback based on the player's score. If they guessed correctly within the attempts, they receive a congratulatory message along with an emoji that matches their performance.

Button Component: A reusable button component used across the app for various actions such as starting the game, submitting an answer, and requesting hints.

## How to Play

Start the Game: Enter your username on the home page and click "Let's Go" to begin.
Guess the Movie: Read the movie description and type in your guess.
Request Hints: If you’re unsure, click the "Show Next Hint" button for clues.
Submit Answer: Once confident, submit your answer.
Track Your Score: After guessing each movie, your score will be updated.
Game Over: After the final question, the game displays your overall performance with a personalized message and score.

## Technologies Used

React.js: For building the dynamic UI and managing the game’s state.
React Router: To handle navigation between the Home, Game, and Greeting pages.
CSS Modules: For modular and scoped CSS styling.
Toastify: For notifications and feedback messages.
LocalStorage: To store and retrieve user data and scores across sessions.


## Clone the Repository:


git clone https://github.com/AmriteshRaj123/Dumcharads-Project.git
cd dumcharades
Install Dependencies:
Run the following command to install all required dependencies:



npm install
Start the Development Server:
After installation, you can start the development server using:



npm start
Open the App in Your Browser:
Visit http://localhost:3000 to view and interact with the game.


## Future Improvements

Multiplayer Mode: Allow multiple players to compete against each other in real-time.
Custom Movie Lists: Allow players to add their own movies and hints for a more personalized experience.

Timed Challenges: Introduce a timer to make the game more challenging and exciting.
Conclusion

The Dumcharades project is a fun and educational way to learn React by building an engaging, real-world application. The project demonstrates the use of React components, state management, routing, and persistent data storage. Whether you're a movie buff or a React developer, this game offers an enjoyable experience!