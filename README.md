Squeek Mailroom

A hardware-connected sorting puzzle game for the Squeekchain ecosystem.

Squeek Mailroom is a browser-based game where players sort incoming packages into the correct destinations: FOOD, TOOLS, or TOYS. Live wheel activity makes the conveyor animation and sorting challenge respond to real hardware RPM.

Live Demo

Current playable version — V3.3 RPM Sync

https://zurickzar.github.io/squeek-stake-lab/mailroom-v3-3-rpm-sync.html

Core Features

- Interactive package-sorting gameplay.
- Live hardware status from the public Squeekchain API.
- Live RPM and total-distance readings.
- Conveyor animation speed synchronized with live RPM.
- Sorting timer adjusts to the available RPM reading.
- XP, levels, combos, and lives.
- Daily sorting mission and Special Delivery milestones.
- Local progress persistence in the browser.
- Practice mode when valid live hardware data is unavailable.
- Reduced-motion accessibility support.

Hardware Integration

The game reads public measurement data from:

https://api.squeekchain.com/v1/status

Hardware readings are accepted only when the API reports hardware provenance, online freshness, valid numeric measurements, and a recent observation timestamp.

The interface falls back to Practice Mode when valid live hardware data is unavailable.

How to Play

1. Open the live demo.
2. Check whether LIVE HARDWARE is available.
3. Sort each package into FOOD, TOOLS, or TOYS before the timer expires.
4. Build combos, earn local XP, and complete daily missions.

Supporting Modules

This repository also contains supporting learning and safety modules:

- Academy
- Challenge Lab V2
- Challenge Lab V3
- Builder Hub

These modules complement the main Squeek Mailroom game.

Technical Notes

- Built with HTML, CSS, and JavaScript.
- Uses the public Squeekchain status API.
- No API key is required for public status reads.
- No wallet connection or blockchain transaction is required to play.
- Browser localStorage is used for local game progress.
- Practice mode is available when valid live hardware data is unavailable.

Project Status

Current playable release: Mailroom V3.3 RPM Sync.

This is an independently developed project. Genesis attribution and verification have not yet been completed; any required verification details will be added only after the official process provides them.

Disclaimer

XP, levels, and gameplay bonuses are local in-game progress only. They are not official tokens, guaranteed financial value, or confirmed on-chain rewards.

squeekchain-project: 7af434d0-7c8f-4230-96ee-d899b6fe5a4c
