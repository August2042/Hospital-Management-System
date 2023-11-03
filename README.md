 # Hospital Management System

This is a simple Hospital Management System developed using Java, JDBC, and Swing. The system is designed to manage various aspects of a hospital, including Doctor management, Patient management, Pharmacy management, and Lab Test management.

## Features

The Hospital Management System consists of the following modules:

1. **Doctor Module**
   - **Add Doctor**: Allows you to add a new doctor to the system.
   - **View Doctor**: Allows you to view the details of all doctors in the system.
   - **Update Doctor**: Enables you to update the information of an existing doctor.
   - **Fire Doctor**: Permits you to remove a doctor from the system.

2. **Patient Module**
   - **Add Patient**: Allows you to add a new patient to the system.
   - **View Records**: Allows you to view the medical records of all patients.
   - **Update Patient**: Enables you to update the information of an existing patient.
   - **Discharge Patient**: Permits you to discharge a patient from the hospital.

3. **Pharmacy Module**
   - **Add Medicine**: Allows you to add a new medicine to the pharmacy inventory.
   - **View Stock**: Allows you to view the current stock of medicines in the pharmacy.
   - **Update Medicine**: Enables you to update the details of a medicine.
   - **Remove Medicine**: Permits you to remove a medicine from the inventory.

4. **Lab Test Module**
   - **Add Lab Test**: Allows you to add a new lab test to the system.
   - **View Lab Test**: Allows you to view the details of all available lab tests.
   - **Remove Lab Test**: Enables you to remove a lab test from the system.
   - **Update Lab Test**: Permits you to update the information of an existing lab test.

## Installation and Usage

1. **Prerequisites:**
   - Java Development Kit (JDK)
   - MySQL Database

2. **Database Setup:**
   - Create a MySQL database for the Hospital Management System.
   - Configure the database connection in the `DBConnection.java` file.

3. **Run the Application:**
   - Compile and run the `HospitalManagementSystem.java` file to start the application.
   - Follow the on-screen instructions to navigate through different modules and perform actions.

## Project Structure

The project's source code is organized as follows:

- `HospitalManagementSystem.java`: The main application entry point.
- `DBConnection.java`: Manages the database connection.
- `DoctorModule.java`: Implements the Doctor module functionality.
- `PatientModule.java`: Implements the Patient module functionality.
- `PharmacyModule.java`: Implements the Pharmacy module functionality.
- `LabTestModule.java`: Implements the Lab Test module functionality.

## About Swing and JDBC

This application uses Swing for the graphical user interface (GUI) components, and JDBC for database connectivity. Swing provides a user-friendly and interactive interface, while JDBC ensures that data is stored and retrieved from the database.

## Contributors

- [August Kumar]
 

## License

This Hospital Management System is open-source and released under the [Your License] License. You can find the license details in the `LICENSE` file.

Please feel free to contribute to and enhance this system. If you encounter any issues or have suggestions for improvement, don't hesitate to open an issue or create a pull request. Thank you for using the Hospital Management System!
