# Experiment No: 1e – SEB-Smallest  of Three Numbers

## AIM  
To write a Python program to find the smallest between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the smallest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum.  
   - Else, if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum.  
   - Otherwise, `num3` is the minimum.  
4. Print the smallest value along with the input numbers in the format:  
   `"The smallest of num1, num2, num3 is min_num."`  
5. Terminate the program.

## PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T

num1 = int(input())
num2 = int(input())
num3 = int(input())

min_num = num1 if (num1 <= num2 and num1 <= num3) else num2 if (num2 <= num1 and num2 <= num3) else num3

print(f"The smallest of {num1}, {num2}, {num3} is {min_num}")
```

## OUTPUT
<img width="1007" height="315" alt="image" src="https://github.com/user-attachments/assets/a8ecaa57-d69a-4e03-ba68-86cd0ed38570" />


## RESULT
The program was successfully executed. It correctly identified the minimum number between three integers using a conditional expression.
