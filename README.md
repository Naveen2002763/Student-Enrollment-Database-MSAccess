📘 Student Skill Enrollment Database – Microsoft Access Project
This Microsoft Access project manages student data, their enrolled courses, and the skills they've gained. It provides an efficient structure to organize information, perform queries, and generate reports — all in a user-friendly.

🗃️ Tables Used
tblStudents
Contains student records including:
StudentID, FullName, Gender, EnrollmentStatus

tblCourses
Contains course details like:
CourseID, CourseName, CourseType

tblSkills
Tracks student skills including:
SkillID, SkillName, SkillLevel, and associated StudentID

🔍 Queries Created (4)
Overview Query
Joins all three tables to show full details: Student Name, Gender, Course, and Skill info.

Skilled Query
Displays Student Name, Skill Name, and Skill Level.

Status Query
Filters students whose EnrollmentStatus is "Ongoing".

StudentSkillQuery
Shows StudentID, FullName, CourseName, and CourseType.

📝 Forms Developed (3)
Student Form – For entering and viewing student details

Course Form – For course creation and management

Skill Form – For recording student skills

🖨️ Report (1)
A formatted Overview Report has been built using the Overview Query, suitable for printing and summarizing student-course-skill information.

🎯 Project Summary
Built using Microsoft Access (.accdb)

Includes 3 structured tables, 4 functional queries, 3 interactive forms, and 1 summary report

Focused on clean design, easy data entry, and flexible querying

Ready for academic or training-based database use cases


📁 GitHub Folder Structure
Copy
Edit
📦 Student_Skill_Enrollment_DB/
├── Student_Skill_Enrollment_DB.accdb
├── README.md
