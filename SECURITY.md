# Security Policy

## About This Project

**تحدّي العيلة** is a fully client-side browser game.

- **No server** — everything runs in the browser
- **No accounts** — no login, no registration
- **No data collection** — zero analytics, zero tracking
- **No network requests** — after the page loads, no external connections are made
- **No cookies** — game state is stored in `localStorage` only, locally in the user's browser

## Data Storage

The only data stored is the game state (current scores, question bank, settings) saved to `localStorage` on the user's device. This data:
- Never leaves the device
- Is never sent to any server
- Can be cleared at any time via the "حذف الحفظ" button or browser settings

## Reporting a Vulnerability

This project has a minimal attack surface given its client-side-only nature. However, if you discover any issue such as:

- XSS via malformed imported JSON question banks
- Logic errors that allow unintended game state manipulation
- Any unintended external network request

**Please do NOT open a public issue.**  
Contact privately so it can be addressed before disclosure.

## Supported Versions

| Version | Supported |
|---------|-----------|
| Latest (`main`) | ✅ Yes |
| Older commits | ❌ No — always use the latest version |

---

*Ayham Megdadi*
