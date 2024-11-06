
# **Car Parking Management System**

A simple and efficient **Car Parking Management System** implemented in **C++**. This system allows users to interactively park cars, vacate parking slots, and exit the program with proper validation and feedback.

## **Key Features**

### 1. **Main Menu Options**

The program starts with a menu, offering the following options:

- **Park Car**
- **Vacate Slot**
- **Exit**

The user selects an option by entering the corresponding choice number.

---

### 2. **Park Car**

This option allows users to park a car in a selected parking slot.

- **Step 1: Enter Car Number Plate**
    - The user is prompted to enter their car’s number plate.
  
- **Step 2: Select Parking Type**
    - The user chooses between two parking types:
      - **Regular Slot** (1-10)
      - **Premium Slot** (1-5)
  
- **Step 3: Slot Validation**
    - The system validates the slot number chosen:
      - If valid, the car is parked and a confirmation message is shown.
      - If invalid (e.g., out of range), an error message is displayed to prompt the user for a correct input.

---

### 3. **Vacate Slot**

This option allows users to vacate a previously occupied parking slot.

- **Step 1: Enter Car Number Plate**
    - The user inputs the number plate of the car they wish to vacate.
  
- **Step 2: Select Parking Type**
    - The user chooses the type of parking slot they wish to vacate:
      - **Regular Slot** (1-10)
      - **Premium Slot** (1-5)
  
- **Step 3: Slot Validation**
    - The system checks the slot number:
      - If valid, the slot is vacated and a confirmation message is shown.
      - If invalid (out of range), an error message prompts the user to input a correct slot number.

---

### 4. **Exit**

Choosing this option terminates the program, and a polite farewell message is displayed.

---

### **Error Handling**

- If the user enters an invalid option in the main menu, the system will show an error message and prompt the user to enter a valid choice.
- If an invalid slot number is provided, the system will request the user to enter a number within the specified range.
  
---

## **Conclusion**

The **Car Parking Management System** is an interactive and user-friendly C++ application that efficiently manages parking slots with validations and error handling. This system can be extended or modified to fit more complex requirements, such as tracking parking durations, adding user accounts, and integrating with databases.

