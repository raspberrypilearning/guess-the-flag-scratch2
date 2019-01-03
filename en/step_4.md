## Choose random flags

For each round of the quiz, choose six random flags from the `flags`{:class="blockdata"} list to be the options.

--- task ---
Create another list called `chosen flags`{:class="blockdata"}. This list will store the six random flags.
--- /task ---

--- task ---
Create a variable called `flag number`{:class="blockdata"}.
--- /task ---

--- task ---
Create a custom block and call it `choose random flag`{:class="blockmoreblocks"}.

![Flag sprite](images/flag-sprite.png)

![blocks_1546524244_5662656](images/blocks_1546524244_5662656.png)

--- /task ---

--- task ---
Add code to the custom block to set the `flag number`{:class="blockdata"} variable to a random number between `1` and the number of items in the `flags`{:class="blockdata"} list.

![Flag sprite](images/flag-sprite.png)

There is a special block in the Data tab for finding the number of items in a list.

--- hints ---
--- hint ---
Set the `flag number`{:class="blockdata"} variable to a `random number`{:class="blockoperators"} between `1` and the `length of the 'flags' list`{:class="blockdata"}.
--- /hint ---

--- hint ---
Here are the code blocks you need:

![blocks_1546524246_2128706](images/blocks_1546524246_2128706.png)
--- /hint ---

--- hint ---
This is what your code should look like:

![blocks_1546524247_8574247](images/blocks_1546524247_8574247.png)
--- /hint ---

--- /hints ---
--- /task ---

This block selects an item from a list by number:

![blocks_1546524249_4272087](images/blocks_1546524249_4272087.png)

--- task ---
Combine this block with the `flag number`{:class="blockdata"} variable to get the text of the randomly chosen item from the `flags`{:class="blockdata"} list. Then insert the item text into the `chosen flags`{:class="blockdata"} list. Add this code to your custom block:

![Flag sprite](images/flag-sprite.png)

![blocks_1546524250_98575](images/blocks_1546524250_98575.png)

--- /task ---

--- task ---
Add the custom `choose random flag`{:class="blockmoreblocks"} block to the code that runs after the green flag is clicked.

![Flag sprite](images/flag-sprite.png)

![blocks_1546524252_6100502](images/blocks_1546524252_6100502.png)
--- /task ---

--- task ---

Test that your code works by clicking the green flag several times and checking that different countries are added to the `chosen flags`{:class="blockdata"} list every time. (If you have hidden the list, tick the box next to the list name to make the list visible.)

--- /task ---

Can you see that, if you click the green flag lots of times, your `chosen flags`{:class="blockdata"} list quickly fills up with more than six items?

--- task ---
Add blocks to delete all the items from the `chosen flags`{:class="blockdata"} list before choosing six flags for the quiz.

![Flag sprite](images/flag-sprite.png)

![blocks_1546524254_2333438](images/blocks_1546524254_2333438.png)
--- /task ---


--- task ---
Test your code again by clicking the green flag several times and checking that the `chosen flags` list is filled with six countries each time.
--- /task ---

You might notice that sometimes the same country gets added to the list more than once.

![Duplicate countries](images/duplicate-countries.png)

--- task ---
Change your `choose random flag`{:class="blockmoreblocks"} block so that the same country never gets added twice to the `chosen flags`{:class="blockdata"} list.

Add a block to the end of your custom block code to delete the `flag number`{:class="blockdata"} from the `flags`{:class="blockdata"} list after it has been added to the `chosen flags`{:class="blockdata"} list.

![Flag sprite](images/flag-sprite.png)

![blocks_1546524255_841607](images/blocks_1546524255_841607.png)
--- /task ---

If you want to, you can now right-click on the lists and variables and hide them, so that they don't take up space on the Stage. If you want to show them again, go to the Data section and select the boxes next to the list names or variable names.
