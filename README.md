# Jigawa State Polytechnic SIWES Management System

## Project Presentation

Good day everyone. My project is the **Jigawa State Polytechnic SIWES Management System**. It is a web-based portal designed to organize the main activities involved in the Students Industrial Work Experience Scheme, commonly known as SIWES.

SIWES connects a student's academic training with practical experience in a workplace. Managing that process can involve several people and records: students need to register and report their activities, supervisors need to follow students' progress, and the SIWES administration needs to review placements and keep track of the programme. This portal brings those tasks together online so each person can use one place to see the information relevant to their role.

To explain how it works, I will follow the process from a student's point of view. A student first creates an account using their details and confirms their email address. After signing in, the student submits a placement request and can check whether it is awaiting review, approved, or rejected. When the placement is approved, the student can see the placement information and assigned supervisor, upload the required documents, and begin recording their industrial experience in the digital logbook.

The logbook is used throughout the placement. The student writes an entry for each programme week and submits it through the portal. This gives the student a record of their activities and gives the assigned supervisor a way to monitor submissions. The student dashboard also provides access to placement status, documents, announcements, and, when available, the final grade.

The supervisor uses a separate dashboard to view their assigned students. They can review students' logbook progress, record supervision visits, and enter an assessment and grade. The grade is made up of several assessment areas and a written note. Grading becomes available from Week 35 of the SIWES programme, so the system follows the programme's timing rather than allowing grades to be submitted at any point.

The administrator oversees the programme from the admin dashboard. They can review placement requests, manage student and supervisor records, maintain organization information, publish announcements, monitor supervision visits, and view programme reports. Reports summarize information such as student progress, logbook submissions, grades, and placements, and can be printed or saved as a PDF using the browser's print feature.

In short, the system follows the SIWES process from registration and placement through weekly reporting, supervision, and assessment. Each role has its own dashboard, but the information is connected so students, supervisors, and administrators can follow the same programme from their respective responsibilities.

## Workflow at a Glance

1. **Student account:** The student registers, confirms their email, and signs in.
2. **Placement request:** The student submits a placement request and checks its status while it is reviewed.
3. **Placement preparation:** Once approved, the student can view the placement and assigned supervisor and upload required documents.
4. **Weekly logbook:** The student records and submits their activities for each SIWES week.
5. **Supervision:** The supervisor reviews assigned students, follows their logbook progress, and records visits.
6. **Assessment:** At the appropriate point in the programme, the supervisor submits the student's assessment and grade.
7. **Administration and reporting:** The SIWES administrator manages programme records, communicates announcements, and reviews or exports reports.

## User Roles

### Student

The student portal provides access to placement status, weekly logbook submissions, required documents, announcements, and grade information. A logbook entry is submitted once for its week, so students should review it before submission. Uploading another document of the same type replaces the previous file.

### Supervisor

The supervisor portal focuses on assigned students. Supervisors can review progress, check logbook submissions, record supervision visits, and submit final assessments and grades. Grading is locked until the programme reaches Week 35.

### Administrator

The admin portal supports placement approvals and the management of students, supervisors, and placement organizations. Administrators can also publish announcements, review supervision visits, and use reports to monitor activity across the programme.

## Technical Overview

The portal's user interface is built with **HTML, CSS, and JavaScript**. HTML defines the pages and forms, CSS controls their layout and appearance, and JavaScript responds to user actions and loads or submits information.

The application uses **Supabase** for authentication and backend data. In everyday terms, authentication checks who has signed in, while the backend stores and returns the records used by the portal. When a user submits a placement request or logbook entry, JavaScript sends that information to Supabase; when a dashboard opens, it requests the records that belong to that user and role. The project has separate pages for the student, supervisor, and admin dashboards, and the sign-in process directs users to the dashboard for their account role.

The dashboards also use **Chart.js** to display selected programme information as charts. The reports can be printed or saved as a PDF through the browser's built-in print workflow. Together, these technologies provide an interactive website connected to an online authentication and data service, without requiring users to install a separate application.

## Main Benefit

The main benefit of the SIWES Management System is that it makes the programme's progress easier to record and follow. Students can manage their SIWES records online, supervisors can monitor and assess assigned students, and administrators can oversee placements and programme activity from one system.
