# Simple-5bit-DNN-example

Given is an array of 5 bits, this is our input.
The output is [0,1] or [1,0] depending on: the 1st and last bit both being ON or not.

> [0, 1, 1, 1, 1], [0,1] <br>
> [1, 1, 1, 1, 0], [0,1] <br>
> [1, 1, 1, 0, 0], [0,1] <br>
> [1, 1, 0, 0, 0], [0,1] <br>
> [1, 0, 0, 0, 1], [1,0] <br>
> [1, 1, 0, 0, 1], [1,0] <br>
> [1, 1, 1, 0, 1], [1,0] <br>
> [1, 0, 0, 1, 1], [1,0] <br>

The entire dataset and its output makes intuitive sense, you (or any reasonably sentient person) could find the pattern instinctively just by looking at the data.
The DNN is now trained with this example data.
