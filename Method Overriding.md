# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:
```
class Fish:
    def Type(self):
        print("fish")
class Shark(Fish):
    def Type(self):
        print("shark")
gold=Fish()
hammer=Shark()
for fish in (gold,hammer):
    fish.Type()
```
## OUTPUT
<img width="1437" height="832" alt="530224153-ea1ff3ab-192f-4692-997b-b482b981852c" src="https://github.com/user-attachments/assets/81964baf-1dee-489b-9f7d-58bb2f94ce67" />

## RESULT
Thus,the given Python Program has been executed successfully.
