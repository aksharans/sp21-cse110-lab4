# Part 3 Answers


1. The bug is that the values that are being inputted into the form are being read in as strings, so when num1 and num2 are being passed into calculateSum, they are string values. Then, when results adds them, they are being concatenated instead of being converted to numbers and added. Therefore, the end result is 2 strings concatenated instead of 2 numbers added.

2. I would fix this by casting the variables num1 and num2 to be a Number. [Screenshot of Fix](./fix.png)  

3. citylots.json  
4. part2.js  
5. 11.7 MB
6. 4.98 s
   
7. Mozilla/5.0 (Linux; Android 6.0; Nexus 5 Build/MRA58N) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.85 Mobile Safari/537.36  
8. Apache  
9.  Tue, 26 Jan 2021 22:14:13 GMT  
10. application/json  
    
11. onclick 