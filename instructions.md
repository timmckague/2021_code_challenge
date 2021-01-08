# Floor Walker

The goal of this challenge is to navigate your way across a floor, finding the shortest path.

The floor is made up of either tiles or walls. You can walk on tiles and you can't walk through walls. You can only walk directly left, right, up or down. You can't walk diagonally.

You need to write a program that can accept a "floor" and return the shortest path from the top left corner of floor to the bottom right. The floors will have a length and height of anywhere between 2 and 20.

for example, you might be given this 4x4 floor...

```
floor1 = [
  [0, 1, 1, 0],
  [0, 0, 0, 1],
  [1, 1, 0, 0],
  [1, 1, 1, 0]
]
```

Your program will calculate the shortest path by the number of floor tiles it visits to reach the end destination including the starting and end tile.

the shortest path for `floor1` involves walking on 7 tiles.

There is one additional twist to this problem... You are allowed to switch any one wall to a tile in order to find the shortest path.

Complete the file `solution.py`. There are some test cases your code should be able to handle in the file `tests.py`. Your program will also be tested against a few "hidden" tests...

## Constraints

Your code cannot use multi-threading...

# all zeros
# multiple paths

