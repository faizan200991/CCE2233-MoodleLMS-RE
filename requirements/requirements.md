# System Requirements Specification
## AIU Moodle Learning Management System (LMS)
**Course:** CCE2233 Requirements Engineering
**Semester:** 2, 2025/2026


## Functional Requirements (FR)

| Req ID | Requirement Name | Description |
|--------|-----------------|-------------|
| FR-01 | User Authentication | The system shall allow students, lecturers, and administrators to log in securely using their AIU credentials (username and password). The system shall support session management and automatic logout after a period of inactivity. |
| FR-02 | Course Enrolment Management | The system shall enable programme administrators to enrol and unenrol students into courses. Lecturers shall be able to view the full list of students enrolled in their courses at any time. |
| FR-03 | Course Content Upload | The system shall allow lecturers to upload, edit, organise, and delete course materials including PDF documents, videos, presentations, and external links, within topic-based or week-based course sections. |
| FR-04 | Assignment Submission | The system shall allow students to submit assignments online before specified deadlines. Lecturers shall be able to download submissions, provide written feedback, and record grades against each submission. |
| FR-05 | Online Quiz and Assessment | The system shall enable lecturers to create timed online quizzes with multiple question types (MCQ, short answer, true/false, matching). The system shall automatically calculate and display scores upon submission. |
| FR-06 | Gradebook Management | The system shall maintain a centralised gradebook where lecturers can input, edit, and publish student grades for all assessed activities. Students shall be able to view only their own published grades. |
| FR-07 | Announcement and Messaging | The system shall allow lecturers to post course-level announcements automatically emailed to all enrolled students. The system shall also support internal direct messaging between any users. |
| FR-08 | Discussion Forum | The system shall provide a course-level discussion forum where students and lecturers can create threads, post replies, and engage in academic discussions. Lecturers shall have moderation privileges. |

---

## Non-Functional Requirements (NFR)

| Req ID | Requirement Name | Description |
|--------|-----------------|-------------|
| NFR-01 | Performance | The system shall support a minimum of 500 concurrent users with average page load times not exceeding 3 seconds under normal network conditions, and not exceeding 6 seconds under peak load. |
| NFR-02 | Security | The system shall enforce role-based access control (RBAC) ensuring users can only access resources appropriate to their role. All data transmissions shall be encrypted using HTTPS/TLS. Passwords shall be stored as hashed values. |
| NFR-03 | Availability | The system shall maintain a minimum uptime of 99.5% during the academic semester. Scheduled maintenance windows shall be communicated to users at least 48 hours in advance via system announcements. |
