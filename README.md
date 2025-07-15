# Point-of-Sale-POS-System-using-Java-and-OOP
This is a simple Point of Sale (POS) application developed using Java, Swing for the graphical user interface, and object-oriented programming (OOP) principles. It supports inventory management, transaction logging, and receipt generation, all within a file-based data structure.

This project was created to:

- Practice and apply core OOP principles in Java.
- Build a functional desktop POS application using Swing.
- Understand file I/O for data persistence (products, users, transactions).
- Demonstrate a structured, GUI-driven application using real-world logic.

## Features

- Add, edit, and delete products
- Inventory management via `products.dat`
- Generate and store receipts in `receipts.txt`
- Track transactions in `transactions.dat`
- Basic user interface using Java Swing
- File-based persistence (no external database required)

## Technologies Used

- Java (JDK 17+)
- Swing (Java's built-in GUI toolkit)
- Object Serialization for data storage
- Maven for project build and dependency management

## Project Structure

- PointofSaleUsingOOP/
├── oop_project.java # Main application file (includes GUI and backend logic)
├── pom.xml # Maven build configuration
├── products.dat # Serialized product inventory
├── transactions.dat # Serialized transaction logs
├── receipts.txt # Human-readable transaction summaries
├── users.txt.txt # User data file (filename may be corrected to users.txt)


## How to Run

1. Ensure you have Java JDK 17+ and Maven installed.
2. Navigate to the project directory.
3. Compile and run the program using:


OOP Concepts Demonstrated

    Encapsulation: Fields are kept private with public getters/setters.

    Abstraction: Separation of data handling logic (Product, Inventory) from UI logic.

    Serialization: Products and transactions are saved as .dat files using Java's object serialization.

    GUI Handling: Built using Swing, includes user interaction through buttons, dialogs, and forms.

Improvements and Ideas

    Separate each class into its own file for better modularity

    Add role-based user login (admin vs cashier)

    Implement reports (daily sales, top products)

    Replace file storage with a lightweight database (like SQLite or H2)

    Add unit tests for core business logic




```bash
mvn compile
mvn exec:java -Dexec.mainClass="com.mycompany.mavenproject12.oop_project"



Disclaimer

This project is built for educational purposes only. It is a simplified POS system and not intended for production use.


Developed by: Muhammad Shah
