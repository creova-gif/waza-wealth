# Waza Wealth

**An investing and financial-literacy app for first-time investors — an AI wealth copilot, cross-market portfolio tracking, and habit-building tools to make investing approachable.**

![Status](https://img.shields.io/badge/status-active_development-yellow)
![License](https://img.shields.io/badge/license-proprietary-red)
![Stack](https://img.shields.io/badge/stack-React_%2F_Vite_%2F_Supabase-blue)

![Waza Wealth landing page](docs/screenshots/dashboard.png)

## Overview
Waza ("waza" — Swahili for idea/think) makes investing approachable for first-time investors.

## Problem
Investing apps are either intimidating for beginners or gamified in ways that encourage bad habits — few combine real education, habit-building, and approachable design.

## Solution
An AI tutor/wealth copilot, cross-market portfolio views, a trading screen, and gamified habit-building elements (daily rituals, badges, activity rings), with Supabase integration in place.

## Key Capabilities
- AI wealth copilot / tutor
- Cross-market portfolio tracking, trading screen
- Gamified habits: daily rituals, badges, activity rings

## Architecture
React/Vite, Supabase. The codebase currently contains several parallel dashboard design explorations ("Calm," "Apple-style," "Wealthsimple-style" variants) rather than one finalized UI — a design direction needs to be picked before this is demo-ready. No live market/brokerage data integration has been verified yet.

## Repository Structure
- `src/app/components/` — dashboard variants, AI tutor/copilot, portfolio and trading screens
- `src/utils/supabase/` — Supabase client setup

## Getting Started
```bash
npm i
npm run dev
```

## Project Status
Active development, pre-demo-ready — dashboard direction not yet consolidated.

## Roadmap
- [ ] Consolidate to a single dashboard direction
- [ ] Verify/replace any mocked market data with a real feed
- [ ] Regulatory review before any real trading-adjacent features ship

## Contributing
See the [org-wide CONTRIBUTING.md](https://github.com/creova-gif/.github/blob/main/CONTRIBUTING.md).

## License
Proprietary — © CREOVA. All rights reserved.

## Author / Organization
Built by [Justin Mafie](https://github.com/creova-gif) under CREOVA.
