# Question 6: Check if Number is Magical


### Task Details
A number is said to be magical if it is greater than 10. If the number `n` is greater than 10, print "magical". Otherwise, print "not magical".


### Example

#### Input
- `n = 15`

#### Output
- `magical`

#### Input
- `n = 5`

#### Output
- `not magical`


### Approach
1. Accept a number `n` as input.
2. Check if `n` is greater than 10.
3. If it is, print "magical".
4. If not, print "not magical".

<details>
  <summary>Solution</summary>

```javascript
function checkMagicalEnergy(n) {
    if (n > 10) {
        console.log("magical");
    } else {
        console.log("not magical");
    }
}
```
</details>