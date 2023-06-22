# Students-Practical-Training-Management-System
This is a web project utilizing PHP, JavaScript, and CSS. It is a project I am working on with my teammates for the web programming subject in my second year. The system consists of three roles: Coordinator, Student, and Admin.

Students' Practical Training Management System:
The system encompasses three types of users: admin, student, and coordinator. In this system, students are required to apply for practical training sessions by completing a form. The coordinator then approves or rejects the applications based on the availability of the requested organization. As the admin responsible for managing the website and database, you have already set up the database with user information, including their usernames, passwords, and user levels. The following is an example of the system flow:

i) All users must log in using the provided username and password. Incorrect logins will be rejected through user verification (using session).

ii) The admin has the ability to add new users, as well as edit and delete information of existing users. Coordinators and students can only edit their own information on their respective profile pages. Editable information should not include the Identification ID. User level determines the extent of data manipulation, such as insert, update, and delete operations.

iii) Students can apply for practical training sessions by filling out the necessary information in a form and submitting it for approval. Data manipulation operations include insert, update, and delete.

iv) Coordinators can view applications and approve or reject them based on the availability of the requested organization. Data manipulation operations include insert, update, and delete.

v) Students can view the results of their applications.

vi) Coordinators can view sorted reports, such as alphabetically, on all students' practical training records. Students can only view reports on their own records. User level determines the access rights to view data, including sorting and searching, and retrieving data from multiple tables.

vii) The admin can access all pages, while coordinators and students have limited access to specific pages. For example, only the admin can add new users, so that page is accessible only to the admin. User level determines the accessibility of pages through session management.

To run this project, you need to set up XAMPP, start the Apache and MySQL servers, and move the project folder to xampp/htdocs. Access the project by running "localhost/(folder's name)" in any browser.

Firstly, create a user in localhost with the username "WPproject" and the password "abc123". If you prefer to use a different username and password, you can modify it in the PHP file.

Next, access "http://localhost/Students-Practical-Training-Management-System/create_db.php" to create the database in phpMyAdmin.

Then, import the TABLE.sql file into phpMyAdmin.

Finally, you can enjoy using the system with the following login details for each role:

Login details:
1. Admin
   username: jacklyn
   password: jacklyn@123
2. Coordinator
   username: eunice
   password: eunice@123
3. Student
   username: yuxuan
   password: yuxuan@123

   username: theresa
   password: theresa@123
