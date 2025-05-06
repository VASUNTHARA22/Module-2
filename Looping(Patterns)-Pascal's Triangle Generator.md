# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```def factorial(n): 
if n == 0 or n == 1: 
return 1 
return n * factorial(n - 1) 
def combination(n, k): 
return factorial(n) // (factorial(k) * factorial(n - k)) 

num_rows = int(input()) 

for i in range(num_rows): 

print(' ' * (num_rows - i - 1), end='') 


for j in range(i + 1): 
print(combination(i, j), end=' ') 

print()
```

## Sample Output

![438595534-44e346c2-5e4e-4613-a5fb-dc31089e614a](https://github.com/user-attachments/assets/4d3900be-85c2-401e-ab5f-cbe93055577e)

## Result

Thus, the program has been successfully executed

