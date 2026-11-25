# Sacura Novel Engine 3D

**Create visual novels and story-driven games in 3D.** Lay out a scene, write a branching conversation, and jump into Play to see what happens when the player makes a choice.

**[Download Sacura Editor](https://github.com/1000bets/Sacura-Releases/releases)** · [Читать по-русски](README.ru.md)

![Sacura Editor playing a branching dialogue in the Twins Courtyard 3D scene, with the story graph open below](screenshots/branching-dialogue.webp)

*Twins Courtyard, playtested in the editor with the story graph open.*

## What you can make

- **Branching stories.** Connect dialogue, choices, conditions, and variables in Story Flow. A line of dialogue can cut to a different camera, cue an animation, or start a quest.
- **Places to explore.** Compose 3D scenes with lights, cameras, materials, and reusable prefabs. Mix skeletal characters with animated 2D sprites for a 2.5D look.
- **Quests that respond to the world.** Track objectives and world state. Use a conversation, an item pickup, or an interaction to advance the story.
- **Characters with their own behavior.** Use animation graphs for movement and reactions. Build NPC behavior with navigation, Behavior Trees, and a Blackboard, then follow execution in the debugger. Use Python components when you need custom gameplay.
- **A prototype you can play right away.** Start with a built-in template, press **Play**, and change one dialogue choice or interaction to make it your own.

## Inside the editor

| Courier Station in Play mode | Sprite animation graph | Behavior Tree debugger |
| --- | --- | --- |
| [![A delivery robot and dispatcher dialogue in a 3D depot](screenshots/courier-station.webp)](screenshots/courier-station.webp) | [![The courier robot preview next to its animation state machine](screenshots/animation-graph.webp)](screenshots/animation-graph.webp) | [![A paused behavior tree with its active nodes and execution history](screenshots/behavior-tree.webp)](screenshots/behavior-tree.webp) |

## Get started

1. Open [Releases](https://github.com/1000bets/Sacura-Releases/releases) and pick your platform under **Assets**.

   | Platform | Archive |
   | --- | --- |
   | Windows x64 | `Sacura-Editor-Windows-x64.zip` |
   | Linux x64 | `Sacura-Editor-Linux-x64.tar.gz` |
   | macOS 14+ on Apple Silicon | `Sacura-Editor-macOS-arm64.zip` |

2. Extract the archive and launch **Sacura Editor**. On macOS, open the extracted app. On Linux, run `./sacura-editor` from the extracted folder.
3. Create a project from **Visual Novel** for a dialogue-first example or **Courier Station** to try 2.5D gameplay. Press **Play** to explore the example before editing it.

Found a bug? Include the build number, your OS, and the steps to reproduce it. [Open an issue](https://github.com/1000bets/Sacura-Releases/issues/new).
