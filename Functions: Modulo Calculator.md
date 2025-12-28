# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
~~~
def compute_modulo(a, b):
    return a % b
num1 = int(input("Enter a number: "))
num2 = int(input("Enter a number: "))
result = compute_modulo(num1, num2)
print(f"The modulo of {num1} % {num2} is {result}")
~~~

## Output
<img width="436" height="166" alt="image" src="https://github.com/user-attachments/assets/223b2410-5e59-4779-8161-3e6f649a7b7b" />

## Result
Thus,the program has been executed successfully.
