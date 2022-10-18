# Chest GUI Leaderboard

## Commands

- /leaderboard (/lb)
- /leaderboard [page]

## GUI

Main page:

5 column GUI. Top row is black stained glass panes. Bottom row is black stained glass panes, with red stained glass pane in lower left corner to exit GUI. Center row contains 7 icons for the 7 available leaderboards. Hovering over any of them will state what leaderboard it is and give the player their position on that leaderboard.

Available leaderboards:

- most kills (sword)
- k/d ratio (ender pearl)
- damage dealt (axe)
- damage absorbed (shield)
- drop crates opened (chest)
- power level (emerald)
- votes (diamond)

Leaderboard page:

5 column GUI. Top row is black stained glass panes with top right corner being player's own head they can hover to see their stat. Center 3 slots of top row are the top 3 players' heads for that leaderboard. Bottom row is black stained glass panes with: left corner is red stained glass pane to go back to main page, right corner is block to change filter type, and center 2 spots are arrows to go to next/previous pages.

Available filters:

- All Time
- Monthly
- Weekly

## Metrics

Should be stored in a mysql DB.

- most kills
- k/d ratio
- damage deal
- damage absorbed
- drop crates opened
- power level
- votes
