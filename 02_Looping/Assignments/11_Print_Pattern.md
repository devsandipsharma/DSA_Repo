# Question 11: Print Pattern

### Task Details
Write a program to print the following pattern using `for` loops:

```
*****
****
***
**
*
```

### Approach
1. Use an outer `for` loop to iterate from `1` to `5` (the number of rows).
2. Inside the outer loop, initialize an empty string `str` for each row.
3. Use an inner `for` loop to append `*` characters to `str` based on the current row.
4. Print the constructed string `str` after the inner loop.

<details>
  <summary>Solution</summary>

```javascript
function print_pattern() {
    /* Function to print the pattern */

    for (var row = 1; row <= 5; row++) {
        var str = "";
        for (var col = 1; col <= 5 - row + 1; col++) {
            str = str + "*";
        }
        console.log(str);
    }
}
```
</details>