# IoTBay – IoT Device Catalogue Management Module

<!-- 
This section documents the IoT device management functionality developed for the IoTBay web application (R1 release).

Module Overview:
- This module allows staff users to create, update, delete, and search IoT device records.
- All users (staff and customers) can view and search devices by name and type.
- The module follows the MVC architecture and connects to a SQLite database via JDBC.

Key Features:
1. Create Device (Staff only)
- Staff can input details such as device name, type, unit price, and stock quantity to add a new IoT device record.

2. Edit Device (Staff only)
- Staff can select an existing device and update any of its details.

3. Delete Device (Staff only)
- Staff can delete existing device records from the catalogue.

4. Search and List Devices (All users)
- Both staff and customer users can search for devices by name or type.
- Device records are displayed in a list format after applying filters.

Technology Stack:
- Java, JSP/Servlets, JDBC, SQLite, MVC Architecture
- GitHub used for version control and collaboration

Notes:
- This module is integrated into the main IoTBay system via the dashboard.
- Role-based access control ensures only staff users can perform write operations on the database.
-->
