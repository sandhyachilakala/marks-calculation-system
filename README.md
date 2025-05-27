 Student Marks Calculation System
 
1. Project Content:
   
     The Student Marks Calculation System is an online platform designed to simplify the process of recording, calculating, and presenting student academic results. Faculty members can securely log in to input internal assessment scores (from three midterm exams) and external exam marks. Students can access their accounts to view computed grades and final report cards. The system is suitable for educational institutions such as schools, colleges, and universities, and it supports functionalities for both faculty and student users.

3. Project Code:
   
The project is composed of the following key components:

app.py: Serves as the main backend application handling server-side logic.

index.html: Acts as the landing page, providing login and registration functionalities.

student-dashboard.html: Interface for students to access their marks and view their academic performance.

faculty-dashboard.html: Interface for faculty to input internal and external marks.

report-card.html: Displays the final grades and overall report card for students.

student_mark.sql: Defines the database schema and includes queries for data management.

4. Key Technologies:
   
Frontend: Built using HTML, CSS, and JavaScript to create responsive and interactive user interfaces.

Backend: Developed with Python Flask, managing application logic and server-side processing.

Database: Utilizes MySQL to store and manage data related to students, faculty, and marks.

APIs: Implements RESTful endpoints to handle actions performed by students and faculty.

Session Management: Uses localStorage to retain logged-in user information on the client side.

5. Description:
   
This system provides the following functionalities:

Faculty Features:

Faculty members can log in to input internal marks (Mid1, Mid2, Mid3) and external marks for each student.

Internal marks are calculated by selecting the best two midterm scores and averaging them (each midterm is out of 25).

Final marks are determined by adding the internal average (out of 50) to the external exam marks (out of 75).

Grades are assigned based on the computed final marks.

Faculty can also:

Insert both internal and external marks.

View external marks for all students.

Access a list of all their assigned students.

Student Features:

Students can log in to:

View a subject-wise breakdown of internal, external, and final marks.

See the assigned grade for each subject.

Access overall total and average marks.

5.  Output:

    Homepage --

  ![image](https://github.com/user-attachments/assets/8904cf91-2a66-493d-a741-2840f4ba182b)

 Faculty Dashboard --

  ![image](https://github.com/user-attachments/assets/aec9cb13-27dd-4b97-ab94-86abf12e1a6b)

Student Dashboard --

![image](https://github.com/user-attachments/assets/8c747890-a185-4972-ab75-93656a2f4ce3)

Insertion of internal marks --

![image](https://github.com/user-attachments/assets/90ce8f1d-00a1-46c1-baf1-f3d12192d1b4)

Final Report Card --

![image](https://github.com/user-attachments/assets/32bbc748-1a96-449e-bec2-dd29631e7ee2)

6.  Further Research:
   
PDF Report Cards: Allow students to download report cards as PDFs.

JWT Authentication: Use secure token-based login instead of localStorage.

Performance Charts: Add visual analytics to track student progress.

Responsive Design: Make the UI mobile-friendly.

Subject Feedback: Let students give feedback on each subject
