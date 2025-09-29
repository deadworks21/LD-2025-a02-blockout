# Dungeon Blockout — Intro to Level Design (A02)

A gray-boxed dungeon built for **Intro to Level Design – Fall 2025**.  
Although the assignment’s focus was strictly *block-out*, I experimented with using **light, darkness, triggers, and sight-lines** to guide the player — and wrapped it all in a subtle **“haunted-Unreal-project”** narrative.

---

## 🎮 Tone & Story

> *You boot up what’s supposed to be a simple student block-out file… but something’s wrong.  
>  The editor warns you the level wasn’t meant to ship.  
>  Geometry hangs overhead like a mirrored echo of the space you walk through.  
>  Beyond each pool of light there’s only an infinite black void.  
>  As you move forward, unseen triggers bring cold lights to life one by one, and distant sounds hint that you’re not alone inside the build.  
>  It feels less like testing a dungeon and more like discovering found-footage from a project that should have stayed hidden on a hard-drive.*

This tone drove the layout decisions: sparse lighting, pitch-black negative space, broken mirrored chunks overhead, and audio/lighting cues that push the player to explore deeper.

---

## 🗺️ Project Goals
- Demonstrate **spatial composition** using only primitive meshes.
- **Guide the player** using contrast between light & darkness, rather than combat or heavy props.
- Use **trigger boxes** to:
  - switch lights on/off as the player moves,
  - fire off ambient sounds,
  - reveal/close routes at key sight-lines.
- Implement at least one **collectible** to pull the player through the space.
- Block-out **custom materials** (floor / walls / ceiling) to clarify navigation.

---

## 📂 Repository Layout
