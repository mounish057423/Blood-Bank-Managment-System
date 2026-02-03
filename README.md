# Blood Bank Management System

A modern Java Swing application for managing blood bank operations, including donor registration, blood donations, requests, inventory, and user/admin management. This project is designed to streamline the workflow of a blood bank and provide an intuitive interface for both users and administrators.

---

## Features
- **Donor Registration & Management:** Register new donors and manage their profiles.
- **Blood Donation Tracking:** Record and track blood donations with donor details and donation history.
- **Blood Stock Management:** Monitor and update available blood stock by blood group and location.
- **Blood Request System:** Allow users to request blood and admins to approve or reject requests.
- **User Authentication:** Secure login and password management for users and admins.
- **Search & Reporting:** Search donations, requests, and generate reports for analysis.
- **Admin Dashboard:** Centralized control for managing users, blood stock, and requests.
- **Excel Integration:** Export and manage data using Apache POI for Excel files.

## Technologies Used
- Java (JDK 17)
- Swing (GUI framework)
- Maven (build & dependency management)
- Apache POI (Excel file handling)
- PostgreSQL (database)

## Project Structure
```
├── src/main/java/           # Java source files (Admin, Mainframe, Donation, Requests, etc.)
├── pom.xml                  # Maven project configuration
├── target/                  # Compiled classes and build output
├── ...                      # Other project files and resources
```

## Getting Started
1. **Clone the repository:**
   ```sh
   git clone https://github.com/mounish057423/Blood-Bank-Managment-System.git
   ```
2. **Open in your IDE:**
   Use IntelliJ IDEA, Eclipse, or VS Code with Java support.
3. **Install dependencies:**
   Ensure you have JDK 17 and Maven installed.
4. **Build the project:**
   ```sh
   mvn clean install
   ```
5. **Run the application:**
   - From your IDE: Run the `Mainframe` class.
   - Or from terminal:
     ```sh
     mvn exec:java -Dexec.mainClass="Mainframe"
     ```

## Database Setup
- The application connects to a PostgreSQL database for persistent storage.
- Update the database connection details in `sqlconnect.java`:
  ```java
  String url = "jdbc:postgresql://localhost/bloodbank";
  String username = "postgres";
  String password = "your_password";
  ```
- Create necessary tables as per your requirements.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request. For major changes, open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.

## Contact
For questions or support, please open an issue on the repository.
