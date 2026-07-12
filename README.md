# 2D Platformer — Unity & C#

A 2D platformer game built independently in **Unity** with **C#**, as a hands-on project to apply object-oriented programming concepts (class design, encapsulation, and state management) outside of coursework.

## Gameplay

![Gameplay 1](docs/gameplay%20images%201.png)

![Gameplay 2](docs/gameplay%20images%202.png)

## Features

- **Player controller** — responsive movement, jumping, and input handling
- **Physics & collision** — custom collision-handling classes built on Unity's 2D physics
- **State-machine animation system** — a modular state machine drives player states (idle, run, jump, fall), keeping animation logic decoupled from gameplay code
- **Custom assets** — integrated sprites and animations into the game loop

## Built With

- [Unity](https://unity.com/) (2D)
- C# — object-oriented design: classes for the player controller, states, and collision handling
- Git & GitHub for version control

## Project Structure

```
Assets/            Game scripts, sprites, animations, and scenes
Packages/          Unity package manifest
ProjectSettings/   Unity project configuration
```

Key scripts live in `Assets/Scripts/` <!-- adjust this path/list to match the actual folder, e.g.:
- PlayerController.cs — movement and input
- PlayerStateMachine.cs — state transitions (idle/run/jump/fall)
- CollisionHandler.cs — ground and obstacle detection
-->

## How to Run

1. Clone the repository:
   ```
   git clone https://github.com/waliabd/Platformer.git
   ```
2. Open the project in **Unity Hub** (Unity <!-- add exact version, e.g. 2022.3 LTS -->)
3. Open the main scene from `Assets/Scenes/` and press **Play**

## Controls

<!-- Update to match the actual controls -->
| Key | Action |
|-----|--------|
| A / D or ← / → | Move left / right |
| Space | Jump |

## What I Learned

- Designing interacting classes and debugging runtime issues across them
- Using a state machine to manage animation and player behavior cleanly
- Managing a Unity project with Git, including what belongs in version control (and what doesn't)

## Roadmap

- [ ] Add enemies and hazards
- [ ] Level progression and checkpoints
- [ ] Sound effects and music

---

*Built by [Wali Abdullah](https://github.com/waliabd) — Computer Science student at CUST, Islamabad.*
