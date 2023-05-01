1. the bug was that when adding val1 and val2, they were converted to strings and thus are being concatenated instead of added as numbers. Thus the result was a string. 

2. I use the function parseInt() to convert num1 and num2 to integer numbers.