Car Parking Management System
This is a simple console-based Car Parking Management System implemented in C++. The program allows users to park cars, vacate slots, and exit the system.

Features
Main Menu Options
The program provides a menu with three options:

Park Car
Vacate Slot
Exit
The user selects an option by entering a choice number.

Park Car
Car Number Plate: The user enters the car's number plate.
Parking Type: The user chooses between two parking types:
Regular Slot: Allows selection of a slot between 1 and 10.
Premium Slot: Allows selection of a slot between 1 and 5.
Validation: The program checks the slot number against the selected parking type's range. If valid, it confirms that the car has been parked. If invalid, it displays an error message.
Vacate Slot
Car Number Plate: The user enters the car's number plate to identify the vehicle to be removed.
Parking Type: Similar to the parking option, the user selects the parking type (Regular or Premium).
Validation: The program checks the slot number and confirms the slot is vacated if valid, or displays an error message if the slot number is outside the valid range.
Exit
Ends the program with a goodbye message.
Error Handling
If the user enters an invalid choice in the main menu, parking type, or slot number, the program provides feedback to guide them in correcting their input.

