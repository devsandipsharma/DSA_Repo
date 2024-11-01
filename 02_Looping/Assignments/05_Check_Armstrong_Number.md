# Question 5: Check Armstrong Number

### Task Details
Write a program to check whether a given number is an Armstrong number or not. An Armstrong number is a number for which the sum of the cubes of its digits is equal to the number itself.

### Example

#### Input
- `n = 153`

#### Output
- `true`

#### Logic
- 153 is an Armstrong number because \(1^3 + 5^3 + 3^3 = 1 + 125 + 27 = 153\), which is equal to the original number.

#### Input
- `n = 123`

#### Output
- `false`

#### Logic
- 123 is not an Armstrong number because \(1^3 + 2^3 + 3^3 = 1 + 8 + 27 = 36\), which is not equal to the original number.

### Approach
1. Initialize a variable `sum` to store the sum of cubes of digits.
2. Store the original number in a temporary variable `temp`.
3. Use a `while` loop to iterate through the digits of `n`.
4. In each iteration, calculate the last digit using the modulo operator and add its cube to `sum`.
5. Remove the last digit from `temp` by performing integer division by `10`.
6. After the loop, compare the original number with `sum` and print `true` if they are equal, otherwise print `false`.

<details>
  <summary>Solution</summary>

```javascript
function check_armstrong(n) {
    /* Function to check whether a number is an Armstrong number or not
       Print true if yes, else false */
    var sum = 0;
    var temp = n;
    while (temp > 0) {
        var remainder = temp % 10;
        sum = sum + remainder * remainder * remainder;
        temp = Math.floor(temp / 10);
    }
    if (n === sum) {
        console.log(true);
    } else {
        console.log(false);
    }
}
```
</details>