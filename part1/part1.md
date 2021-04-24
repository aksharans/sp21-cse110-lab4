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
    A. a
    B. a
    C. a
    D. a
    E. a 
    F. a 
    G. a

14.  
    A. a
    B. a
    C. a
    D. a
    E. a 
    F. a 
    G. a

15. 