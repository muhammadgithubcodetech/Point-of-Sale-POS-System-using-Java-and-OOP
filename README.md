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

```bash
mvn compile
mvn exec:java -Dexec.mainClass="com.mycompany.mavenproject12.oop_project"
