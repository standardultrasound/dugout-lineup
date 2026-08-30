# Dugout Lineup

A youth-baseball lineup and game-day tool. Build a batting order, plan defense inning by
inning, check the plan against fairness and workload rules, and run the game from the dugout.

**Live: https://standardultrasound.github.io/dugout-lineup/**

`index.html` is the entire application — one self-contained file, no build step, no server,
no dependencies. It also runs offline if you save it and open it directly.

## What it does

- **Batting order** — drag to reorder, lock spots, generate Development / Balanced /
  Competitive orders and compare them side by side.
- **Defense** — drag players between positions and the bench, one inning at a time, or edit
  every inning at once in a grid. Lock a player to a position so auto-fill leaves them alone.
- **Auto-fill** — fills open positions using coach ratings and position experience, spreading
  rest and avoiding repeat assignments.
- **Review** — flags rule conflicts (two players at one spot, an unavailable player assigned,
  a throwing restriction violated) separately from fairness notes (back-to-back rests, heavy
  catching load, nobody getting an infield inning).
- **Game Day** — current pitcher and catcher, tap-two-players swaps, a catcher's-gear
  reminder for the next inning, and injury/absence handling that repairs the rest of the plan.
- **Rankings** — sort the roster across batting, pitching, fielding, this-game playing time
  and coach ratings, with eligibility and minimum-sample filters.

## Your data

Everything you change is stored in your own browser and never leaves your device — no
account, no server, nothing uploaded. Each device keeps its own copy. **Team → Download
backup** and **Restore from a backup file** move a season between them.

Import a roster from a two-row-header CSV (the shape GameChanger exports) under
**Team → Import season stats**.
