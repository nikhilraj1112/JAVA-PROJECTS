# Car Rental System

## Overview
This is a simple **Car Rental System** built using Java. It allows customers to rent and return cars while managing rental records efficiently.

## Features
- **Add Cars**: The system maintains a list of available cars.
- **Rent a Car**: Customers can rent a car for a specified number of days.
- **Return a Car**: Customers can return rented cars.
- **Rental Price Calculation**: The system calculates the total rental cost.
- **Car Availability Management**: Prevents double-booking of cars.
- **Customer Management**: Stores customer details and rental records.

## Technologies Used
- **Java**
- **Object-Oriented Programming (OOP) principles**
- **Scanner (for user input handling)**


## Class Structure
### 1. `Car`
- Represents a car with ID, brand, model, price, and availability status.
- Methods: `rent()`, `returnCar()`, `calculatePrice()`

### 2. `Customer`
- Represents a customer with ID and name.

### 3. `Rental`
- Represents a rental transaction with a car, customer, and rental duration.

### 4. `CarRentalSystem`
- Manages the list of cars, customers, and rentals.
- Handles car renting and returning.
- Displays a user menu.

### 5. `Main`
- Entry point of the program.
- Initializes cars and starts the menu-driven system.

## Example Usage
```
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 1
Enter your name: John Doe
Available Cars:
C001 - Toyota Camry
C002 - Honda Accord

Enter the car ID you want to rent: C001
Enter the number of days for rental: 3

== Rental Information ==
Customer ID: CUS1
Customer Name: Chris Evans
Car: Toyota Camry
Rental Days: 3
Total Price: $180.00

Confirm rental (Y/N): Y
Car rented successfully.
```


### 🚗 Happy Renting! 🚗

