# Minesweeper Marathon

Minesweeper Marathon is an adaptation of [Minesweeper](https://en.wikipedia.org/wiki/Microsoft_Minesweeper)
with a timer and rounds of increasing difficulty.

Project repo: https://github.com/ebarlas/minesweeper_ftxui

Submission release: https://github.com/ebarlas/minesweeper_ftxui/releases/tag/v1.0

![Screenshot](https://github.com/ebarlas/minesweeper_ftxui/raw/main/screenshot.png)

# Team

* Elliot Barlas (elliotbarlas@gmail.com | @ElliotBarlas) 

# Interpretation of Theme

Microsoft Entertainment Pack, included with Windows in the 90s, was full of addictive quick-play games
that I adored in my youth.
Chip's Challenge, FreeCell, SkiFree, JezzBall, and others were great, but Minesweeper was my favorite.

The text-grid layout of FTXUI immediately made me think of Minesweeper.

When the theme "round" was revealed, I decided to make an adaptation of Minesweeper that occurs over
many rounds.

# Online Play

When I was reading through the FTXUI docs, I was immediately struck by the [online examples](https://arthursonzogni.com/FTXUI/examples/?file=component/canvas_animated).

Right away, I decided that I wanted Minesweeper Marathon to similarly be available for online play.

Minesweeper Marathon is available in the browser at https://barlasgarden.com/minesweeper/index.html

The CMake, HTML, and JavaScript employed to make that happen are available in the project repo.

The simple high score server written in Python is also in the project repo.

# Gameplay

#### Goal
Achieve the highest round in the time allotted.

#### Rules
The original [Minesweeper](https://en.wikipedia.org/wiki/Microsoft_Minesweeper) gameplay
within a grid of tiles remains unchanged. Reveal all non-mine tiles as quickly
as possible.

However, when a single board is completed, the game continues with a 20-second time bonus and
another board that has an additional mine. This process continues until time expires.

Additionally, an individual board can be reset to restart the current round. Progress is
not lost if a mine is revealed!

#### Controls:

* Left click covered tile to reveal
* Click (left or right) revealed number with correct number of flagged neighbors to clear remaining neighbors
* Right click or key press while hovering covered tile to flag