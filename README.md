# Game-Programming-Course-Week-7

In the seventh week of the Game Programming course, I expanded my Unity game by implementing a Speed Boost Power-Up. This power-up allows the player to temporarily increase their movement speed, introducing an additional layer of gameplay dynamics.

This project demonstrates the following skills:

- Creating a Speed Boost Prefab: Designed a speed boost power-up using a sprite with specific settings (sorting layer, scale, collider, and Rigidbody components).
- Modular Power-Up System: Structured the power-up system to allow different types of bonuses by assigning each power-up a unique ID, making it easy to add additional bonuses in the future.
- Player Script Enhancements: Added a speed multiplier variable and a boolean to track the activation status of the speed boost.
- Activation and Deactivation Functions: Implemented functions to activate and deactivate the speed boost. A coroutine deactivates the boost after a set duration, returning the player’s speed to normal.
- SpawnManager Update: Modified the SpawnManager to spawn the speed boost power-up at intervals, allowing players to encounter the bonus regularly.
- Speed Boost Animation: Added an animation to the speed boost power-up to make it visually engaging and easily noticeable.

In this project, players can collect a speed boost power-up that temporarily doubles their movement speed, enhancing their agility. This assignment helped me develop a modular power-up system and better understand the implementation of time-based bonuses in Unity.
