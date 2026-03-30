# 🔁 Recursion: (Factorial) Calculator in C

## 🎯 Aim

To write a C program to calculate the product (factorial) of a given natural number using recursion.

## 🧠 Algorithm

1. **Define** a function `find_factorial(int n)` that recursively calculates the factorial.
2. **Check** if `n == 0`, return `1` (base case, since 0! = 1).
3. **Otherwise**, return `n * find_factorial(n - 1)`.
4. In `main()`:
   - **Read** an integer `num` from the user.
   - **Call** `find_factorial(num)` and store the result in `fact`.
   - **Print** the result.

## Program
```
#include <stdio.h>
int find_factorial(int n) {
    if(n == 0) {
        return 1; 
    } else {
        return n * find_factorial(n - 1);
    }
}

int main() {
    int num, fact;
    printf("Enter a number: ");
    scanf("%d", &num);
    fact = find_factorial(num);
    printf("Factorial = %d\n", fact);

    return 0;
}
```
## Output
<img width="442" height="327" alt="image" src="https://github.com/user-attachments/assets/05a4bdc1-eca2-4038-834d-28dc29b04330" />

## Result
 a C program to calculate the product (factorial) of a given natural number using recursion is written.
