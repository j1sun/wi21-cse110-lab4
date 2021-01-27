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
