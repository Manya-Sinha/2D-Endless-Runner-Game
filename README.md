# 2D-Endless-Runner-Game
A 2D endless runner game made in Unity 6. Jump over obstacles, beat your saved high score, and play against a scrolling parallax background.
# Square Runner

A 2D endless runner built in Unity 6 (6000.0.85f2). A square runs along the ground, and you jump over obstacles that speed up the longer you survive.

## Features
- Jump with SPACE (hold for a higher jump), or click/tap
- Random obstacle groups of 1–3 with a gradually increasing speed
- Live score, Game Over screen and Restart button (or press R)
- Saved high score using PlayerPrefs
- Scrolling parallax background (sky, mountains, hills, flowers)

## Controls
| Action | Key |
|---|---|
| Start / Jump | SPACE or mouse click |
| Higher jump | Hold SPACE |
| Restart | RESTART button or R |

## Play it
Download `SquareRunner_Windows.zip` from the [Releases](../../releases) page, unzip the whole folder, and run `SquareRunner.exe`.

## Open the project
1. Install Unity 6000.0.85f2 from Unity Hub.
2. Clone this repo and add the folder in Unity Hub.
3. Open `Assets/Scenes/RunnerScene`.
4. In Project Settings > Player, set Active Input Handling to **Both**.

## Scripts
- `RunnerPlayerController` – jumping and collisions
- `RunnerObstacleSpawner` – spawns obstacles
- `RunnerWorldController` – speed and obstacle movement
- `RunnerGameManager` – game states, score, UI, high score
- `ParallaxLayer` – scrolling background

## Built with
Unity 6, C#, TextMeshPro
