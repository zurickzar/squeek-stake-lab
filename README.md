Squeek Mailroom

A hardware-connected sorting puzzle game for the Squeekchain ecosystem.

Squeek Mailroom is a browser-based game where players sort incoming packages into the correct destinations: FOOD, TOOLS, or TOYS.

The game reads public Squeekchain hardware measurements and uses real wheel activity to enrich the gameplay experience.

Live Demo

https://zurickzar.github.io/squeek-stake-lab/mailroom-v3-2.html

Core Features

- Interactive package-sorting gameplay.
- Live hardware status from the Squeekchain public API.
- RPM and distance readings.
- XP and level progression.
- Daily sorting mission.
- Special Delivery bonuses.
- Local progress persistence.
- Practice mode when live hardware data is unavailable.

Hardware Integration

The game reads public measurement data from:

"https://api.squeekchain.com/v1/status"

Hardware readings are displayed with freshness and provenance checks.

The game does not claim that local XP or bonuses are official tokens, on-chain rewards, or settled protocol rewards.

How to Play

1. Open the live demo.
2. Check whether LIVE HARDWARE is available.
3. Sort each package into FOOD, TOOLS, or TOYS.
4. Build combos, earn local XP, and complete daily missions.

Supporting Modules

This repository also contains supporting learning and safety modules:

- Academy
- Challenge Lab V2
- Challenge Lab V3
- Builder Hub

These modules complement the main Squeek Mailroom experience.

Technical Notes

- Built with HTML, CSS, and JavaScript.
- Uses the public Squeekchain API.
- No API key required for public status reads.
- Browser localStorage is used for local game progress.
- Practice mode is available when hardware data is unavailable.

Project Status

Mailroom V3.2 is the current stable playable version.

This project is independently developed. Genesis attribution and verification requirements will be added after the official verification process provides the required details.

Disclaimer

Local XP and gameplay bonuses are in-game progress only. They do not represent guaranteed financial value, token rewards, or on-chain earnings.
