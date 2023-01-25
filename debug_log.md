# Debug Log

**Explain how you used the VSCode debugger tools to uncover the bugs in Exercise 7. Be specific. What breakpoints did you set? Where did you step to? What made you realize the error?**

_Example: I set a breakpoint on line 5 and stepped until line 12. There, I discovered that the `x` variable had a value of `-3`, whereas it should have had a value of `7`. That made me realize that we should be adding the two numbers `x` and `y`, instead of subtracting._


I set a breakpoint on line 9 and stopped on line 13. I traced forward and discovered on line 10 that the remainder_of_sentence was using the length of the 'start_str' instead of 'sentence'. I fixed it by replacing the variable names.

Then, in the else block on line 13, it is returning sentence[0] instead of sentence[1:] and I realized that it doesn't consider all the characters after the first one. I fixed it by replacing start_str with 'sentence'.
