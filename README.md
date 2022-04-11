# 2022 Game Jam submission: TheWorld

First you have to answer three personal questions. Based on that you will get ... ;). To merge the worlds of square and round, you will have to accomplish 8 halls which are guarded by monsters triggered by tension between worlds... 
Will you be able to survive?

link to project: https://github.com/JungerBoyo/TheWorld/releases/tag/game_jam_submission

[![gamejam-scr0.png](https://i.postimg.cc/5NNwqZRg/gamejam-scr0.png)](https://postimg.cc/fkptMgZS)
[![gamejam-scr1.png](https://i.postimg.cc/SQG69yDj/gamejam-scr1.png)](https://postimg.cc/w37R8dKd)

# Team

 * JungerBoyo

# Interpretation of Theme

 * The world represents pair of two opposities one of them is the round and the other the square!

# Other Things I Want To Share

 * explore!

## Code of Conduct

All interactions around the game jam are to be governed by the [Berlin Code of Conduct](https://berlincodeofconduct.org/). If you, your team, or your project are found to be in violation of the code of conduct, then your submission wil be disqualified.

## Funding, Sponsorships and Prizes

There is currently no actual prizes planned, but in case there are prizes awarded, I must note:

 * YouTube [Community Guidelines](https://www.youtube.com/howyoutubeworks/policies/community-guidelines/) apply
 * YouTube is not a sponsor

## Announcements!

 * [Jam 1, April 2022, is announced](Jam1_April_2022)


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
 * be created from the [C++ Best Practices/ftxui_template project](https://github.com/cpp-best-practices/ftxui_template) via "use this template."
 * compile with no warnings or errors on all pre-configured [actions](https://github.com/cpp-best-practices/ftxui_template/actions)
 * have selected a license
 * run with no errors from Address Sanitizer or Undefined Behavior Sanitizer (as configured by default in "developer mode" of the provided template)
 * interpret the theme in some way
 * document any warnings that have been disabled, and why

Submission requirements:
 * submissions will take place via a pull request to this project
 * submissions must link to a specific github release on your project
 * PR (and release) must be dated before the submission deadline

By participating in this Game Jam you agree to release YouTube and Jason Turner from any liability related to your participation.

## Who Can Participate?

Anyone willing to follow the Code of Conduct. Families and teams are encouraged.

## What Libraries Can I Use?

Anything you want to, as long as it does not violate any other rules. Conan package manager is provided with the template, and it uses some packages already. However, all output must still happen through FTXUI.

## Teams

Teams of any size are allowed. Just be aware that coordinating large teams can be difficult. To meet other people to join into a team, join the [Discord](https://discord.gg/KuKzESDdbt)



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

# Configuration Notes

* clion on Windows is currently an untested configuration, and you might have difficulty getting ASAN, cppcheck, and clang-tidy to be found. They can be installed, but it will take manual work to get them located.
* The easiest option for changing settings is to use your cmake-gui of choice. However, if you want to change options during CMake configuration time (commandline or from your IDE's options, you should be able to follow this example from the [CMakePresets.json](https://github.com/cpp-best-practices/cpp_boilerplate_project/blob/main/CMakePresets.json#L35-L38)
