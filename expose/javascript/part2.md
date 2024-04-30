# Part 2
1. The function will print out the value '3'
2. The function will print out the value '150'
3. The function will print out the value '150'
4. The function will return [50, 100, 150]. This is because the function goes through the input array and applies the 'discount', which is the second input to all the values in the array. Thus since the second input is 0.5, all the values in the array are halved in the final return value.
5. Line 12 will throw an error because the variable 'i' is created with 'let' which means its scope is within a block of code and in this case is only valid in the 'for' loop.
6. Since the variable 'discountedPrice' is declared in the for loop using the 'let' keyword the scope of the variable is bounded within the 'for' loop. Thus line 13 will throw en error since it is outside the 'for' loop.
7. Since the variable 'finalPrice' is declared in the scope of the function block, line 14 will print out the value '150'.
8. The function will end up returning an array containing all the values of the orginial array halved.
9. Line 11 will throw an error because the variable 'i' is only declared in the scope of the for loop.
10. At line 12 the function will print out the value '3'
11. The function will return an array of all the values halved. This is because the function applied a discount depending on the second input on all the values in the array of the first input. 
12. 
 - student.name
 - student["Grad Year"]
 - student.greeting()
 - student["Favorite Teacher"].name
 - student.courseLoad[0]
13.   
 - '32' -> the + refers to concatation of the string '3' so the 2 is converted to a string type
 - 1 -> since - does not refer to concatation or a string operation it is treated as a number operator so the '3' is converted into a number
 - 3 -> since the 3 is a number, the + will be a number operator so then null is treated as 0.
 - '3null' -> Since 3 is a string the + is treated as concatation operator so the null is coverted to a string type
 - 4 -> since the + operator is not defined as a boolean operator the + is treated as a number operator and the true is converted to a 1
 - 0 -> false is treated as 0 and null is also treated as 0 since the + referes to the number operator
 - '3undefined' -> since 3 is a string the + is a string operator and the undefined is converted to a string.
 - NaN -> since the - operator is not defined for either type no type conversion is possible between the string and undefined.
14.  
 - true -> There is no strict type comparison so the 2 is treated as number
 - false -> Since both values are strings they are compared in lexicographic order 
 - true  -> Since the == does not compare types both will be treated as numbers
 - false -> since === checks for type equality the comparison will return false as they are different types
 - false -> true is turned into a number value which results in 1 which is not equal to 2
 - true -> the 2 value is turned into a boolean which is true so a comparison of === will return true.
15. The '==' operator does not have type checking and allows values to be converted to other types. On the other hand the '===' operator takes into account type checking, and if two values are of different types the operation immediately returns false.
16. [ANSWER](part2-question16.js)
17. The result will be the array [2,4,6]. What modify array does is iterate through the entire array in the first argument and pass those values into the callback function, the result is then pushed into a new array which is returned in the final output. Since doSomething(num) return the input times 2 then all array values are doubled.
18. [ANSWER](part2-question18.js)
19. The function will print out 
    ```
    1
    4
    3
    2
    ```