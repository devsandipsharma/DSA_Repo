# Question 4: Swap Two Variables


### Task Details
Write a program to swap two variables, `a` and `b`. Swapping means interchanging the values of these two variables.


### Example

#### Input
- `a = 3`, `b = 4`

#### Output
- `a = 4`, `b = 3`


### Approach
1. Accept two variables, `a` and `b`, as inputs.
2. Use a temporary variable to hold the value of `a`.
3. Assign the value of `b` to `a`.
4. Assign the value stored in the temporary variable to `b`.
5. Print the swapped values of `a` and `b`.

<details>
  <summary>Solution</summary>

```javascript
function swap(a, b) {
    var temp = a;
    a = b;
    b = temp;
    
    console.log('a value is =', a);
    console.log('b value is =', b);
}
```
</details>