# Kite Duel — Aerial Line-Cutting Duel

A free, original, single-file HTML5 duel game. Two kites, two lines, one sky:
steer your kite through the wind window, seize the upwind edge, and slash your
taut line across the rival's until it snaps. No dependencies, no build step,
no tracking — one `index.html`.

**Play:** https://shuangyueliao.github.io/kite-duel/

## How to play

- Your kite always carves its own figure-8 in the wind — you control the
  relative position: reel the line in (`↑`/`W`) or let it out (`↓`/`S`), and
  drift across the wind window (`←`/`→` or `A`/`D`).
- **Z** = Yank (0.5 s power reel-in, instant direction change) · **X** = Slack
  (let the line bow out for a big evasive sway). Both cost 1 of 3 stamina,
  which regenerates over time.
- Sweep your kite fast across the rival's line to fray it (relative speed must
  beat the threshold — slashing with the wind, from the upwind side, needs far
  less speed). Each line takes 5 hits; the 5th snaps it and the round.
- Gusts swing the wind every 6–10 s (watch the vane). The upwind kite glows —
  steal that edge, then ride the gust down through the rival's line.
- Best of 3 wins the match; the arena shrinks 10% each round and a storm
  shrinks it further if a fight drags past 55 s.

## Features

- Original kite-fighting mechanics: figure-8 aerobatics, two-point line chain,
  sweep-cut with continuous-frame (no-tunneling) intersection, upwind advantage
- Three AI tiers (Easy rusher / Normal orbiter / Hard upwind-seizer), tuned via
  headless self-play
- Mobile virtual joystick + YANK/SLACK buttons, desktop keyboard, canvas
  auto-fit, dusk-sky procedural visuals, fully synthesized WebAudio sound
- Local win/loss record, mute toggle, no external assets or links

## For portals

Single self-contained HTML file, ready for CrazyGames / GameDistribution /
itch.io submission (portal SDK loads only on matching domains). See `store/`.
