# WAREHOUSE MANAGEMENT SYSTEM

## Screenshots
Screenshots demonstrating the working of the system are included in the uploaded project report.

## About the Project
This project focuses on building a comprehensive Warehouse Management System (WMS) that efficiently manages warehouse operations such as adding, removing, and updating products, managing employee and customer information, and facilitating product orders. It leverages object-oriented principles, role-based access, and fundamental C++ concepts along with data structures like stacks and queues to organize warehouse operations.

## Project Overview
The system allows multiple roles—Admin, Manager, Employee, and Customer—to perform their respective functions efficiently. Products are managed with stacks and queues for organized storage. Employees and customers can interact with the warehouse based on role-specific permissions, while the admin has full control over managing users and generating reports. The use of classes, inheritance, and operator overloading ensures a modular and maintainable codebase.

## How the Project Works
- **Product Management:** Products are added, updated, or removed from the warehouse using object-oriented classes like `Item` and `Warehouse`.
- **Order Processing:** Customers can view products and place orders. Product quantities are updated in real time to reflect stock availability.
- **Employee and Customer Management:** Admin can add, remove, and update employee and customer details using `Admin` and `Manager` classes.
- **Stack and Queue Operations:** Products can be managed using `Stack` and `Queue` classes, allowing LIFO and FIFO operations for storage flexibility.
- **Role-Based Access:**
  - **Admin:** Full control, including user management and report generation.
  - **Manager/Employee:** Manage products and perform stack/queue operations.
  - **Customer:** View products and place orders.
- **Workflow:**
  1. Users select their role from Admin, Employee, or Customer.
  2. Admin authentication grants access to user and product management menus.
  3. Employees can add, update, or remove products and use stack/queue operations.
  4. Customers can browse products and place orders with real-time inventory updates.
  5. Reports are generated to summarize warehouse inventory, employees, and customer details.

## Key Features
- Comprehensive warehouse inventory management
- Role-based access for Admin, Manager, Employee, and Customer
- Order processing with real-time stock updates
- Employee and customer management
- Stack and queue implementation for organized product storage
- Detailed reporting for inventory, employees, and customers
- Interactive command-line interface

## Tools & Technologies Used
- **C++** for overall implementation
- **VS Code / IDE of choice** for development
- **Standard Template Library (STL):** vectors, stacks, queues
- **Object-Oriented Programming Concepts:** classes, inheritance, operator overloading

## Project Goals
- Efficiently manage warehouse operations
- Implement role-based access and modular design
- Support real-time order and inventory management
- Enable organized product handling using data structures

## Applications
- Warehouse and inventory management for businesses
- Role-based employee and customer management
- Order processing and stock control
- Educational use for learning data structures and OOP concepts

## Conclusion
This Warehouse Management System provides a robust and efficient way to handle warehouse operations. By leveraging object-oriented principles, role-based access, and stack/queue data structures, the system ensures smooth and organized management of products, employees, and customers. The modular design allows easy maintenance and potential scalability for larger warehouse operations.

## Problems Faced
- Handling inheritance errors during implementation required careful debugging.
- Integrating C++ concepts in a meaningful, real-world application posed design challenges.
