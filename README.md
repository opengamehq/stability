# opengame-stability

Make a browser game crash-free on every device and browser, and prove it. Covers zero crashes as the release bar with recoveries counted, a structural guard per crash class, soak tests, named pools, crash reports that survive reload, a watchdog that tells a slow load from a hang, one composite per frame, no late timer that moves the game, no silent fallback, a booted fallback renderer and the served build checked.

It is one of the [OpenGame](https://opengame.io) agent skills, which teach a coding agent such
as Claude Code, Codex, Cursor or OpenCode to build a browser game and put it online.

## Install

```bash
npx skills add opengamehq/stability
```

The skill installs under its own name, `opengame-stability`. Every OpenGame skill, each under its own
name, installs from [opengamehq/opengame](https://github.com/opengamehq/opengame):

```bash
npx skills add opengamehq/opengame
```

How the skills fit into making and shipping a game is at [docs.opengame.io](https://docs.opengame.io).

## Changes

This is version 1.1.0. [CHANGELOG.md](CHANGELOG.md) lists what changed in each one.

## Issues

OpenGame's release tooling writes this repository from [opengamehq/opengame](https://github.com/opengamehq/opengame),
so a change made here is replaced by the next release, and it does not take pull requests.
Open an issue [there](https://github.com/opengamehq/opengame/issues) for a skill that teaches the wrong thing.

## License

[Apache 2.0](LICENSE).
