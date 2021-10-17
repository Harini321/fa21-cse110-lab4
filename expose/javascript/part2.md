1. The value of i is 3 at the end of the for loop so 3 is printed to the console. i is declared using var so its scope is not restricted to just the for loop.
2. The value of discountedPrice is 150 so 150 is printed. discountedPrice is declared using var so it's accessible in the whole program, not just the for loop.
3. finalPrice is printed as 150 because its declared as var at the beginning of the function. Printing happens in the function so there are no scope issues.
4. The array [50,100,150] is returned. There are no scope restrictions for discounted so it simply returns the array
5. i is declared using let so its scope is only within the for loop. That's why there is an error when trying to print i outside the for loop.
6. There is an error while printing discountedPrice because the scope of the variable is only within the for loop(since its declared in the for loop using 'let')
7. The program prints 150. Because finalPrice's scope is the function discountPrices and the program is printing finalPrice inside the function the variable is accessible.
8. The array [50,100,150] is returned. The variable discounted can be accessed throughout the whole function so there are no errors when it's being returned.
9. There is an error because the scope of i is only within the for loop.
10. The program prints 3 because length is declared and initialized at the beginning of the program and the value is never changed as it is a const variable.
11. The function returns [50,100,150]. Constant numbers are added into a constant array so there are no errors.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student.Favorite Teacher.name
    E. student.courseLoad[0]
13. A. '3' + 2 = '32' (integers map to their exact string representation)
    B. '3' - 2 = 1 (3 is treated like an integer)
    C. 3 + null = 3 (null equals 0 when doing arithmetic with integers)
    D. '3' + null = 3null (string concatenation occurs because 3 is a string)
    E. true + 3 = 4 (true maps to the integer 1)
    F. false + null = 0 (false and null are both 0)
    G. '3' + undefined = 3undefined (3 is a string so string concatenation occurs)
    H. '3' - undefined = NaN (subtracting undefined from an integer is not a number)
14. A. '2' > 1 = true (the string 2 is mapped to the integer 2)
    B. '2' < '12' = false (string comparisons are based on unicode ordering and 1 comes before 2)
    C. 2 == '2' = true ('2' maps to the integer 2 so they both are equal)
    D. 2 === '2' = false (both have same value but they are different types)
    E. true == 2 = false (true maps to 1 and 1 doesn't equal 2)
    F. true === Boolean(2) = true (Boolean(2) evaluates to a boolean value of true)
15. == only looks for value equality while === checks for both value AND type equality
17. When modifyArray is called, it passes two arguments the array [1,2,3] and the function doSomething, which are stored in modifyArray as array and callback respectively. A new array is created in the modifyArray function. Using a for loop, it goes through each element in array and calls doSomething passing in that element as a parameter. doSomething simply doubles the number and returns the result, and that result is what gets stored in the new array. After going through all the elements, newArr is returned.
19. The output is 
    1
    4
    3
    2