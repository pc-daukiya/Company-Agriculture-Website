# Company Agriculture Web Project

## Project Overview
This is a web application project related to agriculture, designed to provide information and services such as soil data analysis, soil testing, and user login/logout functionality. The project appears to be built using PHP, HTML, CSS, and SQL, and is intended to be run on a local server environment such as XAMPP.

## Project Structure

- **After_Login/**  
  Contains pages accessible after user login, including about, contact, soil data, and soil test pages.

- **Before_Login/**  
  Contains public pages accessible before login, such as about, contact, soil data, and soil test pages.

- **css/**  
  Stylesheets for the main site.

- **Data_Soil_samples/**  
  Contains styles and PHP scripts related to submitting soil sample data.

- **faqs/**  
  Contains FAQ related pages and database connection scripts.

- **images/**  
  Contains image assets used throughout the website.

- **Login_Logout/**  
  Contains scripts for user authentication including login, signup, and logout.

- **SQL Files**  
  - `databasekic.sql`  
  - `location_dynamic.sql`  
  These files likely contain database schema and data for the application.

- **index.html**  
  The main landing page of the website.

## Setup and Usage

1. Install [XAMPP](https://www.apachefriends.org/index.html) or a similar local server environment that supports PHP and MySQL.

2. Place the project folder inside the `htdocs` directory of XAMPP.

3. Import the SQL files (`databasekic.sql` and `location_dynamic.sql`) into your MySQL database using phpMyAdmin or the MySQL command line.

4. Configure database connection settings in the PHP files if necessary (e.g., in `faqs/db_connection.php`).

5. Start Apache and MySQL services from the XAMPP control panel.

6. Access the project in your browser at `http://localhost/Project-5-Company Agriculture/`.

## Features

- User authentication system (login, signup, logout).
- Soil data submission and analysis.
- Separate content for logged-in and guest users.
- FAQ section for user support.

## Notes

- Ensure your PHP environment has the necessary permissions to read/write files and connect to the database.
- Modify database connection details as per your local setup.
- The project uses standard web technologies and can be extended or customized as needed.

## Contact

For any questions or support, Contact to me: prakash18052006@gmail.com

## License

This project is for practice purposes only. It is not intended for commercial use or distribution.
