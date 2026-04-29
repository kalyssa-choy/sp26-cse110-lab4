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