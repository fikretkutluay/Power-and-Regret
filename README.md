# ⚔️ Power and Regret

**Power and Regret** is a dynamic top-down action game built with **Unity**. The project features advanced character state management, a modular ability system, and intense combat mechanics. It showcases clean C# implementation focusing on smooth player experience and scalable game logic.

## 🎮 Core Gameplay Mechanics
* **Dynamic Movement System:** Fluid 2D movement with integrated dash and roll mechanics for tactical combat.
* **Ability & Skill System:** Modular implementation of character abilities allowing for diverse playstyles.
* **Combat & Damage:** Robust hitbox detection and damage systems utilizing efficient event-based communication.
* **State Management:** Sophisticated player states handling transitions between movement, attacking, and interaction.

## 🛠 Technical Features
This project implements several advanced Unity and C# techniques:
* **Architecture:** Component-based design ensuring decoupled logic between player input and character actions.
* **Engine:** Unity (2D focus)
* **Scripting:** C# (.NET Standard) using modern coding standards.
* **Input Management:** Centralized input handling for responsive control across different gameplay states.

## 📁 Project Structure
The repository is organized for maintainability and clear separation of concerns:
```text
Power-and-Regret/
├── Assets/
│   ├── Scripts/        # Core gameplay logic, Controllers, and Systems
│   ├── Prefabs/        # Reusable entities and environment objects
│   ├── Animations/     # Character state machine and sprite animations
│   ├── Sprites/        # Visual assets and character designs
│   └── Settings/       # Project configurations and presets
