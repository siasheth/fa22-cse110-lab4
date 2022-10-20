## Part 1:
1. values added:  20
2. final result:  20
3. values added:  20
4. The code will return an error because result is not defined
5. The code will return an error because you cannot assign something to a const variable (line 6)
6. The code will return an error because you cannot assign something to a const variable (line 6)

## Part 2:
1. line 12 prints 3 because there are 3 elements in the array and i is keeping track of them in the for loop. Since i is a var it can be accessed anywhere in the function so no errors are returned.
2. line 13 prints 150 because it is the last discounted price in the array of prices (300*0.5). Since discountedPrice is a var it can be accessed anywhere in the function so no errors are returned.
3. line 14 will also print 150 because it is the last element in the array's final price which is found in line 8 by using Math.round. Since finalPrice is a var declared in line 4, it can be accessed anywhere in the function so no errors are returned.
4. This function will return an array with the discounted prices based on the array of prices and discount provided on line 19. line 19 gave a prices array [100, 200, 300] with the discount as 0.5, so this function will return the array discount which is [50, 100, 150].
5. line 12 will cause an error since i was defined using let which means it cannot be called outside the for loop. Thus, i is not defined at line 12.
6. line 13 will cause an error since discountedPrice was defined using let which means it cannot be called outside the for loop. Thus, discountedPrice is not defined at line 13.
7. line 14 will print 150 since finalPrice was defined using let on line 5 which was at the start of the function. line 14 calls is still in the same function so finalPrice is defined and won't cause an error. It prints 150 since that was the last value assigned to finalPrice in the for loop.