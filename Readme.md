# NodeJS-AssignMentors-Task

This documentation provides details about the Assign-Mentor API, implemented using Node.js and Express. This API allows you to manage mentors and students, assign mentors to students, change mentors, and retrieve mentor-student relationships.

**Packages installed:**

Express: npm install express

Cors: npm install cors

Dotenv: npm install dotenv

Mongoose: npm install mongoose

1. **POST Create Mentor**

URL: https://nodejs-assignmentors-task.onrender.com/api/mentor/create

Description: Creates a new mentor with details about the mentor.

Method: POST


2. **POST Create Student**

URL: https://nodejs-assignmentors-task.onrender.com/api/student/create

Description: Creates a new student with details about the student.

Method: POST

3. **GET Display All Mentors**

URL: https://nodejs-assignmentors-task.onrender.com/api/mentor/all-mentors

Description: Retrieves and displays the list of all mentors.

Method: GET

4. **GET Display all Students**

URL: https://nodejs-assignmentors-task.onrender.com/api/student/all-students

Description: Retrieves and displays the list of all students.

Method: GET

5. **PUT Assign students to mentor**

URL: https://nodejs-assignmentors-task.onrender.com/api/mentor/assign/6680f09fc337ff677de93afc

Description: Assigns multiple students to a specific mentor.

Method: PUT

6. **PUT Change mentor for one student**

URL: https://nodejs-assignmentors-task.onrender.com/api/mentor/change-mentor/6680f0c0c337ff677de93b00

Description: Changes the mentor for a specific student and records the previous mentor.

Method: PUT

7. **GET Display students of the mentor**

URL: https://nodejs-assignmentors-task.onrender.com/api/mentor/students/6680f081c337ff677de93afa

Description: Retrieves and displays the list of all students assigned to a specific mentor.

Method: GET

8. **GET Previous Mentor**

URL: https://nodejs-assignmentors-task.onrender.com/api/mentor/previous-mentors/6680f0c0c337ff677de93b00

Description: Retrieves and displays the list of previous mentors for a specific student.

Method: GET


**All the APIs are well documented using Postman Documentation and Published -** [published Postman API documentation link](https://documenter.getpostman.com/view/34879950/2sA3duGYtr)

**Deployed my server in Render -** [Deployed API Render URL](https://nodejs-assignmentors-task.onrender.com)

**Note: Since I'm deployed the apis in render's free tier, The initial request is taking time, Please wait little longer for initial request**