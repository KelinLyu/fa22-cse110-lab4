### 1. What will happen at line 12 and why? If the code causes an error, explain why.

Line 12 will print 3 because there are three elements in prices and the for-loop will increment i 3 times.

### 2. What will happen at line 13 and why? If the code causes an error, explain why.

Line 13 will print 150 because the variable discountedPrice will be modified with input 300 in the final round in the for-loop by calculating 300 * (1 - 0.5) = 150.

### 3. What will happen at line 14 and why? If the code causes an error, explain why.

Line 14 will print 150 because the variable finalPrice will be assigned with 150, the rounded discountedPrice, in the final round in the for-loop.

### 4. What will this function return? Give a brief explanation why. If the code causes an error, explain why.

The function will return an array of the discounted prices of the inputed prices given the inputed discount: for every price in the inputed prices, the new price will be the original price * (1 - discount).

### 5. What will happen at line 12 and why?  If the code causes an error, explain why.

The code returns an error because the i variable is undefined: it is defined inside the for-loop block using the let keyword so it can only be accessed within the block it is defined in.

### 6. What will happen at line 13 and why? If the code causes an error, explain why.

The code returns an error because the discountedPrice variable is undefined: it is defined inside the for-loop block using the let keyword so it can only be accessed within the block it is defined in.

### 7. What will happen at line 14 and why? If the code causes an error, explain why.

Line 14 will print 150 because the variable finalPrice will be assigned with 150, the rounded discountedPrice, in the final round in the for-loop.

### 8. What will this function return? Give a brief explanation. If the code causes an error, explain why.

The function will return an array of the discounted prices of the inputed prices given the inputed discount: for every price in the inputed prices, the new price will be the original price * (1 - discount).

### 9. What will happen at line 11 and why? If the code causes an error, explain why.

The code returns an error because the i variable is undefined: it is defined inside the for-loop block using the let keyword so it can only be accessed within the block it is defined in.

### 10. What will happen at line 12 and why? If the code causes an error, explain why.

Line 12 will print 3 because there are three elements in prices, so the length variable will be assigned with the value 3.

### 11. What will this function return? Give a brief explanation. If the code causes an error, explain why.

The function will return an array of the discounted prices of the inputed prices given the inputed discount: for every price in the inputed prices, the new price will be the original price * (1 - discount).

### 12. Given the above Object, write the notation for:

##### A. Accessing the value of the name property in the student object.

student.name

##### B. Accessing the value of the Grad Year property in the student object.

student['Grad Year']

##### C. Calling the function for the greeting property in the student object.

student.greeting();

##### D. Accessing the name property of the object in the Favorite Teacher property in student.

student['Favorite Teacher'].name

##### E. Access index zero in the array of the courseLoad property of the student object.

student.courseLoad[0]

### 13. Arithmetic

##### A. '3' + 2

The output is '32' because whatever comes after '3' is treated as a character or string.

##### B. '3' - 2

The output is 1 because it does not make sense to subtract a string, so it uses the integer representation.

##### C. 3 + null

The output is 3 because null is 0 using the integer representation.

##### D. '3' + null

The output is 3null because null is treated as string after seeing '3'.

##### E. true + 3

The output is 4 because true has an integer value of 1, and 1 + 3 = 4.

##### F. false + null

The output is 0 because both false and null has an integer value of 0.

##### G. '3' + undefined

The output is 3undefined because undefined is treated as string after seeing '3'.

##### H. '3' - undefined

The output is NaN because it does not make sense to subtract a string with an undefined variable's value.

### 14. Comparison

##### '2' > 1

This is true because we are comparing strings, which compares the char code of '2' and '1', and '2' > '1'.

##### '2' < '12'

This is false because we are comparing strings, which compares the char code of '2' and '1', the first character of '12', and '2' > '1'.

##### 2 == '2'

This is true because we are comparing integers, and 2 equals to itself.

##### 2 === '2'

This is false because without converting the types, an integer does not equal to a string.

##### true == 2

This is false because true has an integer value of 1, and 1 does not equal to 2.

##### true === Boolean(2)

This is true because first, we convert 2 to a Boolean, which gives true. Then, since true is strictly equal to itself, the result is true.

### 15. Explain the difference between the == and === operators.

The == operator can do variable-type-conversion for us, for example, when comparing 2 and '2' using the == operator, it will treat them as variable with the same type. The === operator does not convert the types and only does strict comparison.

### 17. If the function above is called with the following parameters modifyArray([1,2,3], doSomething), what will be the result?

The function will return [2, 4, 6] because the function doSomething will be called for every element in the inputed array [1, 2, 3] and multiply them by 2, which gives [2, 4, 6].

### 19. What is the output of the above code?

1
4
3
2
