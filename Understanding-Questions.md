# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* This calls the onClick handle
* this invokes the "dispatch" of our addOne() action
* dispatch takes our current state, applies the action
* dispatch now sets our state equal to our previous state plus our action
* rerenders our function
* TotalDisplay shows the total plus 1.
