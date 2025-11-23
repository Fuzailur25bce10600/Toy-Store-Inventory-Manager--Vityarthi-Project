Toy Store Inventory Management System

Project Overview

Accurate, real-time inventory oversight is a fundamental challenge in small-scale retail, where stock tracking inefficiency can lead to substantial operational losses. This project provides a direct solution to that critical requirement.

The application functions as a foundational digital ledger, engineered to deliver essential stock management capabilities. It facilitates the immediate creation, systematic updating, and comprehensive reporting of all inventory records.

Core Application Capabilities (Features)

The system is structured around four essential functionalities, ensuring robust control throughout the product lifecycle:

1. Inventory Record Management

Enables the creation of new products within the register.

Provides functionality for the permanent removal of discontinued items.

Offers an option to clear the entire inventory database.

2. Data Inquiry

Facilitates immediate verification of current stock availability.

Instantly retrieves the recorded price associated with the product ID.

Requires a unique product identifier for all data lookup operations.

3. Stock Transaction Processing

Allows for the positive adjustment of quantities upon receiving deliveries.

Permits the negative adjustment of levels following sales transactions.

Ensures all inventory counts are updated in real-time.

4. Comprehensive Reporting

Generates a complete, exhaustive list of all products held.

Systematically displays the ID, Name, Price, and Stock status.

Provides a concise overview of the entire data repository.

Technologies and Tools Utilized

The project's technical stack is minimal, prioritizing the use of core programming fundamentals.

Primary Language: Python 3.

Dependencies: None. The application relies exclusively on built-in Python data structures and native control flows (Dictionaries, Loops).

Deployment Environment: Command-Line Interface (CLI).

Deployment and Execution Protocol

The application relies solely on a standard Python 3 installation for deployment.

Prerequisites

The host system must have Python 3 successfully installed.

1. Code Persistence

Save the Python script as inventory_manager.py.

2. Application Launch

Execute the file from the command line using the following command:

python inventory_manager.py


3. Operational Guidance

Interaction is initiated immediately via the presented menu. Input the numeric option corresponding to the required action (e.g., 1 to add, 0 to exit). The interface operates continuously until system termination is requested.