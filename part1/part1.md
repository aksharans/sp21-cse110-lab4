# Part 1 Answers 

## 1a

1. 20
2. 20
3. 20
4. Reference Error. The code returns an error because variables declared with the let keyword are only visible inside the code block they are declared in. result was declared inside the if block and is illegaly trying to be accessed outside of it. 
5. Type Error. The code returns an error because you are trying to illegally assign to a constant variable, which can not be set to a value after they are declared and initialized.
6. Not executed due to error, but this is a Reference Error. Since there is an error before this line, the program will terminate, but you can't access a constant outside it's scope, similar to let.


## 1b

1. 3, console.log prints 3  because the var keyword has no block scope, so its value can be accessed anywhere. Thus, as var i gets incremented in the for loop, until the final check when it is greater than prices.length at 3. 
2. 150, console.log prints 150  because the var keyword has no block scope, so its value can be accessed anywhere. Thus, as var discountedPrice gets changed in the for loop, until the final iteration when it is calculated to be prices[2] * (1-0.5)=300*0.5=150.
3. 150, console.log prints 150  because the var keyword has no block scope, so its value can be accessed anywhere. Thus, as var finalPrice gets changed in the for loop, until the final iteration when it is calculated to be Math.round(150*100)/100) = 150.
4. [50,100,150], The function will return discounted, which is an array of the finalPrices after discounts, which is half of the values of the original array passed.
5. Reference Error. The code returns an error because variables declared with the let keyword are only visible inside the code block they are declared in. i was declared inside the for loop and is illegaly trying to be accessed outside of it. 
6. Reference Error. The code returns an error because variables declared with the let keyword are only visible inside the code block they are declared in. discountedPrice was declared inside the for loop and is illegaly trying to be accessed outside of it. 
7. 150, console.log prints 150 because finalPrice was declared at the top of the function, so its scope is the entire function and it can be accessed anywhere. As mentioned before, let finalPrice gets changed in the for loop, until the final iteration when it is calculated to be Math.round(150*100)/100) = 150.
8. [50,100,150], The function will return discounted, which is an array of the finalPrices after discounts, which is half of the values of the original array passed.
9. Reference Error. The code returns an error because variables declared with the const keyword are only visible inside the code block they are declared in. i was declared inside the for loop and is illegaly trying to be accessed outside of it. 
10. 3, console.log prints 3 because length was declared at the top of the function, so its scope is the entire function and it can be accessed anywhere. Thus, it prints the array size.
11. [50,100,150], The function will return discounted, but although it is a constant, technically it is never reassigned, you are just modifying its value which seems to be legal with the JS const keyword. So, it returns an array of the discountedPrices after discounts, which is half of the values of the original array passed.

12.   
    A. student[]().name   
    B. student['Grad Year']  
    C. student.greeting()    
    D. student['Favorite Teacher'].name  
    E. student.courseLoad[0] 

13.  
    A. '32', integer 2 maps to its exact string representation '2', and the strings are concatenated since + merges strings if any of the operands is a string.     
    B. 1, string '3' maps to its integer representation 3, and subtraction occurs, since - only works with numbers and converts operands to numbers.    
    C. 3, null becomes the integer 0, and addition occurs.    
    D. 3null, null becomes a string 'null', and the strings are concatenated, since + merges strings if any of the operands is a string.       
    E. 4, true becomes the integer 1, and addition occurs.  
    F. 0, false and null both become the integer 0, and addition occurs.
    G. 3undefined, undefined maps to its string representation 'undefined', and the strings are concatenated.
    H. NaN, undefined is mapped to NaN, and returns NaN, since  - only works with numbers and converts operands to numbers.  

14.  
    A. true, JS converts the value '2' into its number representation for the > operator.   
    B. false, comparing 2 strings compares them lexigraphically and 1 occurs before 2.  
    C. true, JS converts the value '2' into its number representation for the == operator.
    D. false, === checks value and type, and a string '2' is a different type than integer 2.
    E. false, JS convets the value true into a number 1 and string '2' into a number 2, and those aren't equal.
    F. true, === checks value and type, and both are booleans, and also, Boolean of anything other than empty values evaluates to true. 

15. The == equality checks if two values are equal with type conversion, while the === strict eqaulity checks if two values are equal without type conversion. So, == converts values and checks if they are equal (i.e '2' == 2 is true), but if you use the strict equality, it checks if the 2 values are equal and of the same type (i.e. '2 === 2 is false).   



16. [JS 16](./part1b-question16.js)

17. [2, 4, 6], modifyArray is called and is given the array [1,2,3] and the callback function doSomething as parameters. In modifyArray, a const newArr is created and then the for loop iterates through the parameter array. At every iteration, the callback function is called on array[i]. So, array[i] is passed to the callback function, and the function returns that number times 2. Thus, the original arr[i]*2 is the value that is pushed to newArr. newArr iterates through 1,2,3 so mutliplied by two is 2,4,6. At the end, the newArr is returned.   

18. [JS 18](./part1b-question18.js)  

19.     
    1  
    4  
    3  
    2  
