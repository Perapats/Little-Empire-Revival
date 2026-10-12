# Changelog

This changelog records verified public milestones for the Revival Server and prototype. Client version 1.26.4 is the separate original Camel Games client version. A Revival version does not mean the game is complete.

## 0.1.0-alpha — proposed baseline, 2026-10-13

This is a proposed documentation baseline for a local prototype. It is not a complete-game release and has not been tagged.

### Verified

- The 1.26.4 client connected to a local replacement server, registered as a Visitor, and loaded an isolated test city in the Android emulator.
- The tested city rendered its House and Barracks. The Barracks selection and recruitment panel were opened.
- One Footman followed a synthetic production timer and collection flow. The test server recorded the collected troop in isolated local test data.
- After a client restart and re-registration, the isolated city and Hero panel loaded.
- In a separate test profile with a preloaded synthetic troop, the Castle Troops screen displayed that troop.
- The existing local backend regression suite passed 8 tests.

### Limitations

- The tutorial still fails to advance after its Hourglass confirmation.
- The Castle roster display has not yet been verified after recruiting and collecting the troop in that same profile.
- Recruitment timing and troop data used in tests are synthetic, not recovered official balance.
- Authentication, the full economy, authoritative combat, Arena, Conquest, multiplayer, and public deployment are incomplete.

### Compatibility

- **Revival Server:** `0.1.0-alpha` proposed.
- **Original Camel Games client:** `1.26.4`, tracked separately.
- **Verified test environment:** Android 9 / API 28, x86 Android emulator, software rendering.



