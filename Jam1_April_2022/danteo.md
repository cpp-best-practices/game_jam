# 2022 Game Jam submission: DanteO

DanteO is proud to present its newest product: DantIO!

DantIO is here to help developers connect around buggy code through increasing our collective WTF/minute KPIs.
Don't wait, come join us in the brand new 10th Circle of Hell!

_DantIO, together, for a buggier tomorrow._

![image](https://user-images.githubusercontent.com/90116665/162724641-d7b62010-a1ba-4e32-aefa-6df4fabe7368.png)
![image](https://user-images.githubusercontent.com/90116665/162724415-fbda8453-74c7-4daa-8964-59e1f9a7c832.png)

link to project: https://github.com/rduckengineer/danteo/releases/tag/v1.0.0

# Team

 * RubberDuckEngineer
 * TrungDinhT
 * CardellaT

# Code quality

Not everything is as tested as I wish it would be, but the core components (mostly) are, and the ones that aren't have been made so that testing them would be not too difficult. But time constraints + deciding to do a narrative game that requires manually-crafted content... 🙃

Some architectural clean ups are still needed (`user_interface` is pretty bare, given its current content it probably should be in `engine`, and `gameplay` has a little bit too much content. I'll try to make it make more sense later)

But still, in theory, you should be able to create any page-based game with the stuff in `engine` + `user_interface`.

In theory, the whole game walkthrough can be tested without any UI to check there was no regression, but then again, time constraints.

There are a few builders here and there to make content easier to pump out.
I'd like to make a lot more of it `constexpr` in the future, but for the sake of finishing I'm still using `std::vector` or `std::map` for a few things right now.

# Interpretation of Theme

Welcome to the 10th Circle of Hell, the new tech hub of the underworld!
You'll find that sometimes, good things don't have to end as we go round and round and round...

# Other Things You Want To Share

Writing and displaying bad code in the console is a lot more time-consuming than it seems.
Maybe V2.0 will give us some truly bone-chilling nested for-loops and subtle exception-safety issues 😉
