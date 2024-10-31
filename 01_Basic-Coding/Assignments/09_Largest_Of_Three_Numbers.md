# Question 9: Largest of Three Numbers


### Task Details
Write a program to print the largest of three given numbers.


### Example

#### Input
- `a = 3`
- `b = 5`
- `c = 1`

#### Output
- `5`


### Approach
1. Accept three numbers as input.
2. Compare the numbers using conditional statements to determine the largest.
3. Print the largest number.

<details>
  <summary>Solution</summary>

```javascript
function max(a, b, c) {
    /* write the code to find the maximum between the three numbers below 
       only print the maximum number */
    if (a > b && a > c) {
        console.log(a);
    } else if (b > a && b > c) {
        console.log(b);
    } else {
        console.log(c);
    }
}
```
</details>