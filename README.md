# Renpay Game Developer

A reusable Codex skill for creating, improving, testing and releasing Ren'Py visual novels and exploration games. It captures practical lessons from a Windows and Android game project without including that game's private files, assets, signing keys or advertising IDs.

## What it covers

- Project scope, story, characters and a playable vertical slice
- Modular Ren'Py systems, exploration maps, time, quests and saves
- Original assets, sprites, UI, accessibility, audio and visual QA
- Windows and Android testing, packaging, signing and release preparation
- Optional rewarded ads, consent, privacy and store review
- Itch.io page preparation, platform downloads and search indexing

## Install in Codex

Copy this repository folder to your Codex skills directory as `renpay-game-developer`. On Windows this is typically `C:\Users\<your-user>\.codex\skills\renpay-game-developer`. The folder must contain `SKILL.md` and `references/`. Restart Codex or refresh its skills if it does not appear.

## Use

Ask Codex to use `$renpay-game-developer` with your game folder, goal and constraints. For example:

> Use $renpay-game-developer to inspect my Ren'Py game, prepare a development checklist and improve the map. Preserve my existing saves.

The skill adapts to the project and does not build, publish, add ads, or reuse another game's assets unless the user authorizes that work. Store policies and SDK versions change; always consult current official documentation. A skill is guidance, not a guarantee of store approval or a substitute for testing.

## Structure

- `SKILL.md` — skill entry point and workflow
- `references/` — planning, asset, QA, release and ad guidance
- `LICENSE` — reuse terms for this skill's text

## Contributing

Report issues or propose focused improvements through GitHub issues or pull requests. Do not include credentials, player saves, proprietary assets, signing keys or private account information in contributions.

## License

MIT. See [LICENSE](LICENSE). The license covers this skill's files only, not third-party games, engines, music or artwork.
