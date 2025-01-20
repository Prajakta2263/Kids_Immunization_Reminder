# Kids Immunization Reminder - Project

## Overview
This project is a **Kids Immunization Reminder** application that helps parents track and manage their child's vaccination schedule. It includes both the frontend and backend components.

## Project Structure
Arrange the files as below (Unzip the backend file)
<pre>
Kids_Immunization_Reminder/
├── frontend/                     # React frontend files
│   ├── public/                   # Public assets (index.html, etc.)
│   ├── src/                      # Source code (components, views, etc.)
│   ├── package.json              # Frontend dependencies and scripts
│   ├── .gitignore                # Git ignore file
│   └── README.md                 # Frontend specific instructions
├── backend_part.zip              # Zip file containing backend code
└── README.md                     # Project overview and instructions
</pre>


### Frontend
- The **`frontend/`** folder contains the React application. It has all the necessary components, views, and logic for the user interface.

### Backend
- The **`backend_part.zip`** file contains the backend code necessary for the application's functionality. Please follow the steps below to set it up.

## Setting Up the Backend

1. **Unzip the `backend_part.zip`** file:
   - After downloading the project, locate the `backend_part.zip` file inside the project directory.
   - Unzip this file into a new folder called **`backend/`**. 

2. **Install Java and Maven** (if not installed):
- Ensure that **Java JDK** and **Maven** are installed on your machine.
- You can check if Java is installed with:
  ```bash
  java -version
  ```
- You can check if Maven is installed with:
  ```bash
  mvn -version
  ```
- If not installed, you can download them from:
  - [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
  - [Maven](https://maven.apache.org/download.cgi)

3. **Navigate to the `backend/` folder** and build the Java project:
- Open the terminal and navigate to the `backend` directory:
  ```bash
  cd backend
  ```
- If using Maven, run the following to build the project:
  ```bash
  mvn clean install
  ```

4. **Run the Java backend server**:
- After building, you can run the backend server using:
  ```bash
  mvn spring-boot:run
  ```
- The backend should now be running on `http://localhost:8080` (or whichever port is specified in your application).

## Setting Up the Frontend (React)

1. **Navigate to the Frontend Folder**:
- Go to the `frontend` directory.
```bash
cd frontend
```

2. **Install Frontend Dependencies**:
- npm install
- npm start to run
- The frontend should now be running on http://localhost:3000


##  

Thank you for checking out the **Kids Immunization Reminder** project! This app is designed to help parents keep track of their children's vaccination schedules and ensure timely reminders for each vaccine.


Feel free to fork this repository and contribute to it. If you have any suggestions or improvements, please open an issue or submit a pull request. Contributions are always welcome!


Happy coding, and good luck with the project! 🚀


