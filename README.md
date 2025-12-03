# Art Gallery Management System

This project provides a simple database structure for managing an art gallery using MySQL. It includes tables for artists, art pieces, customers, transactions, orders, payments, and customer phone numbers. The database is designed to allow users to manage and query relevant information about artwork, artists, and sales.

## Database Tables

- **artist** – Stores details about each artist, including name, address, qualification, and contact.
- **art** – Contains information about each art piece such as style, price, title, year made, discount, and links to the artist.
- **customer** – Keeps customer details including name, address, contact information, and purchase history.
- **transaction** – Records each transaction made, including the amount and date.
- **order1** – Links customers to art and transactions through orders.
- **payment** – Records payment details for bookings, including payment method.
- **CustomerPhone** – Stores multiple phone numbers for customers.

## Example SQL Operations

- Table creation for managing data entities.
- Inserting and querying artist, art, customer, transaction, order, payment, and customer phone records.
- Performing aggregate queries like SUM and AVG on sales data.
- Joining tables to retrieve related records (e.g., customer purchase history, cross-referencing art with customers).
- User management commands for database access control.

## Sample Aggregation/Join Queries

- List total purchases by each customer.
- Retrieve the average purchase history.
- Find customers and their purchased artwork.
- Select all customers/orders based on different join operations.

## Getting Started

1. **Create the database:**
2. **Create the tables as defined above.**
3. **Insert sample data as needed for testing and demonstration (see `DBMS.txt`).**
4. **Run query samples to explore and manage the data.**

## Features

- Supports adding new artists, artworks, customers, transactions, and orders.
- Includes queries for common statistical and string operations.
- Demonstrates basic and advanced SQL features like joins, unions, create/drop users, and permission grants.

## Module Summary Poster
<img src="https://github.com/arshad-perampalli/Art_Gallery_Management_System/blob/main/Art%20gallery%20poster.png?raw=true" width="400"/>


## Usage

Use the `.sql` statements within any MySQL monitor or GUI tool. The schema is flexible for learning and adapting to more complex gallery management needs.

