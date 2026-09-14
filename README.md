# GhostDLL — VTMB Standalone VR Experiment
**Early standalone VR proof of concept for Meta Quest 3.**

>
> 

https://github.com/user-attachments/assets/b80aafca-f92c-406e-a1ac-4dd45988ffcd


[![Watch the early Quest 3 proof of concept](preview.jpg)](GhostDLL_Bloodlines_VR_POC_GitHub_under10MB.mp4)

**[Watch the proof-of-concept video](GhostDLL_Bloodlines_VR_POC_GitHub_under10MB.mp4)**



This is an independent experimental project exploring whether **Vampire: The Masquerade – Bloodlines** can work as a convincing standalone VR experience.

> Early technical prototype.  
> No public build is available yet.

## Proof of concept

<!-- KEEP THE EXISTING GITHUB VIDEO ATTACHMENT BELOW -->

https://github.com/user-attachments/assets/KEEP-YOUR-CURRENT-VIDEO-ID-HERE

The video shows an early internal development build running on Meta Quest 3.

It is not representative of final graphics, UI, performance or gameplay.

---

## Why this project exists

This project started from a simple question:

**Why has Vampire: The Masquerade – Bloodlines received so little attention as a potential standalone VR experience?**

Bloodlines remains a distinctive first-person RPG with an unusual combination of:

- atmospheric environments
- dialogue-heavy gameplay
- memorable characters
- exploration
- ranged and melee combat
- multiple dialogue choices
- different ways of approaching situations

Many of these elements could translate particularly well to VR.

The purpose of this experiment is to see how far that idea can actually be pushed on standalone hardware such as **Meta Quest 3**.

---

## This is a proof of concept

I am an independent enthusiast, not a professional game development studio.

I do **not** currently promise a complete port of the entire game.

One of the main goals of this project is simply to demonstrate that a standalone VR interpretation of Bloodlines is technically interesting and worth exploring.

If this prototype helps attract the attention of experienced VR developers or established teams interested in taking the idea further, I would consider that a success.

---

## Long-term technical direction

The intended public architecture is based on a simple principle:

**Ghost2DLL should provide the VR runtime — not the original game.**

The goal is for a future runtime to work with game data supplied by the user from their own legally obtained installation of Vampire: The Masquerade – Bloodlines.

Conceptually:

```text
Legally owned Bloodlines installation
                |
                v
      user copies game data
         to Meta Quest
                |
                v
        Ghost2DLL runtime
                |
                v
     standalone VR experience
