# Kite Duel — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io, 172 chars)

Two kites. Two lines. One sky. Steer through the wind window, seize the
upwind edge, and whip your line across the rival's until it snaps. Best of 3
against three AI tiers.

## Details

- Genre: Duel / Arcade / Sports (original kite-fighting)
- Controls: Desktop — ↑/↓ reel line in/out, ←/→ drift, Z yank, X slack,
  M mute. Mobile — floating joystick (reel + drift) and YANK / SLACK buttons.
- Features: Figure-8 kite aerobatics, line durability (5 hits to snap),
  upwind advantage (slashing with the wind needs far less speed), gusts that
  swing every 6–10 s, stamina-based skills (Yank dash / Slack dodge),
  best-of-3 with an arena that shrinks 10% each round, storm shrink after 55 s,
  snap slow-motion with debris, win/loss record saved locally.
- AI: Easy rusher / Normal orbiter / Hard upwind-seizer, validated by
  100-match headless self-play (upwind side wins 66%, balanced controls).
- Tech: Vanilla JavaScript, Canvas, WebAudio (fully synthesized sound, zero
  assets), single self-contained index.html, no analytics, no external links.

## Tags

duel, kite, arcade, versus, physics, wind, original, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime wired
- [x] Responsive (canvas scales to any screen, portrait & desktop friendly)
- [x] Mobile touch controls + desktop keyboard
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## GameDistribution
- Upload kite-duel-gd.zip (contains only index.html)

## itch.io
- Upload kite-duel-itch.zip, mark "This file is playable in the browser",
  entry file: index.html, kind: html
- Suggested viewport: 860×1200 (portrait), fullscreen allowed
- Pricing: $0 (donations optional)
