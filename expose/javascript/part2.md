## Part 2:
1. line 12 prints 3 because there are 3 elements in the array and i is keeping track of them in the for loop. Since i is a var it can be accessed anywhere in the function so no errors are returned.
2. line 13 prints 150 because it is the last discounted price in the array of prices (300*0.5). Since discountedPrice is a var it can be accessed anywhere in the function so no errors are returned.
3. line 14 will also print 150 because it is the last element in the array's final price which is found in line 8 by using Math.round. Since finalPrice is a var declared in line 4, it can be accessed anywhere in the function so no errors are returned.
4. This function will return an array with the discounted prices based on the array of prices and discount provided on line 19. line 19 gave a prices array [100, 200, 300] with the discount as 0.5, so this function will return the array discount which is [50, 100, 150].
5. line 12 will cause an error since i was defined using let which means it cannot be called outside the for loop. Thus, i is not defined at line 12.
6. line 13 will cause an error since discountedPrice was defined using let which means it cannot be called outside the for loop. Thus, discountedPrice is not defined at line 13.
7. line 14 will print 150 since finalPrice was defined using let on line 5 which was at the start of the function. line 14 calls is still in the same function so finalPrice is defined and won't cause an error. It prints 150 since that was the last value assigned to finalPrice in the for loop.
8. This function will return an array with the discounted prices based on the array of prices and discount provided on line 19. line 19 gave a prices array [100, 200, 300] with the discount as 0.5, so this function will return the array discount which is [50, 100, 150]. There will be no errors caused since discounted was declared on line 3 at the start of the function and is returned on line 16 at the end of the same function.
9. line 11 will cause an error since i was defined using let which means it cannot be called outside the for loop. Thus, i is not defined at line 11.
10. line 12 will print 3 which is the length of the prices array passed in. The length has been declared as a const and is being called in the same function with no changes being made to the const variable so no errors are caused.
11. This function will return an array with the discounted prices based on the array of prices and discount provided on line 19. line 19 gave a prices array [100, 200, 300] with the discount as 0.5, so this function will return the array discount which is [50, 100, 150]. There will be no errors caused since discounted was declared on line 3 at the start of the function as a const and is returned on line 16 at the end of the same function. The only changes made to discount were values being pushed into the array thus the const array is not being assigned a new value thus causing no errors.
12. Given the above Object, write the notation for:  (These should be in your part2.md)
    1. alert(student.name);
    2. alert(student['Grad Year']);
    3. alert(student.greeting());
    4. alert(student['Favourite Teacher'].name);
    5. alert(student.courseLoad[0]);
13. Arithmetic
    1.  ‘3’ + 2 -> '32' because we have a string datatype first so whatever comes after + will be concatenated to the first string. Since integers map to their exact string representation, 2 will stay 2 as a string and be put after 3 to gvie '32'.
    2.  ‘3’ - 2 -> 1 because you cannot perform subtraction on a string so javascript converts '3' to a number and then subtracts 2 from it to give 1.
    3.  3 + null -> 3 because 
    4.  ‘3’ + null -> '3null' because null maps to its exact string representation
    5.  true + 3 -> 4 because true maps to 1
    6.  false + null -> 0 because false maps to 0 and so does null
    7.  '3' + undefined -> '3undefined' because undefined maps to its exact string representation
    8.  '3' - undefined -> Nan because
14. Comparison 
    1.  ‘2’ > 1
    2.  ‘2’ < ‘12’
    3.  2 == ‘2’
    4.  2 === ‘2’
    5.  true == 2
    6.  true === Boolean(2)
15. Explain the difference between the == and === operators.
16. js file
17. x
18. js file
19. The output will be:
1
4
3
2
This is because line 2 will run first and print 1. Then line 3 and 4 have timeouts set so they will set a timer which executes the console.log in it once the timer expires. Line 5 will run and print 4 since it has no delay or timer set. Then 3 will be printed by line 4 first since the timer is 0ms. After 1000ms, 2 will be printed last by line 3.