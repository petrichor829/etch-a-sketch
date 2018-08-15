# etch-a-sketch

An interactive throwback to the classic 2D drawing toy, coded in vanilla JavaScript.

## features

- The user can toggle between three modes: "Draw" pays homage to the aluminum trail of the original; "Shade" etches progressively darker tones on each pass; and "Color" etches each cell with a random color.

- Clicking the "Shake" button prompts the user for the dimensions of a re-rendered grid—and then animates the entire toy to mimic the clearing mechanism of the original.

- Pressing the ESC key suspends etching, allowing the user to reposition the cursor or change mode without leaving a trail off the grid. Pressing ESC again resumes etching. Granted, this is a departure from the lineographic (don't-lift-that-pen!) premise of the toy itself, though I couldn't resist working in a <code>keydown</code> event.

## acknowledgments

I incorporated open-source work from the following devs:

- Daniel Eden, who coded "shake" animation. See the full complement of fun animations at [Animate.css](https://daneden.github.io/animate.css/).

- Ionuț Colceriu, for the pure-CSS toggle switch used for "Mode" selection. See [css-toggle-switch](https://ghinda.net/css-toggle-switch).