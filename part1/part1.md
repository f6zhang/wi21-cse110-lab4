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
12. It will return []. Because const value cannot change, so it will return the value of its definition.
13a. student.name
13b. student["Grad Year"]
13c. student.greeting()
13d. student["Favorite Teacher"].name
13e. student.courseLoad[0]
