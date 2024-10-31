# Question 8: Compute Taxes Based on Salary


### Task Details
If a salary is given, compute the corresponding tax based on the following conditions:

- If Salary >= 15, Tax = 30
- If Salary >= 10 and < 15, Tax = 20
- If Salary >= 5 and < 10, Tax = 10
- Otherwise, Tax = 0


### Example

#### Input
- `s = 20`

#### Output
- `30`


### Approach
1. Accept the salary as input.
2. Determine the tax based on the salary using conditional statements.
3. Print the calculated tax.

<details>
  <summary>Solution</summary>

```javascript
function compute_taxes(s) {
    if (s >= 15) {
        console.log(30);
    } else if (s >= 10 && s < 15) {
        console.log(20);
    } else if (s >= 5 && s < 10) {
        console.log(10);
    } else {
        console.log(0);
    }
}
```
</details>