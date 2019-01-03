## Show the flags

The person taking the quiz needs to see the pictures of the flags in the `chosen flags`{:class="blockdata"} list.

--- task ---
Create another custom block, and call this one `clone flags`{:class="blockmoreblocks"}.

![Flag sprite](images/flag-sprite.png)

![blocks_1546524259_1352067](images/blocks_1546524259_1352067.png)

--- /task ---

This custom block will clone the Flag sprite six times, once for each flag that should be displayed.

The first flag should be displayed in the top left-hand corner of the Stage.

--- task ---
As part of the instructions for your `clone flags`{:class="blockmoreblocks"} block, make the Flag sprite visible, and add a `go to`{:class="blockmotion"} block to tell the sprite to show at the coordinates `-170`{:class="blockmotion"}, `120`{:class="blockmotion"} in the top left-hand corner of the Stage.

![Flag sprite](images/flag-sprite.png)

![blocks_1546524260_7382407](images/blocks_1546524260_7382407.png)
--- /task ---

--- task ---
Below that code, add a loop that repeats six times.

![Flag sprite](images/flag-sprite.png)

Inside the loop, add code blocks to switch the sprite's costume to the last flag in the `chosen flags`{:class="blockdata"} list, and to clone the sprite. Then, add code blocks to delete the last flag from the list, and to add `110`{:class="blockmotion"} to the `x`{:class="blockmotion"} coordinate to move the sprite to the position of the second flag.

--- hints ---
--- hint ---
`Repeat`{:class="blockcontrol"} six times:
`Switch costume`{:class="blocklooks"} to the `last item in chosen flags`{:class="blockdata"}.
`Clone the sprite`{:class="blockcontrol"}.
`Delete`{:class="blockdata"} the `last item in chosen flags`{:class="blockdata"}.
`Move right 110`{:class="blockmotion"}.
--- /hint ---

--- hint ---
Here are the code blocks you need to add:

![blocks_1546524262_3328414](images/blocks_1546524262_3328414.png)
--- /hint ---

--- hint ---
This is what your code should look like:

![blocks_1546524263_973016](images/blocks_1546524263_973016.png)
--- /hint ---

--- /hints ---
--- /task ---

--- task ---
Add your `clone flags`{:class="blockmoreblocks"} block to the end of the code that runs when the green flag is clicked.

![Flag sprite](images/flag-sprite.png)

![blocks_1546524265_6233544](images/blocks_1546524265_6233544.png)

--- /task ---

--- task ---
Run your code. Notice that the different flags appear, but some are cut off by the edge of the Stage.

![Flags go off the screen](images/flags-off-the-screen.png)

--- /task ---

Instead of putting all six flags in one row, make two rows of three flags.

--- task ---
Add some code inside the `repeat`{:class="blockcontrol"} loop of the `clone flags`{:class="blockmoreblocks"} block to move the Flag sprite down a row if there are three flags left in the `chosen flags`{:class="blockdata"} list.

![Flag sprite](images/flag-sprite.png)

You can the sprite move down a row by using another `go to`{:class="blockmotion"} block and keeping the `x`{:class="blockmotion"} coordinate the same as the starting point, but decreasing the `y`{:class="blockmotion"} coordinate to move downwards.

![blocks_1546524267_281526](images/blocks_1546524267_281526.png)
--- /task ---

--- task ---
Click the green flag and check that the flags display in two rows.
--- /task ---

It looks like the last flag is displayed twice. This is because the original Flag sprite is still visible at the end.

--- task ---
Add a `hide`{:class="blocklooks"} block at the end of the code inside the `clone flags`{:class="blockmoreblocks"} block to hide the original sprite.

![Flag sprite](images/flag-sprite.png)

--- /task ---

If you want to, you can try making the flag sprites appear one by one or playing a sound (a pop, for example) each time a flag appears.
