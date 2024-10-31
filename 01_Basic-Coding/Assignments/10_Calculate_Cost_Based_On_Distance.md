# Question 10: Calculate Cost Based on Distance


### Task Details
Given a variable \( D \) (distance), write a program to print the cost associated with it based on the following criteria:

- If the distance is 100 km or less, the cost is 5.
- If the distance is greater than 100 km and up to 500 km, the cost is 8.
- If the distance is greater than 500 km and up to 1000 km, the cost is 10.
- For distances greater than 1000 km, the cost is 12.


### Example

#### Input
- `D = 700`

#### Output
- `10`


### Approach
1. Accept the distance as input.
2. Use conditional statements to determine the cost based on the given distance.
3. Print the associated cost.

<details>
  <summary>Solution</summary>

```javascript
function print_cost(distance) {
    /* write the code below to print the cost
       if the distance is given   */
    if (distance <= 100) {
        console.log(5);
    } else if (distance > 100 && distance <= 500) {
        console.log(8);
    } else if (distance > 500 && distance <= 1000) {
        console.log(10);
    } else {
        console.log(12);
    }
}
```
</details>