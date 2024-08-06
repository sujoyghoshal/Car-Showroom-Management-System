# Car-Showroom-Management-System
This Java-based Car Showroom Management System leverages Object-Oriented Programming (OOP) principles to efficiently manage and organize a car dealership. The system provides a user-friendly interface to handle various operations related to showrooms, cars, and employees.

## Overview

The Car Showroom Management System is a Java application designed using Object-Oriented Programming (OOP) principles. This system provides functionality to manage car showrooms, cars, and employees, allowing users to efficiently add and retrieve details related to these entities.

## Features

- **Add Showroom:** Create and manage showrooms with details such as name, location, and contact information.
- **Add Car:** Add cars to the showroom's inventory with attributes including make, model, year, price, and associated showroom.
- **Add Employee:** Register employees with their details, including name, ID, position, and associated showroom.
- **Get Car:** Retrieve information about a specific car based on search criteria such as make, model, or ID.
- **Get Employee:** Fetch details of an employee using their ID or name.

## Technologies Used

- **Java:** Programming language used for developing the application.
- **Object-Oriented Programming (OOP):** Core principles used for designing the system.

## Classes and Functionality

### Showroom

- **Attributes:**
  - `name`: Name of the showroom
  - `location`: Address of the showroom
  - `contactInfo`: Contact details of the showroom
  - `cars`: List of cars available in the showroom
  - `employees`: List of employees working at the showroom

- **Methods:**
  - `addCar(Car car)`: Adds a car to the showroom's inventory.
  - `addEmployee(Employee employee)`: Registers a new employee at the showroom.
  - `getCar(String make, String model)`: Retrieves a car based on make and model.
  - `getEmployee(String employeeId)`: Fetches an employee's details by ID.

### Car

- **Attributes:**
  - `make`: Car manufacturer
  - `model`: Car model
  - `year`: Manufacturing year
  - `price`: Price of the car
  - `showroom`: Showroom where the car is available

- **Methods:**
  - `getDetails()`: Returns a string containing car details.

### Employee

- **Attributes:**
  - `name`: Employee's name
  - `id`: Unique employee ID
  - `position`: Employee's job position
  - `showroom`: Showroom where the employee works

- **Methods:**
  - `getDetails()`: Returns a string containing employee details.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/sujoyghoshal/Car-Showroom-Management-System.git
    ```

2. Navigate to the project directory:
    ```bash
    cd car-showroom-management-system
    ```

3. Compile the Java files:
    ```bash
    javac *.java
    ```

4. Run the application:
    ```bash
    java Main
    ```

## Usage

To use the Car Showroom Management System, follow these steps:

1. **Add a Showroom:** Create a new showroom by providing necessary details.
2. **Add a Car:** Add a car to the showroom with its details.
3. **Add an Employee:** Register an employee and associate them with a showroom.
4. **Retrieve Car Details:** Search for a car by make and model.
5. **Retrieve Employee Details:** Search for an employee by ID.

## Contributing

Feel free to contribute to this project by submitting pull requests or opening issues for any bugs or feature requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, please contact:

- **Email:** sujoyghoshal.s@gmail.com
- **GitHub:** [sujoyghoshal](https://github.com/sujoyghoshal/Car-Showroom-Management-System) 

