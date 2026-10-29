<div align="center">

# 🎮 How to Make a Video Game
### Godot Beginner Tutorial

**My implementation and step-by-step walkthrough of the famous Brackeys tutorial to get started with the Godot Engine.**

[![Godot Engine](https://shields.io)](https://godotengine.org)
[![License: MIT](https://shields.io)](https://opensource.org)
[![Brackeys Tutorial](https://shields.io)](https://www.youtube.com/watch?v=LOhfqjmasi0)

<p align="center">
  <a href="#-about">About</a> •
  <a href="#%EF%B8%8F-project-architecture">Architecture</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-features-learned">Features</a>
</p>

<hr />
</div>

## 📝 About

This repository contains the complete source code, scenes, and assets created while following the introductory game development tutorial for **Godot Engine** by Brackeys. It serves as an excellent starting point for understanding core engine concepts: Nodes, Scenes, GDScript coding, and 2D physics mechanics.

## 🛠️ Tech Stack

* **Engine:** Godot Engine 4.x
* **Language:** GDScript
* **Game Type:** 2D Platformer

## 🗂️ Project Architecture

The project follows a clean and modular structure, matching standard Godot best practice:

* `assets/` : Stores all graphical resources (sprites, textures) and audio assets.
* `scenes/` : Gathers Godot scenes (`.tscn`) for levels, the player, enemies, and UI elements.
* `scripts/` : Contains all the logic and programming files (`.gd`) attached to nodes.

## 🚀 Getting Started

### Prerequisites
Make sure you have **Godot Engine 4** (Standard version) installed on your machine.

### Cloning and Launching the Project
1. Clone the repository locally:
   ```bash
   git clone https://github.com/VergeCentenaire/how-to-make-a-video-game-godot-beginner-tutorial
   ```
2. Open the **Godot Project Manager**.
3. Click **Import**, then browse and select the `project.godot` file located at the root of this folder.

## 🧠 Features Learned

* **Player Movement:** Handling horizontal navigation, jumping mechanics, and gravity physics.
* **Scene Management:** Instantiating reusable objects (collectible coins, animated enemies).
* **Collision System:** Implementing `Area2D` and `Body2D` nodes to handle environment interactions.
* **User Interface (UI):** Creating a simple score counter system.

## 📄 License

This project is licensed under the MIT License. Feel free to use it as a reference for your own learning journey!

<div align="center">
  <hr />
  Built with 💙 and Godot
</div>
