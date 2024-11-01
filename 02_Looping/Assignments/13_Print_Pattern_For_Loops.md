# Question 13: Print Pattern Using For Loops

### Task Details
Write a program to print the following pattern using `for` loops:

```
*****
****
***
**
*
*
**
***
****
*****
```

### Approach
1. Initialize a variable `totalRows` to `5` (the number of rows for the upper part of the pattern).
2. Use a `for` loop to iterate through a total of `totalRows * 2` rows.
3. Inside the loop, initialize an empty string `str` for each row.
4. Determine the number of stars to print in the current row using a condition:
   - If `row` is less than or equal to `totalRows`, print stars decreasing from `totalRows` to `1`.
   - If `row` is greater than `totalRows`, print stars increasing from `1` to `totalRows`.
5. Print the constructed string `str` after each row.

<details>
  <summary>Solution</summary>

```javascript
function print_pattern() {
    /* Function to print the pattern */
    var totalRows = 5;
    for (var row = 1; row <= totalRows * 2; row++) {
        var str = "";
        var patternCondition = row <= totalRows ? totalRows - row + 1 : row - totalRows;
        for (var col = 1; col <= patternCondition; col++) {
            str = str + "*";
        }
        console.log(str);
    }
}
```
</details>
