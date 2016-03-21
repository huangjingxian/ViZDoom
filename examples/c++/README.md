To run the examples, [freedoom2.wad]( https://freedoom.github.io/download.html) should be placed in the  ``../scenarios`` subdirectory (it should be done automatically by the building process).

---
##Examples

###[Basic.cpp](https://github.com/Marqt/ViZDoom/blob/master/examples/c++/Basic.cpp)
Demonstrates how to use the most basic features of the environment. It configures the engine, and makes the agent perform random actions. It also prints the current state and the reward earned with every action.

###[Spectator.cpp](https://github.com/Marqt/ViZDoom/blob/master/examples/c++/Spectator.cpp)
Shows how to use the *SPECTATOR* mode in which YOU play Doom and AI is the spectator (intended for apprenticeship learning).

###[Shaping.cpp](https://github.com/Marqt/ViZDoom/blob/master/examples/c++/Shaping.cpp)
Demonstrates how to make use of the game variables to implement [shaping](https://en.wikipedia.org/wiki/Shaping_(psychology)) using health_guided.wad scenario.

###[Seed.cpp](https://github.com/Marqt/ViZDoom/blob/master/examples/c++/Seed.cpp)
Shows how to run deterministic episodes by setting the seed. After setting the seed every episode will look the same (if the agent behaves deterministically).