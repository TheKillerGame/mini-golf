# Mini Golf

A pull-back-and-putt phone game. Drag anywhere on the screen to pull back,
let go to putt. 24 holes in 4 worlds, with par and stars on every hole.

By **RisingForce**.

## Play

Open `index.html` in any browser, on a phone or a computer. It's a single file
with no install, no server and no internet needed (the fonts are embedded and
the sounds are made in code). Pull back with a finger or the mouse; the
further you pull, the harder the putt.

## Features

- 4 worlds of 6 holes; hole 6 of each is a boss hole and finishing it opens
  the next world:
  - **meadow**: walls, sand and bumpers
  - **beach**: water and slopes
  - **valley**: windmills and moving blocks
  - **space**: ice and black holes
- Stars: par or better gets 3, one over gets 2, anything else gets 1; 10
  strokes is the limit
- Water and black holes cost a penalty stroke and put you back where you
  played from
- Every hole was played by a solver to make sure it can be done, and par
  comes from a simulated player who aims well but misses a little
- 5 balls, each with its own look and power, won by beating boss holes:
  - **classic**: no tricks
  - **heavy** (meadow boss): sand and slopes barely slow it down
  - **float** (beach boss): water costs no penalty stroke
  - **scope** (valley boss): the aim line shows the path to the first bounce
  - **golden** (space boss): double coins
- Coins for finishing holes and for new stars, plus 14 missions
- Store: undo and aim+ tools, and ball trails
- Credits with YouTube and Discord
- Saved: best strokes per hole, stars, stats, coins, missions, ball, store items, mute
