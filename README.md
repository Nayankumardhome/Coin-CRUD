# Coin CRUD Application

![Coin Animation](https://media.giphy.com/media/3oKIPuL57n0T03JmSc/giphy.gif)

This project is a simple CRUD (Create, Read, Update, Delete) application for managing coins. Built with J2EE, Hibernate, HTML, and CSS, it showcases basic operations and serves as a foundation for learning CRUD principles. Additionally, the application supports bulk coin management using a CSV file.

## Project Description
- **Developed** a robust platform for managing coins with comprehensive **CRUD (Create, Read, Update, Delete)** functionalities.
- Implemented database operations using **Hibernate ORM** to ensure efficient and secure data management.
- Enhanced scalability by incorporating bulk operations through **CSV file uploads**, enabling the addition of new coins or updating quantities of existing coins seamlessly.
- **Optimized performance** by leveraging Hibernate's caching and query optimization features.
- **Designed and developed** a user-friendly interface using **HTML and CSS**, enabling intuitive interactions for coin management.

## Features
- Add new coins to the system.
- View a list of all coins.
- Edit coin details.
- Delete coins.
- Upload a CSV file:
   - **New coins**: Add to the database.
   - **Existing coins**: Increase their quantity

## Technologies Used
- **Backend**: Java, Hibernate
- **Frontend**: HTML, CSS

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Nayankumardhome/Coin-CRUD.git

2. Open the project in your favorite IDE (e.g., IntelliJ IDEA or Eclipse).
3. Build and run the application.

## CSV File Upload Functionality
- The application supports uploading a CSV file for managing coin inventory.
- **Workflow:**
   1. Upload a CSV file with coin details.
   2. If a coin is **new**, it will be added to the database.
   3. If a coin **already exists**, its quantity will be increased.
