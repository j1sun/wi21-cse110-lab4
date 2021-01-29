# Part 1 Questions

1. Since `i` is a variable declared by `var` in the for loop but within the scope of the function, it will remain at the end of the `for` loop and equal `prices.length`. Then, on line 11, the correct value of `i` will be printed to the console.

2. Since `discountedPrice` is a variable declared by `var` in the for loop but within the scope of the function, it will remain at the end of the `for` loop and equals `prices[prices.length -1] * (1 - discount)`. Then, on line 12, the correct value of `discountedPrice` will be printed to the console.

3. Since `finalPrice` is a variable declared by `var` at the start of the function, it will equal `Math.round(discountedPrice * 100) / 100` at the end of the `for` loop, where `discountedPrice` is the same value in question 2. Then, on line 13, the correct value of `finalPrice` will be printed to the console.

4. For each iteration of the `for` loop, the current value of `finalPrice` will be pushed into `discounted`. If we follow each iteration, we end up returning `discounted = [50, 100, 150]`.

5. Since `i` is a variable declared by `let` in the for loop, trying to print `i` to the console will result in an error.

6. Since `discountedPrice` is a variable declared by `let` in the for loop, trying to print `discountedPrice` to the console will result in an error.

7. Since `finalPrice` is a variable declared by `let` at the start of the function, it will equal `Math.round(discountedPrice * 100) / 100` at the end of the `for` loop, where `discountedPrice` is the same value in question 2. Then, on line 13, the correct value of `finalPrice` will be printed to the console.

8. For each iteration of the `for` loop, the current value of `finalPrice` will be pushed into `discounted`. If we follow each iteration, we end up returning `discounted = [50, 100, 150]`.

9. Since `i` is a variable declared by `let` in the for loop, trying to print `i` to the console will result in an error.

10. Since `discountedPrice` is a variable declared by `const` in the for loop, trying to print `discountedPrice` to the console will result in an error.

11. Since `finalPrice` is a variable declared by `const` at the start of the function, it will not change in the `for` loop. Then, on line 13, `[]` will be printed to the console.

12. Since `finalPrice` is a variable declared by `const` at the start of the function, it will not change in the `for` loop. Thus, we end up returning `discounted = []`.

13.
    1. `student.name`
    2. `student['Grad Year']`
    3. `student.greeting()`
    4. `student['Favorite Teacher']['name']`
    5. `student.courseLoad[0]`

14.
    1. Evaluates to '32' since '3' + 2 is interpreted as string concatenation.
    2. Evaluates to 1 since '3' - 2 is interpreted as subtraction, and '3' is converted to a number.
    3. Evaluates to 3, since 3 + null is interpreted as addition, and null is defined as 0.
    4. Evaluates to '3null', since '3' + null is interpreted as string concatenation.
    5. Evaluates to 4, since true + 3 is interpreted as addition, and true is defined as 1.
    6. Evaluates to 0, since false + null is interpreted as addition, and both false and null are defined as 0.
    7. Evaluates to '3undefined', since "3" + undefined is interpreted as string concatenation.
    8. Evaluates to NaN, since "3" - undefined is interpreted as subtraction, and subtracting undefined results in NaN.

15. 
    1. Evaluates to true, since both values are converted to numbers and 2 > 1.
    2. Evaluates to false, since the character '2' comes after the character '1' in '12'.
    3. Evaluates to true, since the == operator converts both values to numbers and 2 == 2.
    4. Evaluates to false, since the === operator does not perform type conversion.
    5. Evaluates to false, since both values are converted to numbers and true (converted to 1) does not equal 2.
    6. Evaluates to true, since the Boolean() function passes in 2 and returns true.

16. The `==` operator performs type conversions when comparing, while the `===` operator does not.

17. 'How are you?' is printed, since `2 == true` evaluates to false, while `2` evaluates to true (it is truthy, ie. not defined as false).

18. See `part1-question18.js`.

19. `[6, 8, 10]` is returned. For each iteration of the `for` loop, we push the results of `doSomething(array[i], function(x) { return x * 2 })` into `newArr`. For the first item, 1, we call `doSomething(1, function(x) { ... })`, which then returns the result of `function(x)` where `x` equals `1 + 2`; that function returns `3 * 2` which equals `6`. This repeats for each of the other items in the array and result in `8` and `10`, which are then pushed into the array and returned.

20. See `part1-question20.js`.

21. The output is:
```
1
4
3
2
```