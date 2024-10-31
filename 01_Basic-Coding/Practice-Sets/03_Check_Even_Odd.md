# Question 3: Even or Odd

### Task Details
Create a program to determine whether a given number is "Even" or "Odd" based on the input.

### Example

#### Input
- `14`

#### Output
- `Even`

### Approach
1. Accept an integer `n` as input.
2. Use the modulo operation to check if the number is divisible by 2.
3. Print "Even" if it is divisible, otherwise print "Odd".

<details>
  <summary>Solution</summary>

```javascript
function checkEvenOdd(n) {
    if (n % 2 === 0) {
        console.log("Even");
    } else {
        console.log("Odd");
    }
}
```
</details>