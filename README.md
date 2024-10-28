# 2D Drive Game: Delivery Driver
This project is a 2D drive game where players control a vehicle to collect packages and deliver them to specific endpoints. The game involves navigating a course, avoiding obstacles, and ensuring successful package deliveries.

### 🎮 Game Objective
The player’s goal is to:

- Collect a package from a designated location.
- Navigate through the level to deliver the package to an endpoint.
### 📖 Development Process
The game was developed using fundamental concepts in Unity, including collision handling, triggers, physics, and player controls. Here’s an overview of the core elements:

1. Player Controls
- **Vehicle Movement**: The player controls a 2D vehicle, which can move forward, backward, and rotate. This was achieved using Unity’s Rigidbody2D physics component to handle realistic movement.
- **Acceleration and Deceleration**: A simple control system was implemented to allow for speed variations, making the gameplay more engaging and challenging.
2. Collision Detection
- **Collisions**: Unity’s Collider2D components were used to detect collisions with obstacles, boundaries, and other objects.
- **Collision Events**: Collision events were set up to detect when the player hits obstacles. Feedback (like sound or animation) can be provided to indicate a collision, making the game more interactive.
3. Trigger Zones
- **Pickup and Drop-off**: Trigger Colliders were added to specific areas for package pickup and drop-off points. When the player’s vehicle enters these zones:
- **Package Pickup**: On entering the package pickup zone, a trigger event assigns the package to the player.
- **Package Delivery**: On reaching the delivery zone, another trigger event completes the delivery objective, progressing the player’s score or mission status.
4. Game Mechanics
- **Package Collection**: The player’s task is to collect the package by driving over it. This activates a trigger event that "attaches" the package to the player’s vehicle.
- **Delivery Mechanic**: Upon reaching the delivery endpoint, the game detects the player’s position within the drop-off zone, and the delivery is registered.
5. Visual and Audio Feedback
- **Visual Cues**: Indicators were added to show package pickup and delivery zones, guiding players through the level.
- **Sound Effects**: Audio feedback is triggered on collisions, pickups, and deliveries to enhance the immersive experience.
### 🛠️ Unity Fundamentals Used
- **Rigidbody2D and Collider2D**: Core physics components for handling player movement, collisions, and triggers.
- **Trigger Events**: Used for non-collision interactions, such as package pickup and delivery.
- **UI Elements**: Displayed player progress, such as current packages collected and deliveries made.
- **Scripts**: Custom C# scripts to manage player movement, package logic, and game objectives.
### 🚀 How to Play
- Control the vehicle using directional keys to navigate the map.
- Drive over the package to collect it.
- Navigate to the delivery endpoint and enter the zone to complete the delivery.
- Avoid obstacles and walls to keep the package safe during transit.
### 💡 Future Enhancements
- Obstacle Management: Add moving obstacles to increase difficulty.
- Time Challenges: Include timed deliveries for added challenge.
- Score System: Track the number of successful deliveries and provide scoring based on performance.
