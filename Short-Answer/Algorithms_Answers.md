#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)


b) O(n^2)


c) O(n)

## Exercise II

Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

Not 100% sure I understand the question, but I will try:

Loop, using an index, through each floor of the building and drop an egg off.
If the egg breaks, break out of the loop and save index - 1 as f - 1 where eggs can fall off without breaking.

Runtime complexity would be O(n) since we just loop through the floors one time

Alternatively, assuming f is always > 0 throw all eggs off of floor(0) so that no eggs ever break. Time complexity would be O(1)