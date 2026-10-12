# Project Status

**As of 2026-10-13**

## Progress estimate

The playable prototype is estimated at **about 30%**. This is a rough planning estimate, not a measured or verified completion percentage. The game is not yet fully playable.

## Verified features

- The original Camel Games client version **1.26.4** connected to a local replacement server in an Android emulator, registered as a Visitor, and loaded an isolated test city.
- The test city rendered a House and Barracks; the Barracks recruitment panel opened.
- One Footman completed a synthetic recruitment timer and collection flow. The isolated test state retained the troop.
- After a client restart and re-registration, the test city and Hero panel loaded.
- After recruitment, collection, a data-preserving client restart, and re-registration, the same isolated profile displayed one Footman in Castle Troops. This used a synthetic Castle probe and synthetic ArmyData; it verifies the roster read/display path only.
- The existing local backend regression suite passed 8 tests.

## Incomplete or unverified

- The tutorial does not advance after the Hourglass confirmation.
- Formation persistence and battle entry are unverified; server-validated combat and persistent battle results are incomplete.
- Original resource balances, costs, rewards, and unit balance have not been established.
- Authentication and independent player accounts are incomplete.
- Arena, Conquest, multiplayer synchronization, and public deployment are not implemented.
- Testing covers a limited Android emulator configuration; broader device compatibility is unknown.

## Version and compatibility

- **Revival Server:** proposed `0.1.0-alpha`.
- **Original Camel Games client:** `1.26.4`. This is separate from the Revival Server version.
- Verified client testing used Android 9 / API 28 on an x86 emulator with software rendering. Compatibility with other devices and configurations is not established.

## Release status

This is a local prototype, not a complete or production-ready game. The alpha baseline is proposed and untagged. Synthetic test values are not presented as official game rules.
