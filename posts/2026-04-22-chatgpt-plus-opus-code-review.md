# ChatGPT is not useless, it is a strong code reviewer

A lot of people treat model comparison like a winner-takes-all game.

They see Opus write stronger code and jump to the conclusion that ChatGPT is no longer useful. I do not think that is true.

Opus is often very good at writing code, but it still produces bugs. Sometimes obvious ones, sometimes subtle ones. That is exactly where ChatGPT becomes valuable.

What ChatGPT is good at in this workflow is not necessarily replacing the main coding model. It is acting like a second pair of eyes.

You can hand the result to ChatGPT and let it go into review mode:
- pull the logic apart
- nitpick the weak spots
- reconstruct the bug pattern from scattered clues
- turn messy failure symptoms into a concrete bug list

It is a bit like solving a jigsaw puzzle from pieces. One model writes. The other inspects, challenges, and pressure-tests.

Once the bug list is clear and well argued, the main coding model can stop guessing and start fixing things one by one.

That combination works surprisingly well:
- Opus for primary implementation
- ChatGPT for code review and bug finding

Used this way, the pair can produce scripts and programs with fewer bugs than either workflow alone.

The mistake is thinking every model needs to be the best at the same thing.

Sometimes the highest-leverage setup is not one model replacing another. It is one model writing, and another model exposing what the first one missed.
