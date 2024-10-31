# Question 11: Pass or Fail using Ternary Operator


### Task Details
Write a program to assume a value of marks and print whether a person has failed or passed using a ternary operator.

- If Marks >= 40 → "pass"
- Otherwise → "fail"


### Example

#### Input
- `Marks = 52`

#### Output
- `pass`


### Approach
1. Accept the marks as input.
2. Use a ternary operator to determine if the person has passed or failed based on the marks.
3. Print "pass" or "fail".

<details>
  <summary>Solution</summary>

```javascript
function has_passed(marks) {
    /* write the code to find whether a candidate has passed or failed 
       only print "pass" or "fail" */
    var result = marks >= 40 ? "pass" : "fail";
    console.log(result);
}
```
</details>