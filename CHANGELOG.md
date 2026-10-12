# Changelog

This changelog records verified public milestones for the Revival Server and prototype. Client version 1.26.4 is the separate original Camel Games client version. A Revival version does not mean the game is complete.

## 0.1.0-alpha — proposed baseline, 2026-10-13

This is a proposed documentation baseline for a local prototype. It is not a complete-game release and has not been tagged.

### Verified

- The 1.26.4 client connected to a local replacement server, registered as a Visitor, and loaded an isolated test city in the Android emulator.
- The tested city rendered its House and Barracks. The Barracks selection and recruitment panel were opened.
- One Footman followed a synthetic production timer and collection flow. The test server recorded the collected troop in isolated local test data.
- After a client restart and re-registration, the isolated city and Hero panel loaded.
- After recruitment, collection, a data-preserving client restart, and re-registration, the same isolated profile displayed one Footman in Castle Troops. This used a synthetic Castle probe and synthetic ArmyData, and verifies the roster read/display path only.
- The existing local backend regression suite passed 8 tests.

### Limitations

- The tutorial still fails to advance after its Hourglass confirmation.
- Recruitment timing and troop data used in tests are synthetic, not recovered official balance.
- A basic Castle formation commit is verified on synthetic local data; saved-slot retrieval and battle entry remain unverified.
- Authentication, the full economy, server-validated combat and persistent battle results, Arena, Conquest, multiplayer, and public deployment are incomplete.

### Compatibility

- **Revival Server:** `0.1.0-alpha` proposed.
- **Original Camel Games client:** `1.26.4`, tracked separately.
- **Verified test environment:** Android 9 / API 28, x86 Android emulator, software rendering.

## Castle formation storage milestone - 2026-10-13

### Verified

- The original 1.26.4 client loaded one synthetic Footman into Castle Formation.
- The local server stored the submitted formation, and the client returned to the city twice without a crash.
- The backend test suite passed 12 tests, including formation persistence and invalid-input checks.
- This milestone covers only local formation storage on synthetic data. It does not verify saved-slot retrieval, battle entry, combat, tutorial completion, or original game balance. Revival Server 0.1.0-alpha remains proposed and untagged.
