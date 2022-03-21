# C++ Best Practices Game Jam

The C++ Best Practices Game Jam is a periodic friendly competition designed to promote the learning of C++ through game creation in an environment that makes it easy to apply Best Practices.

## Code of Conduct

All interactions around the game jam is to be governed by the [Berlin Code of Conduct](https://berlincodeofconduct.org/). If you, your team, or your project are found to be in violation of the code of conduct, then your submission wil be disqualified.

## Basic Timeline

Game Jams will last across two weekends, and the week inbetween. Voting and evaluation of the submissions will take place over one week.

 * Friday @ 12:00 UTC - Game Jam theme is announced, design and development can begin
 * Saturday - Sunday (8 days) - Game development
 * Monday @ 12:00 UTC - Submissions must be completed
 * Tuesday - Thursday @ 12:00 UTC - Community voting allowed
 * Friday - Winners Announced

## Rules

Games must:
 * use [FTXUI](https://github.com/ArthurSonzogni/FTXUI)
 * be created from c via "use this template."
 * compile with no warnings or errors on all pre-configured [actions](https://github.com/cpp-best-practices/ftxui_template/actions)
 * have selected a license
 * run with no errors from Address Sanitizer or Undefined Behavior Sanitizer (as configured by default in "developer mode" of the provided template)
 * interpret the theme in some way
 * document any warnings that have been disabled, and why

Submission requirements:
 * submissions will take place via a pull request to this project
 * submissions must link to a specific github release on your project
 * PR (and release) must be dated before the submission deadline

## Who Can Participate?

Anyone. Families and teams are encouraged.

## How Submissions Are Judged

 * Interpretation of Theme
 * Gameplay
 * Creativity
 * Code Quality / Code Readability
 * Fun
 * Testing of Game Code

# Getting Started

 1. Create a new project by clicking "use this template" from ![image](https://user-images.githubusercontent.com/234279/159132116-5d6564f5-cbc8-4cce-bf26-e97d1e167280.png).
 2. Make sure the project's "actions" are enabled ![image](https://user-images.githubusercontent.com/234279/159133640-cd2466f8-1cba-4490-8dfb-976ec800ac9b.png)
 3. Wait for the "template janitor" action to finish ![image](https://user-images.githubusercontent.com/234279/159133663-e4c4880c-88b7-48f4-9057-a49177a21981.png)
 4. Install local tools
    * compiler of choice
    * clang-tidy and cppcheck (linux, MacOS)
    * conan
 5. Clone your project locally, and open it with your editor of choice

(Videos on this will be forthcoming)

# Some Hints

 * The template provided gives you the foundation for a turn-based game
 * FTXUI has a canvas: https://github.com/ArthurSonzogni/FTXUI/blob/master/examples/dom/canvas.cpp
 * The "homescreen" example shows how to do live animations / event loop https://arthursonzogni.com/FTXUI/examples/?file=component/homescreen
 * It should be possible to create a normal game loop
 * There are Unicode fonts which might prove to be useful: https://unicode-table.com/en/blocks/block-elements/ https://unicode-table.com/en/blocks/symbols-for-legacy-computing/
