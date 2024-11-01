# Question 14: Print Pattern Using For Loops2

### Task Details
Write a program to print the following pattern using `for` loops:

```
*    *
**   **
***  ***
**** ****
**********
```

### Approach
1. Initialize a variable `totalRows` to `5` (the number of rows for the pattern).
2. Use a `for` loop to iterate through the total number of `totalRows`.
3. Inside the loop, initialize an empty string `str` for each row.
4. For each row, determine the number of stars and spaces to print:
   - Print stars increasing from `1` to `row`.
   - Print spaces to separate the two groups of stars.
   - Print stars again, equal to the number of stars printed initially.
5. Print the constructed string `str` after each row.

<details>
  <summary>Solution</summary>

```javascript
function print_pattern() {
    /* Function to print the pattern */
    var totalRows = 5;
    for (var rows = 1; rows <= totalRows; rows++) {
        var str = "";
        // Print stars
        for (var cols = 1; cols <= rows; cols++) {
            str = str + "*";
        }
        // Print spaces
        for (var spaces = totalRows - rows; spaces >= 1; spaces--) {
            str = str + " ";
        }
        // Print stars again
        for (var cols = 1; cols <= rows; cols++) {
            str = str + "*";
        }
        console.log(str);
    }
}
```
</details>