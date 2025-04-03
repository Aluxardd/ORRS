# ORRS

Designed and created an online railway reservation system (ORRS) using MySQL.

## Features

1. **User Management**:
   - Add, update, and delete user profiles.
   - Secure storage of user credentials.

2. **Ticket Booking**:
   - Book tickets for available trains.
   - Automatic seat allocation based on availability.

3. **Train Management**:
   - Add, update, and delete train schedules.
   - Manage train routes and timings.

4. **Cancellation**:
   - Cancel booked tickets with automatic refund calculations.

5. **Inquiry System**:
   - Check train schedules, availability, and ticket prices.
   - View booking history for registered users.

6. **Database Features**:
   - **Joins**: Efficiently retrieve data from multiple tables using SQL JOINs for complex queries like fetching user bookings, train schedules, and availability.
   - **Views**: Predefined SQL views for commonly used queries, such as available trains or user booking history, to simplify query execution.
   - **Triggers**: Automated triggers to handle tasks like updating seat availability after a booking or cancellation.
   - **User Creation**: Support for creating database users with specific roles and permissions to ensure secure access to the system.

7. **Reports**:
   - Generate reports for daily bookings, cancellations, and revenue.

## Limitations

1. **Scalability**:
   - The system is designed for small to medium-sized railway networks and may face performance issues with large datasets.

2. **Concurrency**:
   - Limited support for handling multiple simultaneous transactions, which may lead to data inconsistencies.

3. **User Interface**:
   - This implementation focuses on the database layer and does not include a graphical user interface.

4. **Error Handling**:
   - Minimal error handling for invalid inputs or failed transactions.

## How to Open the Files Using MySQL

1. **Install MySQL**:
   - Ensure that MySQL is installed on your system. You can download it from [MySQL Downloads](https://dev.mysql.com/downloads/).

2. **Open MySQL Workbench**:
   - Launch MySQL Workbench or any other MySQL client tool.

3. **Import the Database**:
   - Open the `.mwb` file:
     - In MySQL Workbench, go to `File > Open Model`.
     - Navigate to the location of the `ORRS.mwb` file and open it.
   - Alternatively, if you have an exported SQL script, use `File > Run SQL Script` to execute the script and create the database.

4. **Review and Modify**:
   - Review the database schema and make any necessary adjustments.

5. **Run Queries**:
   - Use the query editor in MySQL Workbench to interact with the database.

6. **Backup and Restore**:
   - Use the `.mwb.bak` file as a backup. To restore, rename it to `.mwb` and open it in MySQL Workbench.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
