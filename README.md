# Campus Of Secrets (with Unity and Vuforia)


![image](https://github.com/sassy-bugs/CampusOfSecrets/blob/master/COS%20logo.png)

Welcome to the Campus Of Secrets! This Android-based augmented reality (AR) game is designed to combine the excitement of treasure hunting with the challenges of data structures and algorithms (DSA). Utilizing Unity and the Vuforia engine, this immersive experience allows players to explore the real world while hunting for treasures and answering questions related to DSA.

## Table of Contents

- [Demonstration](#demonstration)
- [Game Overview](#game-overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Gameplay](#gameplay)
- [Authentication](#authentication)
- [Backend](#backend)
- [Installation](#installation)
- [Contributing](#contributing)

## Demonstration

[Demo video showcasing CampusOfSecrets in action.](https://drive.google.com/file/d/181b6PNWHy7uaujSv_hV24av7MpeIHo1l/view?usp=sharing)

## Game Overview

In the AR Treasure Hunt game, players will embark on an adventure to find hidden treasures in the real world. The game uses image tracking with Vuforia to trigger the appearance of treasure boxes on the screen when specific images are detected. Each treasure box contains a DSA-related question that the player must answer correctly to progress in the game.

## Features

- **AR-Based Gameplay:** Immerse yourself in an augmented reality world where you must find hidden treasures using image tracking.

- **DSA Challenges:** Test your knowledge of data structures and algorithms with a series of questions that become progressively challenging.

- **Hint System:** If you're stuck, the game provides hints to help you locate the next image for your treasure hunt.

- **Authentication:** Before starting the game, users must log in to their game accounts for personalized gameplay.

- **Backend:** The game's backend is powered by Node.js and MongoDB to store user data and scores.

## Getting Started

To start playing the AR Treasure Hunt game, follow these steps:

1. Download the APK file provided in the repository.

2. Install the game on your Android device.

3. Log in to your game account or create a new one if you haven't already.

4. Allow necessary permissions for image tracking and camera access.

5. Start scanning for the specified images to trigger the treasure hunts.

## Gameplay

- Scan Images: Use your device's camera to scan real-world images specified in the game. When the image is detected, a treasure box will appear on the screen.

- Solve Questions: Tap on the treasure box to open it. Answer the DSA-related question inside correctly to continue the game.

- Collect Treasures: Successfully answering questions will lead you to the next image location. Collect all the treasures to complete the game.

- Submit Your Score: If you wish to submit your score, click on the provided "Submit Score" button. Your score will be saved in the backend.

## Authentication

Before playing the game, users must log in or create an account. This authentication system ensures a personalized gaming experience and tracks individual scores.

## Backend

The backend of the AR Treasure Hunt game is built using Node.js and MongoDB. It stores user account information and game scores. The backend code and setup instructions can be found in the [backend repository](https://github.com/sassy-bugs/LoginPage_Backend).

## Installation

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/sassy-bugs/CampusOfSecrets.git
   ```
2. Install Unity and Vuforia and open the project in Unity.

3. Import the required assets and set up your Vuforia account and image tracking targets.

4. Build the project for Android and generate the APK file.

5. Install the APK on your Android device.

## Contributing
Contributions to our AR Treasure Hunt game are welcome! Feel free to open issues, suggest features, or make pull requests to help improve the game.

