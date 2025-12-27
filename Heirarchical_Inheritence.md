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

```
def display_details(self):
    print("Name:", self.name)
    print("Age:", self.age)
def display_employee(self):
    self.display_details()
    print("Employee ID:", self.emp_id)
def display_patient(self):
    self.display_details()
    print("Patient ID:", self.patient_id)
print("Employee Details") emp = Employee() emp.display_employee()

print("\nPatient Details") pat = Patient() pat.display_patient()
```
## Sample Output
<img width="205" height="527" alt="image" src="https://github.com/user-attachments/assets/3b13e978-dfb0-4fd8-9f74-bfbeef5b96c9" />


