# Question 1: Print Even Numbers Using While Loop

### Task Details
Write a program using only a `while` loop to print all even numbers from 1 to a given number `n`.

### Example

#### Input
- `n = 10`

#### Output
- `2`
- `4`
- `6`
- `8`
- `10`

### Approach
1. Initialize a variable to the smallest even number, which is `2`.
2. Use a `while` loop to check if the variable is less than or equal to `n`.
3. If the condition is true, print the current number and increment it by 2.
4. The loop continues until all even numbers up to `n` are printed.

<details>
  <summary>Solution</summary>

```javascript
function print_even(n) {
    // write the code to print all even numbers from 1 to n
    var num = 2;
    while (num <= n) {
        console.log(num);
        num = num + 2;
    }
}
```
</details>