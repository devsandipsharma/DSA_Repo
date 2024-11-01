# Question 12: Print Pattern Using While Loops

### Task Details
Write a program to print the following pattern using `while` loops:

```
*****
****
***
**
*
```

### Approach
1. Initialize a variable `row` to `1` and a variable `totalStars` to `5` (the number of rows).
2. Use a `while` loop to iterate until `row` exceeds `totalStars`.
3. Inside the outer loop, initialize an empty string `star` for each row and a variable `col` to `1`.
4. Use another `while` loop to append `*` characters to `star` based on the current row.
5. Print the constructed string `star` after the inner loop and increment `row`.

<details>
  <summary>Solution</summary>

```javascript
function print_pattern() {
    /* Function to print the pattern */
    var row = 1;
    var totalStars = 5;
    while (row <= totalStars) {
        var star = "";
        var col = 1;
        while (col <= totalStars - row + 1) {
            star = star + "*";
            col++;
        }
        console.log(star);
        row++;
    }
}
```
</details>