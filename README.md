# LearnSphere360
LearnSphere360 is a Spring Boot–based Student Management System (SMS) that provides a complete API backend for managing students, subjects, attendance, and users (admins, faculty, students).

It is designed as a backend API layer that can be integrated with a frontend (e.g., Angular at http://localhost:4200) to build a complete academic management solution.

🚀 Features

✔ Manage Students – add, update, delete, and fetch details
✔ Manage Subjects – add, update, delete, and fetch subjects
✔ Track Attendance – record daily attendance with subject & date
✔ User Management – login, register, and manage users (Admin/Faculty/Student)
✔ Role-based functionality (future scope)

🏗️ Tech Stack

Backend: Spring Boot

Database: MySQL (configurable in application.properties)

Language: Java (8/11/17 compatible)

API Type: RESTful APIs

Frontend Integration: Angular / React

📡 API Endpoints
👩‍🎓 Student

GET /student/get-all-students

POST /student/add-student

GET /student/get-student-by-id/{id}

PUT /student/update-student

DELETE /student/delete-student/{id}

📚 Subject

GET /subject/get-all-subjects

POST /subject/add-subject

GET /subject/get-subject-by-id/{id}

PUT /subject/update-subject

DELETE /subject/delete-subject/{id}

📝 Attendance

GET /attendance/get-all-attendance-records

GET /attendance/get-attendance-by-date-subjet/{date}/{subjectId}

POST /attendance/take-attendance

👩‍🏫 User

POST /user/login-user

POST /user/register-user

GET /user/get-user-by-username/{username}

GET /user/get-all-user

GET /user/get-all-admin

GET /user/get-all-faculty

PUT /user/update-user

DELETE /user/delete-user-by-username?username={username}

👨‍💻 Author

Developed by Nilesh Wankhede
 🚀
