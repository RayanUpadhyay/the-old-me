# THE OLD ME

> You can't outrun who you used to be.

A first-person psychological and body-horror game for **Mac and Windows**.

Halden Tower comes down in seven days. One tenant refused to leave, and he isn't the only one still inside.

![THE OLD ME logo](marketing/the-old-me-logo.png)

## Status

🩸 **In development.** Night 1 is being built first and will be released free on [itch.io](https://itch.io). Nights 2–5 will follow.

| Part | Status |
|---|---|
| Night 1 code | Written, being set up in Unity |
| Night 1 art and sound | In progress |
| Nights 2–5 | Planned |

## Content warning

**18+ (Mature).** Contains blood and gore, body horror, intense violence and strong language. A **reduced-gore** option is available in Settings.

## Features

- **One condemned tower block** that changes around you, night after night
- **A lamp in your hand** as your main light, in a building where the power keeps failing
- **Claws that cost you:** filing them, using them and bleeding for it
- **Hiding, holding your breath and running** on an old man's body
- **No voice acting.** Every voice comes through static, tape hiss and subtitles
- **Five nights, five endings,** decided by one last choice

## Controls

| Key | Action |
|---|---|
| W A S D | Walk |
| Shift | Hurry (he tires quickly) |
| Mouse | Look |
| E / Left click | Use, read, close notes |
| F | Lamp on / off |
| Hold left click + drag | File the claws |
| Esc | Pause |

## Built with

- **Unity 6 LTS** with the **Universal Render Pipeline (URP)**
- **C#**
- **Git LFS** for large assets (models, textures, audio)
- Developed on a MacBook Pro (Apple Silicon), with builds for macOS and Windows

## Project structure

```
the-old-me/
├── Assets/
│   ├── Scripts/
│   │   ├── Core/          # Settings, gore toggle, scene loading
│   │   ├── Player/        # Movement, lamp, footsteps, breathing
│   │   ├── Interaction/   # Interacting, notes, doors
│   │   ├── Environment/   # Flickering lights, ambient sounds, scares
│   │   ├── Night1/        # Night 1 events and the director that runs them
│   │   └── UI/            # Menus, subtitles, fades, settings
│   ├── Scenes/            # MainMenu, Night1
│   ├── Audio/
│   └── Art/
├── marketing/             # Logo and promo images
├── BRIEF.md               # The game's design brief
├── ASSETS.md              # Every sound and asset the game needs
└── NIGHT1_SETUP.md        # How to set up and playtest Night 1 in Unity
```

## Running it from source

1. Install [Unity Hub](https://unity.com/download) and **Unity 6 LTS** with **Windows Build Support (Mono)**.
2. Install Git LFS, then clone:
   ```bash
   git lfs install
   git clone https://github.com/RayanUpadhyay/the-old-me.git
   ```
3. Open the folder in Unity Hub (**Add → Add project from disk**).
4. Open `Assets/Scenes/MainMenu.unity` and press **Play**.

New to the project? Start with `NIGHT1_SETUP.md`.

## Roadmap

- [ ] Night 1 grey-box playable in Unity
- [ ] Night 1 art, lighting and sound
- [ ] Playtesting and polish
- [ ] **Night 1 release on itch.io (free)**
- [ ] Nights 2–5
- [ ] Full release, then Steam

## Credits

Created by **Rayan Upadhyay**. [rayanupadhyay.com](https://rayanupadhyay.com)

Third-party sounds and assets are credited in `Assets/Audio/CREDITS.txt` and `Assets/Art/CREDITS.txt`.

## License

© Rayan Upadhyay. All rights reserved. This repository is for development and is not licensed for reuse or redistribution.
