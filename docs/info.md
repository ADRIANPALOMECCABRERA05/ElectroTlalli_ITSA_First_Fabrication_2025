<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Simon says is a simple electronic memory game: the user has to repeat a growing sequence of colors. The sequence is displayed by lighting up the LEDs. Each color also has a corresponding tone.

In each turn, the game will play the sequence, and then wait for the user to repeat the sequence by pressing the buttons according to the color sequence. If the user repeated the sequence correctly, the game will play a "leveling-up" sound, add a new color at the end of the sequence, and move to the next turn.

The game continues until the user has made a mistake. Then a game over sound is played, and the game restarts.

## How to test
You need four buttons, four LEDs, resistors, and optionally a speaker/buzzer. Ideally, you want to use 4 different colors for the buttons/LEDs (red, green, blue, yellow).

1. Connect the buttons to pins btn1, btn2, btn3, and btn4, and also connect each button to a pull down resistor.
2. Connect the LEDs to pins led1, led2, led3, and led4, matching the colors of the buttons (so led1 and btn1 have the same color, etc.)
3. Connect the speaker to the speaker pin.
4. Select the clock frequency (using the clk3 and clk1 inputs).
5. Reset the game, and then press any button to start it. Enjoy!


## External hardware

Four push buttons (with pull-down resistors), four LEDs, and optionally a speaker/buzzer

