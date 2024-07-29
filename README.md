# Blood Donation Form 

This repository contains a login and registration form implemented in HTML and PHP. The data will be stored in sql database using Xampp.

## Features

- User login form with fields for username, password, and blood group
- Hidden field to specify the form type
- Basic form validation and submission

## Getting Started

To use this form with XAMPP, follow these steps:

### Prerequisites

1. **XAMPP**: Download and install XAMPP from [the official website](https://www.apachefriends.org/index.html).

2. **PHP**: XAMPP includes PHP, so no additional PHP installation is required.

### Installation

1. **Clone the repository**

   git clone https://github.com/skyneon1/Blood-Donation-Form.git
   
2. **Navigate to the project directory**

   cd Blood-Donation-Form

3. Move the project to XAMPP's htdocs directory

   Copy the contents of your cloned repository into the htdocs directory of your XAMPP installation.

   This directory is typically found at: C:\xampp\htdocs\

   For example, if you cloned your repository into a folder named user-login-form, you should move it to: C:\xampp\htdocs\user-login-form

4. Set up the database

   Open XAMPP Control Panel and start the Apache and MySQL services.
   
   Open your web browser and go to http://localhost/phpmyadmin to access phpMyAdmin.
   
   Create a new database for your project.
   
   Update the connect.php file with your database connection details.


### Usage

  Access the Form

  Open your web browser and navigate to the form page:
  
  arduino
  Copy code
  http://localhost/user-login-form/index.html
  Fill out the Form
  
  Username: Enter your desired username.
  Password: Enter your desired password.
  Blood Group: Select your blood group from the dropdown list.
  Submit the Form
  
  Click the "Submit" button to send the form data. The form will be processed by connect.php.
  
  Customizing
  Form Type: The hidden field formType is set to "signUp" by default. You can modify this field if you need different form types.
  Database Connection: Update the database connection settings in connect.php to match your database credentials.
  Troubleshooting
  Undefined Array Key Warning: If you encounter an "undefined array key" warning, ensure that the form field names in your HTML match those used in your PHP script.
  
  Form Data Handling: Verify that your PHP code is correctly handling the form data and that the form fields are properly named and used.
  
### License
  This project is licensed under the MIT License - see the LICENSE file for details.
  
### Contributing
  Feel free to open issues or submit pull requests for improvements or bug fixes.
