## 1 
20 is printed by line 9

## 2  
20 is printed by line 13

## 3  
20 is returned by line 9

## 4
An error is returned by line 13, because unlike var in question 1 that declares a global variable, declaring a variable with the let keyword will give the variable a block scope, meaning that variable result can only be accessed in the if block. line 13 is not within the block, Thus an error is returned.

## 5
The code returns an error, because the variable result is declared with the const keyword, and is assigned a vlue of 0. However, on line 7, it is trying to re-assign the constant variable result, thus causing an error. 

## 6
The code returns an error, because of the re-assignment to constant variable in question 5. However, line 13 also will cause an error because result is out-of-scope, since it is declared with a block scope within the if statement block.




