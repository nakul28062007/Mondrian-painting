# Mondrian composition — CSS Grid practice
 
Pure CSS Grid recreation of a Mondrian-style composition. Practice exercise, not production code.
 
## Files
 
- `index.html` — markup + CSS
- `goal.jpg` — reference image
## How it's built
 
- 15×15 grid, `repeat(15, 40px)` columns and rows, `10px` gap
- Each shape placed with `grid-area: row-start / col-start / row-end / col-end`
## Deliberate tradeoffs (not bugs)
 
- Fixed px sizing — not responsive
- Class names (`no_1`–`no_21`) are placement IDs, not semantic
- `transform: scale(0.9)` used to fit viewport instead of true responsive scaling
## Colors
 
| Shape | Hex |
|---|---|
| Red | `#D7362A` |
| Yellow | `#D8CE60` |
| Off-white | `#D7D4D2` |
| Black | `#000000` |
| Blue | `#2D316E` |
| Orange | `#CC6750` |
 
