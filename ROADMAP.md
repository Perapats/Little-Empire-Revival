# Public Roadmap

Roadmap items move to complete only after the client-visible behavior and relevant local state have been verified. Temporary test rules will remain labeled as synthetic.

## Current milestone: battle entry and result prototype

**In progress.** Visitor registration, test-city loading, Barracks access, and one synthetic Footman collection have been exercised locally. The same isolated profile also displayed one Footman in Castle Troops after a data-preserving restart and re-registration, using synthetic Castle data; this verifies roster display only. Formation persistence, battle entry, and battle results remain unverified.

## Planned milestones

1. **Verify the basic battle loop**
   - Trace a battle request using evidence from the client.
   - Verify battle entry, result handling, and persistence using the emulator and isolated test data.
2. **Restore tutorial progression**
   - Identify why the Hourglass confirmation does not advance the tutorial.
   - Verify the complete tutorial path without relying on a direct-to-city test bypass.
3. **Improve city progression**
   - Verify building placement and persistence across reconnects.
   - Identify which resource and progression values can be established from reliable evidence.
4. **Expand the single-player prototype**
   - Add only client-visible systems whose behavior can be tested.
   - Keep replacement rules separate from verified original behavior.
5. **Plan broader game modes**
   - Investigate Arena, Conquest, and multiplayer only after the city, troop, and basic battle loop are stable.
   - Design account safety, data isolation, and operations before considering any public server.
6. **Improve repeatable testing and releases**
   - Expand emulator-based end-to-end checks.
   - Publish version and changelog updates only for verified milestones.

## Out of scope for this documentation repository

This repository is not a place to publish implementation code, APKs, game assets, saves, secrets, or private technical logs.
