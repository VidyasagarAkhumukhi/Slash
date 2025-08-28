# The Slayer of Demons - A World in the Making

## About the Game

**The Slayer of Demons** is a third-person action RPG being built in **Unreal Engine 5**. Set in a desolate, fallen world, players take on the role of the last of a sacred order, tasked with hunting down powerful demons that have consumed the land.

This README serves as a living document and devlog, tracking the progress from the initial world-building to the final gameplay mechanics.

## Core Features

* **Challenging Combat:** A skill-based combat system emphasizing timing, dodging, and strategic use of abilities.
* **Vast World Exploration:** A large, seamless world full of hidden locations, valuable resources, and environmental storytelling.
* **Atmospheric World Design:** A beautifully crafted environment with dynamic lighting and a day/night cycle that brings the desolate world to life.
* **Deep Lore:** Uncover the secrets of an ancient cataclysm that allowed the demons to overrun the world.

## Development Log

### **August 2025: Initial World Creation**

The project began with the creation of the world's foundation. Using Unreal's landscape tools, a 32x32 km grid was sculpted with noise and erosion algorithms to create a base terrain. A multi-layered landscape material was then created, allowing for vertex blending of different PBR textures (sand, rock, grass) based on height and slope to form the initial biomes.

<img width="800" alt="Raw Landscape Sculpt" src="https://github.com/user-attachments/assets/01d3fe9c-374f-43b5-8873-dbb1c727a821" />
<br>
<img width="800" alt="Textured Overhead Map" src="https://github.com/user-attachments/assets/d2167106-6a35-4000-b752-a4f6db1c6cc2" />

### **Update: August 26, 2025 - Foliage and Atmosphere**

To bring the world to life, high-quality assets from Quixel Megascans were introduced using the foliage system. This allowed for the efficient painting of trees, grass, and rocks across the landscape. The atmosphere was dramatically enhanced with a Post-Processing Volume, adjusting color grading for a high-contrast, cinematic look and enabling effects like volumetric god rays and lens flares for dynamic lighting.

<img width="800" alt="God rays filtering through the new foliage during midday." src="https://github.com/user-attachments/assets/2b9ee366-603a-4eee-9706-49bd17414523" />
<br>
<img width="800" alt="The world at golden hour, showcasing long shadows and warm post-processing." src="https://github.com/user-attachments/assets/bd20c7c0-59ea-48a8-9aea-86626b741f9e" />

### **Update: August 28, 2025 - World Redesign & Grand Scale**

A significant art direction shift led to a redesign of the world. The environment was reshaped into a vast desert canyon with a lush, temperate oasis at its center. To create a massive sense of scale and enclose the playable area, large backdrop meshes were added to form distant, impassable canyon walls, grounding the world and creating an epic, cinematic horizon.

<img width="800" alt="The redesigned world map, featuring a central oasis surrounded by a vast desert canyon." src="https://github.com/user-attachments/assets/de24f48e-592e-4612-8421-83c9fc56a9ef" />
<br>
<img width="800" alt="The view from the oasis, with the new canyon walls providing a stunning backdrop." src="https://github.com/user-attachments/assets/5900b81a-dd88-4d50-bb8c-40a569541344" />
<br>
<img width="800" alt="The expansive desert region, showing the scale and detail of the new environment." src="https://github.com/user-attachments/assets/cdca55a0-dcee-4bee-a20e-eb0027448b8c" />


## Technology Stack

* **Game Engine:** Unreal Engine 5.6
* **Programming:** C++ (for gameplay systems), Blueprints (for prototyping and logic scripting)
* **Assets:** Quixel Megascans for high-quality environmental assets.
* **Version Control:** Git & GitHub

## Project Roadmap

### **Phase 1: Environment & Foundation (Complete)**
* [x] Initial landscape sculpting and texturing.
* [x] Populating the world with foliage and environmental assets.
* [x] Establishing advanced lighting and post-processing.
* [x] World redesign and backdrop implementation.

### **Phase 2: Core Gameplay (In Progress)**
* [ ] Implementing a playable character controller (movement, abilities).
* [ ] Developing the core combat system (melee attacks, dodging, blocking).
* [ ] Creating the first demon enemy type with basic AI.
* [ ] Building the player HUD and inventory systems.

### **Phase 3: Content & Narrative (Planned)**
* [ ] Designing and implementing the main quest line.
* [ ] Creating additional enemy types and boss battles.
* [ ] Building key locations and points of interest within the world.
* [ ] Adding sound effects and a musical score.

Stay tuned for more updates!
