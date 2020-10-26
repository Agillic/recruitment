# Front-End Developer home assignment

Your assignment is to build a simple chess clock web application.

Chess clocks are used in chess, the purpose is to keep track of the total time each player takes for their own moves.

A chess clock consists of two adjacent counters with a button to stop one while starting the other, so that the two clocks never run simultaneously.

## Functional requirements

- When the page loads, both timers (one for white and one for black) are set to the initial time limit (15 minutes), and the clock is not running

- There is a button that starts the first round of the game (it’s always white who moves first)

- When the game has started, it must be clearly indicated at any point whose turn it is

- The remaining time for the players must be continuously updated when it’s their turn

- The remaining time for both players is displayed in millisecond resolution

- When the clock is running, there is a button that ends the turn and switches to the other player (stops the countdown for the current player and starts it for the other player)

- When a player reaches their time limit, the clocks must be stopped, and the fact that the player ran out of time must be clearly indicated (this also means that the player has lost the game)

- During the game there must be a timeline of turns in the entire game (including the currently running one) displayed, which shows the relative length of turns

## Stretch goals

- The game can be stopped prematurely with both players having time left (for example in case of a checkmate)

- Time limit can be set for both players individually before starting the game

- A ticking sound is played when the current player has less than 30 seconds of their time limit left

- The application is responsive and works fine on both desktop and mobile devices

## Non-functional requirements

- Being precise with remaining time is of the essence, make sure the clocks are updated as punctually as possible, every millisecond can make a difference for the players

- The application should be responsible for tracking time of only one chess game, it is fine if you need to refresh the page if you want to start a new game

- Strive for readability, maintainability and testability of your code (you might be asked to implement small requirement changes at the technical interview)

## Architectural requirements

- All you need to build is a front-end application, do not worry about server side, persistance etc.

- Use React, Redux Toolkit and TypeScript

- Prefer functional design to imperative design

- Use a CSS preprocessor or CSS-in-JS solution

- Use version control and don’t be conservative with committing your changes in small increments

## Questions

Should you have any questions, feel free to reach out at martin.schalck@agillic.com.
