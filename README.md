# NEGATIVE RUNNER

**The worst score game ever.** A browser-only 3D endless runner where surviving makes your score worse. The project uses HTML5, CSS3, JavaScript, Three.js, WebGL, localStorage, and Web Audio API.

## Run

Open the folder in Visual Studio Code and launch `index.html` with Live Server. The Three.js library loads from jsDelivr, so an internet connection is needed the first time. No backend or build step is required.

## Deploy To Vercel

Import this repository into Vercel with the project root set to `/`. Use the **Other** framework preset, leave the build command empty, and deploy. Vercel serves `index.html` as the site entry point.

## Controls


## Features

- Pooled endless road, obstacles, buildings, clouds, lights, trees, shadows, fog, and a moving star field
- Modular `Game`, `Player`, `ObstacleManager`, `EnvironmentManager`, `ScoreManager`, `UIManager`, `AudioManager`, and `LeaderboardManager` classes
- Negative score leaderboard persisted in localStorage
- Collision effects, combo system, speed progression, score milestones, pause/restart, mute, mobile controls, and Web Audio fallback sounds
- `MAKE SCORE WORSE` and `PANIC` buttons, because the core loop was not pointless enough

## Credits

Built as a deliberately over-engineered useless hackathon game.

> RUN FOREVER. LOSE EVERYTHING.




# [Project Name] 🎯

