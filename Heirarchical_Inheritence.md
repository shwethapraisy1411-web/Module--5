# Hierarchical Inheritance in Python

This Python project demonstrates **Hierarchical Inheritance** using a base class `Details` and two derived classes `Employee` and `Patient`. The program collects and displays details for both employees and patients.

## 🎯 Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details.

## 📘 Description

- **Base Class:** `Details`
  - Stores common attributes: `name`, `age`
  - Provides methods: `getName()`, `getAge()`

- **Derived Class 1:** `Employee`
  - Inherits from `Details`
  - Adds: `employee_id`, `department`
  - Method: `getEmployeeDetails()`

- **Derived Class 2:** `Patient`
  - Inherits from `Details`
  - Adds: `patient_id`, `disease`
  - Method: `getPatientDetails()`

## 🧠 Algorithm

1. Create base class `Details` with common attributes.
2. Create `Employee` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for employee and patient data.
5. Display collected information using class methods.

## Program

<img width="796" height="708" alt="image" src="https://github.com/user-attachments/assets/d6d469ee-b997-46c8-aa74-f2d8e5c62985" />
<img width="786" height="732" alt="image" src="https://github.com/user-attachments/assets/93db9a33-6ebf-47d2-bf24-e8d75f70080e" />

## Sample Output
<img width="822" height="755" alt="image" src="https://github.com/user-attachments/assets/0cd3b221-b74f-4ce9-95ea-ca7aec0dc4b4" />

## Result
The output is verified successfully.
