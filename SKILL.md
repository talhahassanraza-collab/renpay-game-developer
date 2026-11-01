---
name: renpay-game-developer
description: Develop, test, and release Ren'Py visual novels and exploration games, including project planning, UI, assets, Windows and Android builds, and optional rewarded ads. Use for Ren'Py game development or release tasks.
---

# Renpay Game Developer

Help build and release the user's Ren'Py game. Adapt the scope, genre, art direction, platforms and business model to the current project; never assume that another game's story, schedule, assets, credentials or requirements apply.

## Start with the real project

- Inspect project instructions, the existing game folder, Ren'Py version, configuration, assets, saves and any release notes before editing. Work only in authorized locations. Preserve existing files and user changes; back up only when the risk warrants it.
- Identify the actual current task and give a short progress update. Maintain a project checklist for multi-stage work, recording evidence and distinguishing done, in progress, untested and blocked. Do not ask about routine decisions the user has delegated.
- For a new game, agree on a small playable scope, audience, content boundaries, platforms and art direction. Do not introduce deadlines, time limits, or monetization without authorization. Keep existing saves compatible where practical.

## Build a playable game

- Organize story, characters, locations, state, screens and assets into cohesive modules that fit the existing project. Make a working vertical slice before expanding routes, quests or locations.
- Implement features that serve the design: dialogue and meaningful choices; map navigation; location/time rules; tasks; relationships; inventory; economy; saves; audio; settings; and optional phone interface. Do not claim a feature is complete from a checklist alone.
- Use original or properly licensed art, music and fonts. Verify supplied assets and naming before wiring them in. Respect requested reference layouts without copying protected artwork. Match sprites, expressions, anchor positions and background variants to the scene.
- Make interfaces legible and usable by mouse, keyboard and touch where relevant. On maps, align interactive regions and hover highlights to the actual artwork, support locked areas and provide a touch-accessible alternative. Ensure screen overlays do not cover dialogue or other controls.
- Keep time advances, quest conditions, economy changes and reward grants explicit and testable. Allow users to play without optional monetization when appropriate.

## Verify and report

- Run version-appropriate Ren'Py lint and tests and inspect errors. Exercise affected flows: start/menu, navigation, choices, day/night, saves/load, settings, UI, audio and platform-specific behavior. Test existing saves when state or screens change. Prefer meaningful integration checks to tests that duplicate implementation.
- For visual work inspect the actual screens at target resolution; for mobile work test on a device when possible. Do not claim phone, ad, consent, or release tests succeeded without evidence. Distinguish previous user reports from fresh verification.
- Close or clean up only processes and temporary files created by your own testing; never remove player saves or signing keys unless specifically instructed. Avoid repeated builds when the user has restricted them.
- Explain what changed, how it was checked, and remaining blockers in the user's preferred language and level of detail.

## Load references when relevant

- [Planning, assets and UX](references/planning-and-assets.md): game scope, asset inventory, map interaction, and checklist.
- [Testing and release](references/testing-and-release.md): desktop and Android QA, signing, store assets, itch.io publication and release checks.
- [Android rewarded ads](references/android-rewarded-ads.md): AdMob, privacy/consent, rewards, tests and store-review constraints.
- Verify current SDK, platform, legal and store requirements against official documentation before implementing or releasing; they can change. Treat sample commands and versions as context, not guarantees.
