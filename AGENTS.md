# Agent instructions — Cardell IT Support site

This file is for coding agents (Claude Code, Cursor, Codex) working in this repo. It is not site copy.

## What this is

Public website for **Cardell IT Support** — friendly local house-call tech help for homes and small businesses around Tacoma / Puyallup, Washington. Visits by appointment; do not advertise availability as limited to evenings after 6 PM or weekends. Computer help, TV/display wall mounting, and security-camera installation and setup. No MSP. No electrical work or 24/7/on-call support.

Legal entity (when filed): trade name under Cardell Works LLC. Sister brand: Cardell Exhibit Service (separate site: https://cardellexhibits.com/). Do not mix exhibit copy into this site.

Repo: https://github.com/cardellexhibits/cardellitsupport
Intended live domain: https://cardellitsupport.com/ (register separately; CNAME when DNS is ready)

## How to change the live site

Static files only. Push or merge to `main` and GitHub Pages deploys. No bundler, SSG, npm, or theme unless Nick or Sign explicitly lifts that.

Public page starts as `index.html`. Keep it small.

## Locks (do not violate)

- Friendly local repair-guy tone. Plain English. No MSP jargon.
- Services that may be listed (prices OK on this site — unlike CES):
  - Slow PC / virus / bloat cleanup — $99
  - Wifi / router swap (customer buys router) — $89–$99
  - New laptop setup + file move — $149
  - Printer won\'t print — $99
  - Hourly after flats: $99 first hour, then $89/hr
  - TV/display wall mounting — ask for a quote; no fixed price supplied
  - Security-camera installation and setup — ask for a quote; no fixed price supplied
- Phone: 253-319-3049 (Quo). Email: `cardellitsupport@gmail.com` (locked 11 Sep 2026). Do not put nacardell@gmail.com or nick@cardellexhibits.com on this site.
- Never mention AI, models, Qwen, Grok, Codex in public copy.
- No PetroCard, no exhibit/CES services, no client names from CES work.
- TV/display wall mounting and security-camera installs are offered (scope updated by Nick on 17 Sep 2026).
- No electrical work, low-voltage wall runs, or 24/7/on-call support as offered services.
- Do not add analytics, chat widgets, paid backends, or third-party font/CDNs unless asked.
- Do not charge cards or buy hosting add-ons from agent work. Domain/DNS is Sign + Nick.

## Files

- `index.html` — public page (scaffold until Claude Code builds)
- `AGENTS.md` — this file (also the Claude Code brief)
- `README.md` — deploy notes
- `CNAME` — cardellitsupport.com (only after domain is registered; do not break Pages)
- `robots.txt`, `sitemap.xml`, `404.html`, `favicon.svg`

## PRs

Prefer a branch and PR against `main`. Keep diffs small. Build the real marketing page in Claude Code from this foundation; do not paste CES exhibit copy.


## Public contact (locked)
- Phone: Quo 253-319-3049
- Email: cardellitsupport@gmail.com
- Not nick@cardellexhibits.com, not nacardell@gmail.com.
