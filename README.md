# Lacrosse Scoreboard App

This is a simple and interactive lacrosse scoreboard app built using **Vue.js** and **Firebase**. It is designed to track game time, score, shot clock, and penalties for a lacrosse game. The app also allows for team name edits, score adjustments, and penalty tracking, with support for a controller and viewer mode.

## Features

- **Editable Team Names**: Allows for the home and away teams to modify their names in controller mode.
- **Game and Shot Clocks**: Tracks the main game clock and shot clock, with the ability to start, pause, and reset the timers.
- **Score Tracking**: Updates the score for both the home and away teams, with plus and minus buttons.
- **Timeouts**: Tracks timeouts for both teams.
- **Penalty Tracking**: Manages player penalties with timers, categories, and the option to release penalties.
- **Firebase Integration**: Saves the game state (team names, scores, timers, penalties) to Firebase Realtime Database for persistence.

## Tech Stack

- **Vue.js**: JavaScript framework for building the app.
- **Firebase**: Real-time database to save and load game state data.
- **Bootstrap**: For responsive and clean UI components.

## Installation

### Prerequisites

- **Node.js**: Ensure Node.js is installed on your machine.
- **Firebase**: Set up a Firebase project and obtain your Firebase configuration keys (API Key, Auth Domain, etc.)

### Steps to Run the App

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/lacrosse-scoreboard.git
   cd lacrosse-scoreboard
