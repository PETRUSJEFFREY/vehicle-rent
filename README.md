The **Vehicle Renting Management System** SQL project is a medium-level relational database application designed to manage the rental operations of a vehicle rental business. It allows for efficient tracking of vehicles, customers, and rental transactions using structured SQL tables and queries. This system is ideal for small to mid-sized businesses that offer cars, trucks, or bikes for rent.

The database schema consists of three primary tables: **Customers**, **Vehicles**, and **Rentals**. The `Customers` table stores information such as the customer's name and the date they joined. The `Vehicles` table maintains records of available vehicles, including model, type, year of manufacture, and how many units are available. The `Rentals` table acts as a bridge between customers and vehicles, recording which customer rented which vehicle, along with rental and return dates.

The project includes sample data and various SQL queries to demonstrate its functionality. Users can retrieve all available vehicles, check customer rental histories, and manage inventory levels by updating the number of available units when a vehicle is rented or returned. Referential integrity is maintained through foreign keys linking rentals to customers and vehicles, ensuring consistency and accuracy in data relationships.

This project highlights essential database concepts such as **data normalization, foreign key constraints, join operations**, and **data manipulation commands** (INSERT, UPDATE, DELETE). It is a practical implementation suitable for academic purposes, resume projects, or prototyping real-world vehicle rental systems.

The project can be extended further by integrating features like payment tracking, vehicle maintenance logs, dynamic pricing, or customer ratings. Additionally, it can be connected to a front-end interface or backend service using technologies like Python Flask, PHP, or Node.js for a full-stack application.

Overall, this SQL project demonstrates how structured data storage and operations can support core business functions in a vehicle rental company.
