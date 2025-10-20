This is a website built for university, where there are mainly 3 class of user i.e. student, staff, admin. Prospective student can register themselves. Staff can see their academic stuffsand admin can bring changes to program, module leader, access list of students registered and many more.

1. At first extract the folder 'our_project'.Copy 'web_app_project' from the 'our_project' folder to htdocs/.

2. Create a new database in your PhpMyAdmin called 'student_course_hub.sql'. The name should be exactly same.

3. Then, import the database provided inside 'our_project' folder, in PhpMyAdmin's newly created database.
Database name should be exactly same and no other database with same name should exist in PhpMyAdmin.

4. Now open the folder web_app_project in VS Code or any IDE you are using.

5. GO to your browser and type only localhost/web_app_project. You can view our project. If there is any error called 'Not Found', probably you couldn't set it up. Check your folder in htdocs, if it is web_app_project/web_app_project

6. I personally added the "Web Layout.docx" for providing our initial blueprint for the project.

7. I have also provided my separately done work in a seaprate fzip file called "my_particular_tasks.zip" for better understanding of my contribution to the project.

8. Password to enter student, staff and admin account are provided below:

"Student": 
email: tahiru@gmail.com
password: tahiru

"Staff":
email: fati@gmail.com
password: test123

"Admin": 
email: admin@test.com
password: test123

Project Structure
web_app_project/
├── app/              # Controllers, views, and core logic
├── config/           # Database connection (db.php)
├── database/         # SQL file for importing 
student_course_hub
├── public/           # Assets (CSS, JS, images)
├── index.php         # Entry point and router
├── README.md         # Setup and documentation


Security: password_hash/verify, PDO prepared statements, CSRF tokens, htmlspecialchars(), session-gated admin.
Mailing list: unique (ProgrammeID, Email) + Active unsubscribe.
UI: Staff menu nests Admin inside it (see header). Responsive & accessible.

Built by-- Nusrat-Frontend
          Sanjana-Backend
          Nabil- Backend+ Security
