# Question 15: Print Pattern Using While Loops

### Task Details
Write a program to print the following pattern using `while` loops:

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
1. Initialize a variable `patternLength` to `5` (the number of rows for the upper part of the pattern).
2. Use a `while` loop to iterate through a total of `patternLength * 2` rows.
3. Inside the loop, initialize an empty string `str` for each row and a counter variable `cols` set to `1`.
4. Determine the number of stars to print in the current row using a condition:
   - If `rows` is less than or equal to `patternLength`, print stars decreasing from `patternLength` to `1`.
   - If `rows` is greater than `patternLength`, print stars increasing from `1` to `patternLength`.
5. Print the constructed string `str` after each row.

<details>
  <summary>Solution</summary>

```javascript
function print_pattern() {
    /* Function to print the pattern */
    var patternLength = 5;
    var rows = 1;
    while (rows <= patternLength * 2) {
        var cols = 1;
        var str = "";
        var patternCondition = rows <= patternLength ? patternLength - rows + 1 : rows - patternLength;
        while (cols <= patternCondition) {
            str = str + "*";
            cols++;
        }
        console.log(str);
        rows++;
    }
}
```
</details>