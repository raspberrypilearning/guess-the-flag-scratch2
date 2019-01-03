## Check the answer

Your sprite now asks the player to click on the correct flag. Then the game needs to check whether the flag that was clicked is the right answer.

--- task ---
Go back to the Flag sprite code, and add a block to start a new section of code that will run `when this sprite is clicked`{:class="blockevents"}.

![Flag sprite](images/flag-sprite.png)
--- /task ---

Then your quiz needs to check whether the costume name of the Flag sprite that was clicked is the same as the correct answer.

--- task ---
Add code to say 'Correct' if the costume name of the Flag sprite is the same as the `correct answer`{:class="blockdata"} variable, or to say 'Sorry, that was wrong' if the name and the variable are not the same.

You can use this useful block here as well.

![blocks_1546524273_7982447](images/blocks_1546524273_7982447.png)

This time, combine it with a `costume #`{:class="blocklooks"} block to get the name of the current Flag sprite costume.

![Flag sprite](images/flag-sprite.png)

--- hints ---
--- hint ---
`When this sprite is clicked`{:class="blockevents"}, `create the flags list`{:class="blockmoreblocks"}. `If`{:class="blockcontrol"} the `item in the flags list`{:class="blockdata"} with this `costume #`{:class="blocklooks"} equals the `correct answer`{:class="blockdata"}, `say`{:class="blocklooks"} 'Correct', or `else`{:class="blockcontrol"} `say`{:class="blocklooks"} 'Sorry, that was wrong'.
--- /hint ---

--- hint ---
Here are the code blocks you need:

![blocks_1546524275_3481674](images/blocks_1546524275_3481674.png)
--- /hint ---

--- hint ---
This is what your code should look like:

![blocks_1546524276_9661481](images/blocks_1546524276_9661481.png)
--- /hint ---

--- /hints ---
--- /task ---

--- task ---
Press the green flag and test your code twice: once by picking the correct flag, and once by picking an incorrect one. Check that the right message appears depending on whether you give the right or wrong answer.

![Click on the flag](images/click-on-flag.png)
--- /task ---
