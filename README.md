# Little Empire Revival

Little Empire Revival is a community development effort to make a local, playable revival of the classic Little Empire experience. The original server source is not available to this project, so development focuses on rebuilding the client-facing server behavior from testable observations and clearly marked replacement rules.

This repository is for **public documentation and progress tracking only**. It does not host the game client, source code, server implementation, game assets, saves, or internal development notes.

## Versions

- **Revival Server:** `0.1.0-alpha` — proposed early prototype baseline.
- **Original Camel Games client:** `1.26.4` — the client version used for compatibility testing.

These are separate version numbers. The Revival Server version does not change or identify the original client.

## Current status

The local prototype has verified a narrow city and recruitment loop in an Android emulator: the client can register with the local replacement server, load a test city, and complete one synthetic Footman recruitment and collection. A separate test also verified that a preloaded troop can appear in the Castle roster screen.

The playable-prototype progress is estimated at **about 30%**. This is a rough planning estimate, not a measured or verified completion percentage. The tutorial, original economy, complete battle loop, multiplayer, and other major systems are unfinished.

See [STATUS.md](STATUS.md) for the evidence boundaries and [ROADMAP.md](ROADMAP.md) for planned work.

## Project principles

- Preserve the original client and distinguish observed behavior from temporary replacement rules.
- Verify each milestone with repeatable local tests before describing it as complete.
- Keep synthetic test values clearly labeled; they are not recovered official game balance.
- Do not publish private implementation files, client packages, game data, credentials, or internal notes.

## Compatibility snapshot

Compatibility has been exercised with Camel Games client 1.26.4 in an Android 9 (API 28), x86 emulator using software rendering. This does not establish compatibility with other Android versions, device architectures, or public servers.

## Contributing

This public repository tracks documentation milestones. It is not a source-code repository. Any future public development process will be described here before source or binaries are considered for release.


