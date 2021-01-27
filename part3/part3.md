Answers:
 1. It will print the length of prices. Because declaring a variable with var has global scope.
 2. It will print raw discount price of the last variable in prices. The same as above.
 3. It will be printed, the same value as the last value in the "discounted". Because both print and the definition of "final price" is in the scope of this function.
 4. It will return "[50, 100, 150]". Because this function loop through prices and applies the discount to them. Apply 0.5 discount on [100, 200, 300] is [50, 100, 150].
 5. Error, no such varibale. Because i is in the for loop scope, which the print don't have access to.
 6. Error, no such varibale. The same reason as above.
 7. It will be printed, the same value as the last value in the "discounted". Because both print and the definition of "final price" is in the scope of this function.
 8. It will return "[50, 100, 150]". The same as 4.
 9. Error, no such varibale. Because i is in the for loop scope, which the print don't have access to.
 10. Error, no such varibale. The same reason as above.
 11. It will return 0, as it defined above and const value cannot change.
 12. It will return [0, 0, 0]. Because const value cannot change, so three 0 will be pushed to the array.
 13. a: student.name b: student["Grad Year"] c: student.greeting() d: student["Favorite Teacher"].name e: student.courseLoad[0]
 14. a: 32 b: 1 c: 3 d: 3null e: 4 f: 0 g: 3undefined h: NaN
 15. a: true b: false c: true d: false e: false f: true
 16. == only check if two values are equal. === check if two values are equal and if they are the same datatype.
 17. "How are you?". Because 2 == true will return false, their values are different. But 2 is true because anything other than 0 is true.
 18. See part1-question18.js
 19. It will return [6, 8, 10]. The callback in modifyArray is doSomething, it would call doSomething(array[i], function ...), which is funtion(array[i]+2). So the output is (array[i] + 2) * 2, which is [6, 8, 10].
 20. See part1-question20.js
 21. 1
     4
     3
     2
