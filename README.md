# Machine-Learning
A simple project to help myself understand how machine learning works.

This program creates dots and gives them a randomly generated array in which they use to determine which way to go and how often. When they run into a wall or obstacle they die. If they make it to the destination they kill all the other dots. If none of the dots make it to the destination, but all die, the "champion" lives on. A genetic algorithm then randomly clones a dot, higher chance based on fitness, and modifies a certain percentage of the array they have by changing that many chosen numbers with new random numbers and repeats the process until a dot makes it to the goal. If a dot makes it to the goal, the process also resets in the same way as before until a new dot can beat the current champion with the "fewest moves" in which case they become the new champion.

Feel free to use this code in any way you like, including but not limitted to modifying or cloning for personal use.
