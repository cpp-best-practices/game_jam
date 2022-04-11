# 2022 Game Jam submission: Grand Rounds

A nonogram tour of the [Grand Rounds Scenic Byway](https://en.wikipedia.org/wiki/Grand_Rounds_National_Scenic_Byway) in Minneapolis, MN

link to project: https://github.com/dholmes215/grandrounds/releases/tag/v0.1

# Team

 * David Holmes (dholmes@dholmes.us)

# Interpretation of Theme

The linked Wikipedia page "Round" for inspiration included mention of the Grand Rounds, which I was very familiar with, having lived in Minneapolis my whole life and having biked the Grand Rounds trails hundreds of times.  I sought a way to take pictures of landmarks around the Grand Rounds and incorporate them into a game that could be made quickly with the FTXUI library and with my current skills, and nonogram puzzles seemed like a viable vehicle for that, though I ended up biting off more than I could chew.

# Other Things You Want To Share

I have only tested on Windows, building with MSVC, running in Windows Terminal.  Furthermore the Debug builds are extremely slow, so I recommend Release builds if you actually want to play the game.  I hope it works in other environments but sadly I'm out of time to test them.  It is not playable at all in terminals that do not support a mouse.

Unfortunately, due largely to poor planning on my part and somewhat unrealistic goals, I didn't actually finish the game to nearly the extent I would have liked.  I hoped to have a dozen or so puzzles, all with photographs of locations around the city.  It turns out that 1) designing _good_ nonograms is actually kind of hard, and 2) many great photographs do not make good nonograms at all.  Since this was supposed to be a _C++ Best Practices_ game jam, I decided not to spend all my limited time designing puzzles and was more than busy just trying to make the game anyways.  So I only ended up with two nonograms, only one of which is actually good.

There are no unit tests, and I disabled the sample tests because I was getting weird build errors I had no time to look into.  The CodeQL action on GitHub hasn't passed since the first couple days.  It started failing due to CMake/Conan issues that were also causing the regular CI builds to fail, and once I fixed those it was failing due to timeouts after six hours.  I haven't looked into why.

The code itself is also sort of a mess.  I basically just got it working and now it's time for it to be done so I'm calling it done.  I'll hopefully clean it up a bit over the next couple days.

In retrospect I should have spent more time figuring out my environment and the FTXUI library _before_ the game jam started, instead of spending the first weekend on that stuff.

In spite of all that, it was very educational.  I can see myself using FTXUI for other projects in the future, and I think I'll be better equipped for future game jams, with better planning and time management.
