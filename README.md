# Galaxy Shooter

## Overview
This project is a multiplayer real-time game built using modern web technologies. Players can move their characters, shoot projectiles, and chat with each other, all in real time. The game features smooth animations, a responsive interface, and robust synchronization between the server and clients.

## Features
- **Real-Time Multiplayer Gameplay**: Synchronizes player movements and actions across all connected users using WebSockets.
- **In-Game Chat**: Players can send and receive messages, fostering interaction within the game.
- **Projectile System**: Players can shoot projectiles with smooth trajectories, calculated and updated dynamically.
- **Leaderboard**: A real-time leaderboard displays player scores in descending order.
- **Responsive Design**: The game is optimized for desktop and mobile devices.
- **Touch Controls**: Includes touch gestures for movement and shooting on mobile devices.

---

## Tech Stack
### Backend
- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Lightweight web framework for building the HTTP server.
- **Socket.IO**: Enables bidirectional communication between server and clients for real-time updates.

### Frontend
- **HTML5 Canvas**: Renders the game interface and animations.
- **JavaScript**: Implements game logic and interactions.
- **CSS**: Provides the styling for the interface.

---

## Prerequisites
Make sure you have the following installed on your system:
- **Node.js** (v16+)
- **npm** (Node Package Manager)

---

## Installation and Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/multiplayer-game.git
   cd multiplayer-game
