# GhostDLL — VTMB Standalone VR Experiment

> Early technical proof of concept for a standalone VR runtime targeting Meta Quest 3.

[![Watch the early Quest 3 proof of concept](media/preview.jpg)](media/GhostDLL_Bloodlines_VR_POC_GitHub_under10MB.mp4)

**[Watch the proof-of-concept video](media/GhostDLL_Bloodlines_VR_POC_GitHub_under10MB.mp4)**

## Why this project exists

This project started from a simple question:

**Why has Vampire: The Masquerade – Bloodlines never received serious attention as a standalone VR experience?**

Bloodlines remains a distinctive first-person RPG, and its atmosphere, conversations, characters and environments make it an unusually interesting candidate for VR.

I am experimenting with a standalone Meta Quest implementation to see how far the idea can be pushed.

This is currently a **technical proof of concept**, not a promise of a complete port. I am an independent enthusiast, not a professional game-development studio, and I do not yet know whether I will personally be able to bring the entire game to completion.

One of the main goals is therefore to demonstrate that the idea is technically interesting and potentially achievable, and hopefully encourage experienced VR developers and established teams to take an interest in Bloodlines.

If this experiment helps attract developers with significantly more experience and resources, I would consider that a success in itself.

## Current status

Very early experimental development.

The video above is a proof of concept running on **Meta Quest 3**. It does not represent the final architecture, visual quality, compatibility or feature set of any future public release.

The current development work and the intended public runtime should be treated as separate stages of the project.

## Intended public architecture

The long-term public target is an **independent VR runtime** that does not distribute the original Bloodlines game data.

The intended installation model is:

1. The user legally owns Vampire: The Masquerade – Bloodlines on Steam.
2. The user installs the GhostDLL VR application on Meta Quest.
3. The user copies the required original game-data files from their own installation to a predefined folder on the Quest.
4. GhostDLL validates and prepares those user-supplied data for its own runtime.
5. The original Windows executable and original Windows engine binaries are not required by the Quest runtime.

For the initial public target, the reference baseline is the clean Steam / official 1.2 game data. Compatibility with unofficial patches, translations or other mods may be investigated later and is not currently promised.

## Development principles

- No original Bloodlines game data in the public repository.
- No original game executable or Windows engine binaries distributed with GhostDLL.
- No third-party mod files distributed without permission.
- User-supplied game data remains read-only.
- GhostDLL-generated cache and runtime data are kept separate from the user's original files.
- The GhostDLL runtime is developed independently from the original game engine.

## Collaboration

Technical discussion, testing feedback and documentation suggestions are welcome.

I would especially be interested in hearing from developers or teams experienced with:

- standalone VR development
- Meta Quest / Android ARM64
- OpenXR
- runtime asset loading
- legacy game-data formats
- game-engine reimplementation and interoperability
- VR interaction and locomotion

At this early stage, please **do not submit copyrighted game data, original game binaries, decompiled source code, or third-party mod assets**.

## Support

GhostDLL is developed in my spare time and is provided independently of any financial contribution.

If you enjoy the project and would like to contribute toward the time and work involved, voluntary support may be offered in the future. Any such contribution would be optional and would not provide access to copyrighted game data or imply ownership of third-party intellectual property.

## Intellectual property

GhostDLL is an unofficial independent technical experiment.

Vampire: The Masquerade – Bloodlines and all associated trademarks, characters, game data, artwork, audio and other original materials belong to their respective rights holders.

This repository does not claim ownership of third-party intellectual property.

Original GhostDLL-authored code, tools, documentation and other original project material remain the property of their respective author unless explicitly licensed otherwise.

This project is not affiliated with or endorsed by the original game's developers, publishers, rights holders, Meta or Epic Games.

## Downloads

**No public game build is currently available.**

The repository is currently being used to document the experiment and show the technical proof of concept.
