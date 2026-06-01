# Multilevel Inheritance Example in Python

This Python project demonstrates the concept of **Multilevel Inheritance** to collect and display the **name**, **age**, and **location** of a person.

## 🎯 Aim

To write a Python program that uses multilevel inheritance to get and display a person’s name, age, and location.

## 🧠 Algorithm

1. **Parent Class**  
   - `__init__(name)` initializes the `name` attribute.  
   - `getName()` returns the `name`.

2. **Child Class (inherits Parent)**  
   - `__init__(name, age)` initializes `name` using `super()` and adds `age`.  
   - `getAge()` returns the `age`.

3. **Grandchild Class (inherits Child)**  
   - `__init__(name, age, location)` initializes `name` and `age` using `super()` and adds `location`.  
   - `getLocation()` returns the `location`.

4. **Input & Output**  
   - Take user input for name, age, and location.  
   - Create an instance of `Grandchild`.  
   - Print all details using class methods.

## Program

<img width="792" height="726" alt="image" src="https://github.com/user-attachments/assets/9ec531ef-79fc-4a07-b93b-1ff432d92ffc" />
<img width="796" height="374" alt="image" src="https://github.com/user-attachments/assets/15e03d16-33b2-4904-8f4c-425cef9e5434" />

## Sample Output
<img width="569" height="389" alt="image" src="https://github.com/user-attachments/assets/cb3e853a-0e6b-4def-bb7c-a661526db738" />

## Result
The output is verified successfully.
