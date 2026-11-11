# Parent-School Communication and Management System

## Project Overview

Design and develop a web-based system that connects school administrators, teachers, parents, and students. The system is intended for schools in Rusizi District, Rwanda, and will support communication, academic monitoring, attendance tracking, announcements, and school administration.

## Essential Features

### Module 1: User Registration and Authentication

1. Register parent accounts.
2. Register teacher accounts.
3. Register school administrator accounts.
4. Create student accounts.
5. Provide secure login.
6. Provide logout.
7. Support forgotten-password requests.
8. Allow users to reset passwords.
9. Allow users to change passwords.
10. Manage user profiles.

### Module 2: Parent Management

11. Register parents.
12. Update parent information.
13. Delete parent accounts.
14. View parent profiles.
15. Store parent phone numbers.
16. Store parent email addresses.
17. Link parents to their children.
18. Allow a parent to be linked to multiple children.
19. View a parent's children and their information.
20. Manage emergency contact details.

### Module 3: Student Management

21. Register students.
22. Update student information.
23. Delete student records.
24. View student profiles.
25. Assign students to classes.
26. Generate student admission numbers.
27. Upload student profile pictures.
28. View student academic history.
29. Manage student transfer records.
30. Search students by name or registration number.

### Module 4: Teacher Management

31. Register teachers.
32. Update teacher information.
33. Delete teacher accounts.
34. Assign teachers to classes.
35. Assign subjects to teachers.
36. View teacher profiles.
37. Manage teacher contact information.
38. View the students assigned to each teacher.
39. Manage teacher availability.
40. Generate teacher reports.

### Module 5: Communication and Messaging

41. Support parent-to-teacher messaging.
42. Support teacher-to-parent messaging.
43. Support parent-to-administration messaging.
44. Support group messaging.
45. Send private messages.
46. Receive messages.
47. Reply to messages.
48. Delete messages.
49. View message history.
50. Show message delivery and read status.

### Module 6: School Announcements

51. Publish school announcements.
52. Update announcements.
53. Delete announcements.
54. View announcements.
55. Send announcements to all parents.
56. Send announcements to selected classes.
57. Send announcements to individual parents.
58. Highlight important announcements.
59. Schedule announcement publication dates.
60. Archive old announcements.

### Module 7: Attendance Management

61. Record daily student attendance.
62. Mark students present.
63. Mark students absent.
64. Mark students late.
65. Record excused absences.
66. View daily attendance reports.
67. View monthly attendance reports.
68. Notify parents when a student is absent.
69. Calculate student attendance percentages.
70. View attendance history.

### Module 8: Academic Performance Management

71. Upload examination results.
72. Enter student marks.
73. Update examination marks.
74. View student results.
75. Calculate total marks.
76. Calculate average marks.
77. Calculate student grades.
78. Generate report cards.
79. View academic performance history.
80. Notify parents when results are published.

### Module 9: Homework and Assignments

81. Allow teachers to create homework.
82. Allow teachers to upload assignments.
83. Set assignment deadlines.
84. Assign homework to specific classes.
85. Allow parents to view their children's homework.
86. Allow students to view assigned homework.
87. Upload assignment documents.
88. Submit completed assignments.
89. Allow teachers to mark submitted assignments.
90. Notify parents about missing homework.

### Module 10: School Fees and Payments

91. Record school fees.
92. View student fee balances.
93. Record payments.
94. Generate payment receipts.
95. View payment history.
96. Track unpaid school fees.
97. Send fee payment reminders.
98. Generate school fee reports.
99. View outstanding balances.
100. Notify parents when payments are received.

### Module 11: Notifications and Events

101. Send SMS notifications.
102. Send email notifications.
103. Display in-system notifications.
104. Notify parents about school meetings.
105. Publish a school event calendar.
106. Notify parents about examination dates.
107. Notify parents about holidays.
108. Send emergency notifications.
109. Notify parents about disciplinary incidents.
110. Allow parents to confirm receipt of notifications.

### Module 12: Reports and System Administration

111. Generate student reports.
112. Generate parent reports.
113. Generate teacher reports.
114. Generate attendance reports.
115. Generate academic performance reports.
116. Generate school fee reports.
117. Manage user roles and permissions.
118. View system activity logs.
119. Back up school data.
120. Restore backed-up school data.

## Main Users and Permissions

- **Administrator:** Manages users, classes, teachers, students, announcements, permissions, and reports across the system.
- **Teacher:** Manages attendance, marks, assignments, announcements, and communication with parents for assigned classes and subjects.
- **Parent:** Views linked children's results, attendance, fees, homework, announcements, and messages.
- **Student:** Views personal results, homework, attendance, school announcements, and messages.

## Recommended Technology Stack

| Component | Suggested technology |
| --- | --- |
| Frontend | HTML, CSS, JavaScript, and Bootstrap |
| Backend | PHP |
| Database | MySQL |
| Local development server | XAMPP |
| Notifications | SMS and email integrations |
| Reports | PDF generation library |
| Security | Password hashing and role-based permissions |

## Suggested Database Tables

`users`, `parents`, `teachers`, `students`, `classes`, `subjects`, `parent_students`, `messages`, `announcements`, `attendance`, `examinations`, `results`, `assignments`, `submissions`, `school_fees`, `payments`, `notifications`, `events`, `activity_logs`, and `backups`.

## Recommended Minimum Viable Product

Start with these core capabilities, then expand the system module by module:

1. Login and registration.
2. Parent management.
3. Student management.
4. Teacher management.
5. Parent-teacher messaging.
6. School announcements.
7. Student attendance.
8. Academic results.
9. Homework management.
10. Notifications.