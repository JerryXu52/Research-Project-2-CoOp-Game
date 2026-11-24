# Out of Frame — Research Project 2 Proposal

**English** | [中文](README.zh-CN.md)

**Team:** Jerry Xu & TongLin
**Engine:** Unity (2D, C#)
**Category:** Go somewhere unfamiliar. This is our first full game built in Unity.

## The project in one sentence
A 2D side-scrolling, two-player co-op puzzle-platformer in Unity, inspired by *Pico Park* and *Picnic Adventure*, where an animator gets sucked inside their own 3D software and has to clear one level for each stage of the animation pipeline (Modeling → Rigging → Animation → Lighting → Rendering) to finish the film.

## Why this one
We both work inside 3D software every day, but neither of us has built a game. Afterward we'll be able to:
- Build a complete, playable game in Unity: 2D physics, character controllers, local two-player input, scene flow, and a build that runs outside the editor.
- Design co-op puzzles where neither player can win alone (stacking, pushing, holding switches, sharing a key).
- Turn a 2D art style (CalArts-style "bean" faces, simple shapes, bold outlines) into game-ready sprites and animation.
- Turn what we know about the production pipeline into game design. Each level's mechanic comes from its stage of production: extruding platforms in Modeling, linking a joint chain in Rigging, scrubbing a timeline to move objects in Animation, using light and shadow as platforms in Lighting.

## What we'll show
Both. A playable build that two classmates can pick up and play on our last day (on a shared keyboard or two gamepads), plus a short trailer/playthrough video and this repo with the Unity project and a short write-up of what we learned.

## The three weeks
- **By Dec 1: the core works.** Unity project and repo set up. Two players can move, jump, stand on each other's heads, and push objects. Basic Pico Park-style rules: one key, one door, and both players must reach the exit. Character designs and the CalArts-style art direction locked. Greybox of Level 1 (Modeling).
- **By Dec 8: the game exists.** Levels 1–3 (Modeling, Rigging, Animation) playable, each with its own mechanic. Player sprites with idle/run/jump animations. Title screen, level select, restart, and level-complete flow. First playtest with classmates.
- **By Dec 14: polish and finish.** Levels 4–5 (Lighting, Rendering) and a short intro and ending that tell the story. Final background art styled like a 3D software UI, sound and music, fixes from playtesting, and a standalone build. Trailer recorded.

## The smallest version that still counts
A standalone build with two playable co-op characters in final art and **two complete levels** (Modeling and Rigging), each with its own pipeline-themed mechanic, plus a title screen and a story intro. The later levels can be shown as greybox or concept art.

## The riskiest part
- **Co-op physics that feel good.** Standing on a partner's head, pushing together, and sharing moving platforms easily turn buggy (jitter, sliding off, getting stuck). We'll build and tune this in week 1, before any level depends on it.
- **The pipeline mechanics themselves**, especially the Animation level's timeline scrubbing, which moves objects over time while both players are standing on them.
- **Scope, with two people new to Unity.** To keep it manageable we're doing local co-op only (no online play), and we'll greybox and playtest every level before making its final art.

## Tentative split
- **Jerry:** player controller, co-op physics, level mechanics, game flow.
- **TongLin:** character and environment art, sprite animation, UI, story panels.
- **Together:** level design, playtesting, sound, trailer.
