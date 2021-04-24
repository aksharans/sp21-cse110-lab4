# Part 3 Answers


1. The bug is that the values that are being inputted into the form are being read in as strings, so when num1 and num2 are being passed into calculateSum, they are string values. Then, when results adds them, they are being concatenated instead of being converted to numbers and added. Therefore, the end result is 2 strings concatenated instead of 2 numbers added.

2. I would fix this by casting the variables num1 and num2 to be a Number. [Screenshot of Fix](./fix.png)