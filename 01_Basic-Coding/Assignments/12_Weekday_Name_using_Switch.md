# Question 12: Weekday Name using Switch Statement


### Task Details
Given the day number, print the day name in lower case corresponding to it by using the help of a switch statement.

- Note: Day 1 is Monday.
- If the day is not valid (i.e., less than 1 or greater than 7), print "invalid".


### Example

#### Input
- `Day - 3`

#### Output
- `wednesday`


### Approach
1. Accept the day number as input.
2. Use a switch statement to map the day number to its corresponding day name.
3. Print the day name or "invalid" if the input is out of range.

<details>
  <summary>Solution</summary>

```javascript
function weekday_name(n) {
    /* write the code to print the weekday name in lower case when
       the weekday number is given using switch statements */
    switch (n) {
        case (1):
            console.log("monday");
            break;
        case (2):
            console.log("tuesday");
            break;
        case (3):
            console.log("wednesday");
            break;
        case (4):
            console.log("thursday");
            break;
        case (5):
            console.log("friday");
            break;
        case (6):
            console.log("saturday");
            break;
        case (7):
            console.log("sunday");
            break;
        default:
            console.log("invalid");
    }
}
```
</details>