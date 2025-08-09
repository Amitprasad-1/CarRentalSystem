Car Rental System – Java Console Application

Overview

A console-based Car Rental System built in Java that manages car availability, customer records, and rental transactions via an interactive menu.

Features

Rent available cars and track availability.

Return cars and remove active rentals.

Calculate rental cost based on number of days.

Store cars, customers, and rentals using ArrayList.

Simple menu-driven CLI for user interaction.


Tech Stack

Java (OOP)

Java Collections (ArrayList)

IntelliJ IDEA (recommended)

Git & GitHub


Project Structure

CarRentalSystem/
├── src/
│   └── Main.java              # All classes (Car, Customer, Rental, CarRentalSystem, Main)
└── README.md

How to Run

# Clone the repository
git clone https://github.com/Amit Prasad-1/CarRentalSystem.git
cd CarRentalSystem

# Open in IntelliJ IDEA and run Main.java
# OR compile & run from terminal:
javac src/Main.java
java -cp src Main

Usage (sample)

===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice:

Notes

Classes are currently in a single Main.java file for simplicity; you can split them into separate files (one class per file) for better organization.

Consider marking immutable fields final and adding persistence (file/DB) if extending the project.


License

MIT License

Author

Your Name — https://github.com/YOUR_USERNAME
