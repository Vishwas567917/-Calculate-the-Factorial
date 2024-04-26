# JavaScript Factorial Functions

This repository contains a simple JavaScript script that calculates the factorial of a given number in two different ways: using the `reduce` method and a `for` loop. It demonstrates basic JavaScript operations and iterative techniques.

## Contents

- **HTML File:** The entry point for the script.
- **JavaScript File:** Contains the functions to calculate the factorial using different approaches.

## How It Works

The script calculates the factorial of a given number. Factorial is a mathematical operation defined as the product of all positive integers up to a given number. For example, the factorial of 5 is `5 * 4 * 3 * 2 * 1 = 120`.

### `factorial` Function

This function uses the `reduce` method to calculate the factorial:

```javascript
function factorial(number) {
    let arr = Array.from(Array(number + 1).keys());
    return arr.slice(1).reduce((a, b) => a * b);
}

facFor Function
This function uses a for loop to calculate the factorial:

function facFor(number) {
    let fac = 1;
    for (let index = 1; index <= number; index++) {
        fac = fac * index;
    }
    return fac;
}

let a = 7;
console.log(factorial(a)); // Output: 5040
console.log(facFor(a));    // Output: 5040
Both functions return the same result, demonstrating two different approaches to calculate the factorial.

Contributing
Contributions are welcome! If you have suggestions for improving the script or would like to add more functionalities, please open an issue or submit a pull request.
