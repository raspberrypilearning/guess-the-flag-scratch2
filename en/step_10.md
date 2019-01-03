## Start a new round

At the moment there is only one round in the quiz, so the quiz doesn't last long. You are going to set up multiple rounds.

--- task ---
Create a new `broadcast`{:class="blockevents"} that sends the message 'Start the round'.

![Flag sprite](images/flag-sprite.png)

![blocks_1546524225_7197363](images/blocks_1546524225_7197363.png)

--- /task ---

--- task ---
Add a `when I receive 'Start the round'`{:class="blockevents"} block, and then move all of the code from below the `when green flag clicked`{:class="blockevents"} block to below this new block.

![Flag sprite](images/flag-sprite.png)


![blocks_1546524228_3548393](images/blocks_1546524228_3548393.png)

--- /task ---

--- task ---
Remove the `set score to 0`{:class="blockdata"} block and place it back below the `when green flag clicked`{:class="blockcontrol"} block. Then add the new `broadcast`{:class="blockevents"} block below both of them.

![Flag sprite](images/flag-sprite.png)

![blocks_1546524230_0148969](images/blocks_1546524230_0148969.png)
--- /task ---

--- task ---
After the code that checks whether the answer is correct, add another `when I receive 'Start the round'`{:class="blockevents"} block so that a new round starts after an answer has been given.

![Flag sprite](images/flag-sprite.png)

![blocks_1546524231_5934067](images/blocks_1546524231_5934067.png)

--- /task ---

--- task ---
Click the green flag to test your code. Click on one of the flags to play a round. Do you notice that the next round does not get set up properly?

![Next round does not work](images/next-round-does-not-work.png)
--- /task ---

This is because before the game starts another round, the game needs to first clear up the cloned flags.

--- task ---
Create another new `broadcast`{:class="blockevents"} called 'clean up'.

![Flag sprite](images/flag-sprite.png)

![blocks_1546524233_2246745](images/blocks_1546524233_2246745.png)
--- /task ---

--- task ---
Set the Flag sprite to `delete this clone`{:class="blockcontrol"} when it receives the `clean up`{:class="blockevents"} broadcast.

![Flag sprite](images/flag-sprite.png)

![blocks_1546524234_819807](images/blocks_1546524234_819807.png)
--- /task ---

--- task ---
Place the `clean up`{:class="blockevents"} broadcast block just above where the game starts a new round after an answer has been given.

![blocks_1546524236_4284346](images/blocks_1546524236_4284346.png)
--- /task ---

--- task ---
Test your code again and check that you can play multiple rounds, and that your score increases as you get answers correct.
--- /task ---

--- task ---
Make sure you right-click on and hide the `correct answer`{:class="blockdata"} variable so the player can't see it!
--- /task ---
