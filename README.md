# Even–Odd Checker

This is a **simple Python program** to check whether a given number is **even or odd**.

## 📘 Description
The program asks the user to enter a number and then checks:
- If the number is divisible by 2 → it’s **Even**
- Otherwise → it’s **Odd**

## 🧩 Code

```python
# Program to check whether a number is even or odd

num = int(input("Enter a number: "))

if num % 2 == 0:
    print(num, "is Even")
else:
    print(num, "is Odd")
