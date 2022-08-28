# Bowling Rules

The game consists of 10 frames. In each frame the player has two rolls to knock down 10 pins.
The score for the frame is the total number of pins knocked down, plus bonuses for _strikes_ and _spares_.

A _spare_ is when the player knocks down all **10 pins** in two rolls.
The bonus for that frame is the number of pins knocked down by the _next roll_.

A _strike_ is when the player knocks down all **10 pins** on his first roll.
The frame is complete with a single roll. The bonus for that frame is the value of the _next two rolls_.

In the tenth frame a player who rolls a spare or strike can roll the extra balls to complete the frame.
However, no more than three balls can be rolled in the _10th frame_.

# Requirements
Write a class `Game` that has two methods

1. `void roll(int)` is called each time the player rolls a ball. The argument is the number of
pins knocked down.
2. `int score()` returns the total score for that game.
