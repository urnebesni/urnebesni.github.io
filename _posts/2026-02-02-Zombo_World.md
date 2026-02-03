---
title: "Zombo World: A 2D Tower Defense Game Built with Godot"
date: 2026-02-02 10:00:00 +0000
category: [game development, Godot]
tags: [Godot, GDScript, tower defense, game development, 2D games]
---

Zombo World is a 2D tower defense game developed as part of my **Bachelor’s thesis** using the **Godot Engine** and **GDScript**. The project focused on designing and implementing a complete, playable game while gaining hands-on experience with game logic, system behavior, and asset creation.

The development process consisted of two main parts: building the game itself and writing detailed technical and project documentation. The project was developed under the mentorship of **Assoc. Prof. Dr. Sc. Mladen Konecki**, with regular feedback and iterative improvements throughout the process.

### Game concept and mechanics

Zombo World is a classic tower defense game where the player defends a predefined path from waves of zombies by strategically placing and upgrading towers. The game is intentionally simple and focused, allowing players to concentrate on strategy rather than complex controls.

Core gameplay features include:
- wave-based enemy spawning
- tower placement with placement restrictions
- four different tower types with unique strengths and weaknesses
- a tower upgrade system
- damage calculation and health system
- game state control (pause, speed-up, restart)
- win and lose screens

Enemies follow a predefined path using Godot’s `Path2D` and `PathFollow2D` system, while towers detect enemies within range using collision areas and signals. The targeting logic prioritizes enemies closest to the end of the path, encouraging strategic placement and tower combinations.

### Technical implementation

The game was built entirely in **Godot** using **GDScript**, which allowed tight integration with the engine’s scene and node system. Common tower behavior was implemented using inheritance to avoid code duplication, making the system easier to maintain and extend.

All visual assets were created using **Aseprite**, following a pixel-art, retro-inspired style. Sound effects and background music were created using **Audacity** and **FM Synthesizer**, emphasizing a dark atmosphere that fits the zombie theme. Creating custom assets instead of relying on pre-made ones was an important part of the project’s creative and technical goals.

### Outcome and release

After completing my studies, the game was released publicly on **itch.io**, where it is available for free. This project significantly strengthened my understanding of game development workflows, debugging gameplay logic, and testing different gameplay scenarios to ensure a balanced experience.

**Play the game:** <a href="https://maxarmy.itch.io/zombo-world" target="_blank" rel="noopener noreferrer">**Zombo World on itch.io**</a>

**Project documentation:** <a href="https://drive.google.com/file/d/1otkjIs4wi9ZctHUgtY7kfgSB3hFcJXNm/view?usp=sharing" target="_blank" rel="noopener noreferrer">**Read PDF here**</a>


