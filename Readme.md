# Register and Login Form with MySQL Database in Java NetBeans

This project is a register and login form implemented in Java NetBeans that allows users to register with their information, including name, email, mobile number, country, gender, date of birth, password, retype password, and address. The form includes complete validation to ensure data integrity and accuracy.

## Features

- **Registration Form**: Users can input their information in the provided fields.
- **Form Validation**: The form validates user input to ensure data correctness.
  - Name field only allows alphabetic characters.
  - Mobile field only allows 10-digit numbers.
- **Date Restriction**: Users can select the date of birth up to today's date; future dates are disabled.
- **MySQL Database Integration**: User registration data is stored in a MySQL database.
- **Login Functionality**: Users can log in using their registered credentials.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

    git clone https://github.com/ms-maheswari/RegisterAndLogin_using_JAVA_and_Mysql.git
   

2. Import the project into Java NetBeans.
3. Set up MySQL database:
    - Create a MySQL database.
    - Update the database connection settings in the project to match your MySQL configuration.
4. Build and run the project in Java NetBeans.

## Usage

1. Open the application in Java NetBeans.
2. Fill out the registration form with your information. 
3. Click the "Register" button to register.
4. Once registered, you can log in using your credentials on the login page.
5. After successful login , you can redirect to home page


# Download KGradientPanel Jar
  

- [KGradientPanel Jar](https://raw.githubusercontent.com)
- [MySQL Connector/J](https://dev.mysql.com/downloads/connector/j/)
- [JCalendar](http://www.java2s.com/Code/Jar/j/Downloadjcalendarjar.htm)

This is Register page where you have to enter all necessary details
![Registration Form](Screenshots/Register.png)

After creating account you have to login here
![Login](Screenshots/Login.png)

Once login is done, you will redirect to this home page
![Home](Screenshots/Home.png)

