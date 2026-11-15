🚀 Second Chance: Space Mission Rescue

Investigate Real Failed NASA Missions, Redesign the Spacecraft & Fly Again!

Second Chance is an interactive, zero-dependency educational space engineering simulation built for the NASA International Space Apps Challenge. Guided by Orbi (your friendly robot assistant), 1 to 4 players step into NASA Mission Control to solve historical space mysteries, balance real engineering constraints, and rewrite space history.

✨ Key Features

🕵️ Real Historical Case Files & Open Missions:

Mars Climate Orbiter (1999): Uncover the famous imperial-vs-metric unit mismatch before atmospheric entry.

Orbiting Carbon Observatory (2009): Expose falsified supplier test certificates and payload fairing risks.

Kepler Space Telescope (2013): Survive reaction-wheel failures using solar radiation pressure (K2 rescue).

Vanguard TV-3 (1957): Fix first-stage tank pressure and ignition sequences on America's first satellite attempt.

Swift Rescue / LINK (2026): Race against solar drag with a robotic servicing mission.

Nile Watch (Open Mission): Design an Egyptian Earth-observation CubeSat to monitor crops, water, heat, or dust storms.

Cadet Story Missions: Kid-friendly lunar and Martian survival scenarios (Lunar Sprout & Rover Ruby).

👥 1–4 Player Co-Op & Real NASA Roles:

🔭 Science Lead: Defines scientific objectives and selects payload instruments.

🛠️ Spacecraft Engineer: Manages solar arrays, batteries, flight computers, attitude control, and propulsion.

🧭 Navigator: Selects target orbits, tracking networks, and communications.

💼 Mission Boss: Controls budget, launch windows, launch vehicles, and pre-flight verification tests.

🎚️ 3 Adaptive Difficulty Tiers:

Cadet (Ages 8–12): Visual meters, extra budget/schedule margin, and automatic hints from Orbi.

Engineer (Ages 13+): Real engineering units (kg, W, Wh, $M), on-demand hints, and 5 mission challenges.

Flight Director (Experts): Tight budgets, strict launch rules, 4 in-flight anomalies, zero hints, and 7 mastery challenges.

🌍 Fully Bilingual (English & Arabic RTL):

Instant mid-game switching between English (LTR) and Arabic (RTL) across all clues, telemetry logs, and UI elements.

⚡ Zero-Dependency Single-File Architecture:

Built purely with vanilla HTML5, CSS3, custom inline SVGs, and HTML5 Canvas animations—runs offline or on any static host (GitHub Pages) with zero build steps.

🕹️ 5-Phase Gameplay Loop

Incident Replay & Investigation: Watch what went wrong, flip evidence cards on the detective board, and deduce the root cause.

Mission Objectives: Choose primary and secondary science goals and review verification requirements.

Spacecraft Design & Build: Assemble subsystems while monitoring mass, power, battery depth-of-discharge, data downlink, and budget.

Launch & Pre-Flight Tests: Pick your orbit, launch vehicle, and high-impact tests (Thermal-Vacuum, Vibration, Interface/Unit Checks, Hardware-in-the-Loop).

Go / No-Go Poll & Live Flight: Vote across all 4 stations and handle real-time space emergencies to earn stars and mission badges.

🚀 Quick Start (Local & GitHub Pages)

No installation, Node.js, or bundler required:

Clone the repository:

git clone https://github.com/YOUR_USERNAME/second-chance-space-rescue.git


Run locally: Open index.html directly in any modern web browser.

Deploy on GitHub Pages: Go to Settings → Pages → Source, select your main branch, and launch immediately.

 Repository Structure

├── index.html          # Main bilingual simulation & game engine (Single-file architecture)
├── presentation.html   # Interactive 12-slide NASA Space Apps pitch deck
└── README.md           # Project documentation


 Tech Stack

Core: Semantic HTML5, Modern CSS3 (Custom Properties, Grid/Flexbox, RTL Logical Properties), Vanilla ES6+ JavaScript

Graphics & Simulation: Custom procedural SVG spacecraft & icon generator + 60fps HTML5 Canvas orbital/flight renderer

Data Persistence: localStorage for tracking high scores, stars, and earned mission badges

 Historical & Engineering References

Mars Climate Orbiter Mishap Investigation Board, Phase I Report (1999)

NASA Launch Services Program — Taurus XL Fairing Failure Summaries (2019)

NASA Kepler / K2 Mission Archives & NASA CubeSat 101 Guide

NASA NSSDC Vanguard TV-3 & Swift Boost Mission Updates
