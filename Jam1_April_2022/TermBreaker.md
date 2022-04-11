# TermBreaker

[TermBreaker]: https://github.com/ArthurSonzogni/termBreaker

[TermBreaker] is an inverted break-out game. You have to throw a set of balls from the top. Goal is to erase all the bricks before getting submerged.



Project repo: https://github.com/ArthurSonzogni/termBreaker

Submission release: https://github.com/ebarlas/minesweeper_ftxui/releases/tag/v0.0.2


https://user-images.githubusercontent.com/4759106/162654777-de337c90-8d31-4a03-a5d9-a13fc606fb5e.mp4


# Team

* Arthur Sonzogni (@ArthurSonzogni)

# Interpretation of Theme

When the theme is "round", you have to make balls. Many! Ideally the goal of the game is buy more and more of them.

# Code Quality

- There are several simple tests. Please note that the component can be tested in isolations.
- I didn't have time for adding fuzzers.
- I tried using IWYU, like I did in many project, but I have errors and abandonned.
- The CI on MSVC on Window with DEVELOPER_MODE was failing. I don't own a Windows desktop, and there was no clear error. I had to remove them from the CQ.

# Online Play

This compile toward WebAssembly. It even works with Audio.
https://arthursonzogni.com/TermBreaker/

# Gameplay

#### Goal
Achieve the last level.
Use your mouse to throw a set of balls toward bricks. You have to do it before one of them touch the top of the screen.
Completing levels gives you coins. Use coins to get more balls.


#### Controls:

Mouse mainly. You can also use the keyboard in menu.
