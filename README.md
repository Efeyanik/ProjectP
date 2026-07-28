# ProjectP - Unreal Engine Action Prototype

This project is an action prototype developed to grasp the core mechanics, game programming logic, and system architecture of Unreal Engine 5. Rather than focusing on visual assets, the primary focus is entirely on software architecture, modular AI, and combat mechanics.

## ⚙️ Technical Features & Implemented Systems

* **Combat and Damage System:** A precise melee combat mechanic driven by Anim Notifies and Line/Sphere Trace logic. Damage calculation and delivery are optimized using Point/Apply Damage functions.
* **Artificial Intelligence (AI):** Designed a modular enemy AI (AI Controller) with decision-making capabilities using Behavior Trees, Blackboards, Services, and Decorators.
* **Animation Infrastructure:** Implemented fluid character movements, combo attacks, and stance transitions using State Machines, Blendspaces, and Anim Montages.
* **User Interface (UI) & Controls:** Established a modern control scheme utilizing the *Enhanced Input System* (Contexts & Actions). Added a main menu and in-game interfaces capable of detecting and modifying dynamic resolution settings.
* **Core Gameplay Loop:** Integrated a Health system, collectible items, wave-based enemy spawn management, and a functional Save/Load system.
* **Software Architecture:** Actively utilized Casts, Interfaces, Enums, and Event Dispatchers to optimize communication between Blueprints and structure a clean, scalable codebase.

*(Note: Character and animation models in this project were sourced from Epic Games / Paragon assets to maintain focus on coding and system design.)*

**Developer:** Efe Yanık (Computer Engineering Student)
