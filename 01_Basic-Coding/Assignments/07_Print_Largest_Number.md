# Question 7: Print the Largest Number


### Task Details
Write a program to print the largest number between two given numbers.


### Example

#### Input
- `a = 3, b = 4`

#### Output
- `4`


### Approach
1. Accept two numbers, `a` and `b`.
2. Compare the two numbers.
3. Print the larger of the two numbers.

<details>
  <summary>Solution</summary>

```javascript
function max(a, b) {
    /* write the code to find the maximum between two numbers below 
       only print the maximum number  */
    if (a > b) {
        console.log(a);
    } else {
        console.log(b);
    }
}
```
</details>