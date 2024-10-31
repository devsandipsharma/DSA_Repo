# Question 4: Assign Grades Based on Student Scores

### Task Details
In an educational institution, students are graded based on their scores in examinations. Your task is to create a program that assigns a grade to a student based on the following criteria:

- A student scoring **less than or equal to 50** should receive a **"D"** grade.
- A student scoring **greater than 50 but less than 60** should receive a **"C"** grade.
- A student scoring **between 60 and 75 (inclusive)** should receive a **"B"** grade.
- A student scoring **greater than 75** should receive an **"A"** grade.

### Example

Given the following student scores:

- `45` ➔ `D`
- `58` ➔ `C`
- `70` ➔ `B`
- `80` ➔ `A`

### Input
- A single integer representing the student's score. The score is guaranteed to be in the range of **0** to **100**.

### Output
- The program should output the corresponding grade for the given score.

### Approach
1. Accept the student's score as input.
2. Use conditional statements to determine the grade based on the specified criteria.
3. Print the corresponding grade.

<details>
  <summary>Solution</summary>

```javascript
function assignGrades(score) {
    // Your implementation to assign grades based on the given criteria
    // Output the corresponding grade
    if (score <= 50) {
        console.log("D");
    } else if (score > 50 && score < 60) {
        console.log("C");
    } else if (score >= 60 && score < 75) {
        console.log("B");
    } else {
        console.log("A");
    }
}
```
</details>