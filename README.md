# Hotel Management System

## Introduction

The Hotel Management System is a comprehensive software solution designed to streamline and enhance the operations of a hotel or hospitality establishment. This system integrates a range of functionalities to cater to various aspects of hotel management, ensuring smooth and efficient operations.

### Key Features:

1. **Room Booking:** Users can easily book rooms through the system, selecting their preferred room type, check-in/check-out dates, and other preferences.

2. **Complaints Management:** Guests can raise complaints or feedback through the system, allowing hotel staff to address issues promptly and improve guest satisfaction.

3. **Self Checkout:** The system enables users to check out of their rooms independently, reducing waiting times and enhancing convenience for guests.

4. **Room Search:** Users can search for available rooms based on criteria such as room type, occupancy, amenities, and pricing.

5. **User Authentication:** The system provides secure login mechanisms for both employees and administrators, ensuring data privacy and access control.

6. **Employee Management:** Administrators can add new employees, assign roles and responsibilities, and manage staff profiles efficiently.

7. **Maintenance Management:** The system facilitates the management of maintenance tasks, scheduling repairs, and tracking maintenance history for various hotel facilities.

8. **Inventory Management:** Hotel inventory, including supplies, amenities, and equipment, can be managed effectively through the system, ensuring optimal stock levels and inventory control.

Overall, the Hotel Management System is a comprehensive solution that empowers hotels to deliver superior guest experiences, streamline operations, and optimize resource utilization.

## System Requirements

1. MySQL
2. MySQL Workbench
3. `mysql-connector-java-8.30.jar` file (for database connection)
4. Java
5. Eclipse (Java IDE)
6. Java Swing
7. `jcalendar-1.4.jar` file
8. `jdatepicker-1.3.4.jar` file
9. `rs2xml.jar` file
10. Windows Builder

## Installation Steps

1. Install MySQL, MySQL Workbench, Java, Eclipse, Java Swing, and Windows Builder.
2. Download `mysql-connector-java-8.30.jar`, `jcalendar-1.4.jar`, `jdatepicker-1.3.4.jar`, and `rs2xml.jar` files.
3. Open `FinaldumpFDB` dump and import it into MySQL Workbench. Name the imported database as `hotelmanagementsystem`.
4. In Eclipse, go to Help > Install New Software > New > Add > Archive, then select the Windows Builder repository and install it.
5. In Eclipse, import the project named `HotelManagementSystem-Master`.
6. Right-click on the project folder, go to Properties > Java Build Path > Libraries > Add External Jars, and add the following jar files:
   - `mysql-connector-java-8.30.jar`
   - `jdatepicker-1.3.4.jar`
   - `rs2xml.jar`
   - `jcalendar-1.4.jar`
7. Apply and close the build path settings.
8. Navigate to `HotelManagementSystem/src` > `hotelmanagementsystem` package in the project.
9. Run the file `HotelManagementSystem.java` as a Java application.

## Notes

- Ensure MySQL server is running before executing the application.
- Make sure all jar files are correctly added to the project build path for seamless execution.
- For any issues or queries, refer to the project documentation or contact the developer.

## ER Diagram

![ERDiagram](https://github.com/Rohit061199/FDBProject/assets/73810251/b894433d-ece2-4cc1-8ec2-40973702266c)

