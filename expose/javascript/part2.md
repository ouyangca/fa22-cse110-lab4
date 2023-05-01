## 1
At line 12, the console will print out 3, because var i contains the value of 3 after it exits the for loop, since price.length = 3. i is declared with the tag var so the scope of i will be global.

## 2

At line 13, the console will print out 150, because it is the calculated discountedPrice for the last element of the list Prices since it keeps the value at the last iteration after it exits the loop. The price is originally 300, and 150 after the discount. discountedPrice is declared with the tag var so the scope of it will be global.

## 3
At line 13, the console will print out 150, because it is the calculated finalPrice for the last element of the list Prices since it keeps the value at the last iteration after it exits the loop. The price is originally 300, and 150 after the calculation. finalPrice is declared with the tag var so the scope of it will be global.

## 4
The function wll return a list [50,100,150], which is an array containing 3 elements. The array will be the discounted prices of the prices array that was passed in as the parameter, discounted with the discount rate parameter.

## 5
The code causes an error because since i is declared with let, i has a block scope in the for loop. Thus it is out of scope at line 12.

## 6
The code causes an error because since discountedPrice is declared with let, discountedPrice has a block scope in the for loop. Thus it is out of scope at line 13.


## 7 
finalPrice has block scope within function discountPrice, thus after exit for loop, it still contains the value of 150, which is the last element's discounted price.

## 8
[ 50, 100, 150 ], which is the array of discounted price, every iteration adds one element to the array discounted.  discounted array has a block scope within function discountPrice.

## 9 
The code causes an error because since i is declared with let, i has a block scope in the for loop. Thus it is out of scope at line 11.

## 10
12 will print in terminal 3, which is he size of the array prices.

## 11
Will return[ 50, 100, 150 ], which is the array of discounted price. even though discounted is a const variable meaning that it cannot be re-assigned a value, discounted.push is modifying the element within the same array, not reassigning the variable to another value.


# 12
## A
student.name

## B
student['Grad Year']

## C
student.greeting()

## D
student: student['Favorite Teacher'].name
## E
student.courseLoad[0]

# 13

## A
'32' because 2 is mapped to the string '2'

## B
1 beacuse '3' is converted to int 3

## C
3 because null is converted to 0

## D
3null because null is converted to string 
## E
4 because ture is mapped to 1

## F
0 because both false and null is converted to 0

## G
'3undefined' because undefined is converted to string

## H
'NaN' because undefined is converted to 'Nan' when used in arithmetic operations.

# 14
## A
true because string 2 convert to int 2

## B
false because comparing 2 strings, js compares based on unicode values. thus 2 is compared with 1 first, which returns false.

## C
true because string is converted to int 2

## D
false because  === operator performs a strict comparison without type coercion


## E
false, because true is converted to 1.

# 15
==  is arithmetic comparison with type convertion while === is a strict comparison without type coercion

# 16
in .js file

# 17 
[2] will be returned because when modifyArray is called, it will first create an empty array named newArr. Then, it enters the for loop and pushes the first element of the passed-in array parameter to the newArr, which is 1, and since return in right after the push statement, an array with one single element [1] is returned. and doSomething function doubles the value of the element, thus returning [2].

# 19

1  
4  
3  
2  

will be the output. 