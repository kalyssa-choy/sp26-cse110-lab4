## Part 2 

1. It will print 3 because i is initiated as a variable which means it is accessible in the whole function and outside of the for loop
2. It will print 150 because discountedPrice is a var meaning it is accessible outside of the for loop and it keeps being updated everytime the for loop runs by the price[i] * 1/2 so the last iteration overwrites it
3. It will print 150 because finalPrice is just updated with discountedPrice and since it is a whole number it rounds to 150 still
4. It will return [50, 100, 150] since after every iteration of the for loop it pushes the calculated finalPrice of that index to discounted
5. It will cause an error since i is a let variable so it will not be accessible outside of the for loop
6. It will cause an error since discountedPrice is a leet variable so it is only accessible inside of the for loop
7. It will print 150 since it is a let variable defined in the function block so it is still accessible outside of the for loop that updated it to the last iteration of the for loop
8. It will return [50, 100, 150] still since discounted is defined in the function block and it continuously updates after every iteration of the for loop with the calculated finalPrice at that index
9. It will cause an error since i is a let variable and can only be accessed inside of the for loop block
10. It will print 3 since the input prices array has length 3 and since it is a const variable it will only be assigned 3
11. It will return an empty array since it was initialized as that and cannot be changed
12.  
    A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. 
    A. '32' since integers are directly mapped to their exact string representation so it becomes concatenation
    B. 1 forces number conversion with the subtraction
    C. 3 since null is 0 
    D. '3null' since + when using string always means concatenation
    E. 4 since true maps to 1
    F. 0 since false and null both map to 0
    G. '3undefined' since + when using string always means concatenation
    H. NaN since undefined is NaN
14. 
    A. true since '2' maps to 2 and 2 > 1
    B. false since you iterate through the strings so comparison 2 > 1 means that it would be false
    C. true becauase '2' maps to 2 and 2 == 2
    D. false since === checks value and type and 2 is not the same as string '2'
    E. false since true maps to 1 which isn't 2
    F. true since any nonzero number in boolean is true
15. The difference between == and === is that == compares values without taking the type into account and === compares values with taking type into account
17. [2,4,6] since modifyArray loops through [1,2,3] and for each iteration is calls the callback function ut returns num*2 so it multiplies all is by 2.
19. 
    1
    4
    3
    2