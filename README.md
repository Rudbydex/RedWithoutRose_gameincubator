#Red Without Rose

**Red Without Rose** is a short wordless narrative game inspired by *Little Red Riding Hood*.  
The game explores fear, pursuit, and transformation through environment, color, and movement rather than dialogue.

This project was developed as part of **Columbia University Game Incubator – Narrative Without Words Track**.

**Play the game on itch.io:**  
https://rudbyde.itch.io/red-without-rose

---

#Concept

The game begins in a desaturated, colorless world.  
As the player progresses and interacts with key objects, color gradually returns, symbolizing awareness, danger, and choice.

Instead of explicit storytelling, meaning is conveyed through:
- Enemy behavior
- Spatial pressure
- Environmental color shifts
- Silence

---

#Gameplay

- **Movement:** WASD / Arrow keys  
- **Goal:** Navigate the environment, avoid the wolf, and reach the ending
- **Core mechanics:**
  - Enemy pursuit based on distance
  - Safe zones that restrict enemy movement
  - Color-based world state changes

---

#Technical Overview (Unity)

- Engine: **Unity (2D)**
- Language: **C#**
- Key systems implemented:
  - Wolf AI with distance-based chasing
  - Trigger-based scene transitions
  - Global color adjustment for narrative progression
  - Safe zone logic to shape player routes

---

#Repository Structure
Assets/
└── Scripts/
├── Player movement
├── Wolf behavior
└── Scene / trigger logic

