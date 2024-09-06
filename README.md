# Cab Booking System

A full-featured Cab Booking System designed and implemented in Eclipse with a MySQL backend. This project demonstrates a robust backend infrastructure supporting essential CRUD operations, enabling seamless interaction between the user interface and the underlying database. With a focus on responsiveness and interactivity, this system provides a smooth experience for users looking to book, modify, or cancel cab services.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Database Design](#database-design)
- [CRUD Operations](#crud-operations)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Cab Booking System is a backend-driven project developed using Java in Eclipse IDE, with MySQL Workbench as the database management system. The project emphasizes implementing CRUD (Create, Read, Update, Delete) operations to manage cab bookings efficiently. It features a responsive and interactive interface, providing users with a smooth and intuitive experience while handling various booking functionalities.

## Features

- **Create**: Allow users to create new cab bookings with specified details.
- **Read**: Fetch and display booking details, available cabs, and user information.
- **Update**: Modify existing bookings, including pickup location, drop-off location, time, and cab type.
- **Delete**: Cancel bookings or remove user data as needed.
- **Responsive Design**: Ensures the interface adapts seamlessly across different devices and screen sizes.
- **Interactive User Experience**: Provides real-time updates and smooth navigation.

## Technologies Used

- **Backend**: Java (Eclipse IDE)
- **Database**: MySQL (MySQL Workbench)
- **Server**: Apache Tomcat (optional for local testing)

## Database Design

The database is designed using MySQL Workbench and consists of the following tables:

1. **Users**: Stores user information, including user ID, name, contact details, etc.
2. **Cabs**: Contains cab details such as cab ID, type, availability status, etc.
3. **Bookings**: Manages booking information, including booking ID, user ID, cab ID, pickup and drop-off locations, and timestamps.
   
The tables are interlinked to enable efficient querying and manipulation for various operations.

## CRUD Operations

- **Create**: Users can book a new cab by providing their details and preferences.
- **Read**: The system retrieves user information, booking history, and available cab details from the database.
- **Update**: Users can modify their existing bookings, including changing locations, cab type, or timings.
- **Delete**: Users can cancel their bookings, and the system will remove them from the database accordingly.

## Setup and Installation

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/anjalikumari10/Cab-Booking.git
   ```
2. **Open in Eclipse**: Import the project into Eclipse IDE.
3. **Set Up the Database**:
   - Install and configure MySQL Workbench.
   - Create the necessary database schema and tables using the SQL scripts provided in the `/database` directory.
4. **Configure Database Connection**: Update the database connection settings in the project's configuration file to match your local setup.
5. **Run the Project**: Deploy the project on the Eclipse server or Apache Tomcat.

## Usage

- Open the web application in a browser.
- Register or log in to access the booking dashboard.
- Book a cab by providing pickup and drop-off details.
- View, modify, or cancel bookings through the interactive interface.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or feature additions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
