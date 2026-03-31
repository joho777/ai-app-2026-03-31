# MapLeak Lab

A single-file, browser-only web app that simulates the risk of accidentally shipping JavaScript source maps (".map" files) in public packages.

Inspired by today's trend: "Claude Code's source code has been leaked via a map file in their NPM registry".

## What it does

- Scenario builder for package + bundling + attacker model
- Explainable risk score (0–100) with breakdown
- Fake-but-plausible source map preview generator
- Recon timeline simulator
- Guardrail patch plan generator
- Shareable scenarios via URL hash
- Local leaderboard (saved runs stored in localStorage)

## Run it

Open `index.html` directly in your browser.

## Notes

This is a simulation meant for education and checklist design, not a security assessment.
