# Student Record and Academic Management Platform

## Unit 2 Mini Project — Agile Methodology

**Student Name:** Shubham Deshmukh  
**PRN / Roll No:** 2125UDSM1027  
**Course:** DevOps — Unit 2 (Agile Methodology)  
**Submission Date:** September 6, 2026

---

## 1. Project Overview

The Student Record and Academic Management Platform is designed to streamline higher education institutional operations. It aims to address fragmented record-keeping systems, paper-based attendance tracking, delayed academic reporting, and inadequate access control.

This Unit 2 mini project focuses on Agile product planning, Scrum roles, project epics, user stories, acceptance criteria, product backlog prioritization, sprint planning, Scrum board architecture, and Agile framework comparison.

## 2. Business Problem

Educational institutions may face challenges such as:

- Fragmented student records.
- Manual attendance tracking.
- Delays in academic reporting and result publication.
- Inefficient course registration.
- Inadequate access control and data protection.
- Time-consuming report generation.

The proposed platform aims to centralize academic information and improve administrative efficiency through a unified web-based solution.

## 3. Product Vision

> Develop a secure and user-friendly Student Record and Academic Management Platform that enables educational institutions to efficiently manage student records, attendance, academic performance, course registration, and reporting through a scalable web-based application.

### Mission

Deliver an intuitive, accessible, and scalable platform that digitizes student lifecycles, automates course and attendance handling, and supports academic performance tracking.

### Primary Stakeholders

- University Administrators
- Faculty Members
- Students
- Academic Coordinators
- System Administrators

## 4. Business and System Requirements

### Functional Requirements

- User authentication and profile management.
- Student registration and student search.
- Course enrollment and course assignment.
- Real-time attendance tracking.
- Marks entry and grade calculation.
- Transcript and report generation.
- Notifications for attendance and examination updates.

### Non-Functional Requirements

- Proposed operational availability target of 99.9%.
- Search response time below 2 seconds.
- Role-Based Access Control (RBAC).
- End-to-end data encryption.
- Responsive web design.

These are project requirements and targets, not verified measurements from an implemented application.

## 5. Scrum Roles and Responsibilities

| Scrum Role | Assigned Personnel | Responsibilities |
|---|---|---|
| Product Owner | Shubham Deshmukh | Defines product vision, prioritizes backlog, and establishes acceptance criteria |
| Scrum Master | DevOps Project Lead | Facilitates Scrum ceremonies and helps remove blockers |
| Development Team | Cross-functional engineers | Designs, develops, tests, and supports delivery automation |

## 6. Project Epics

The platform is organized into seven major epics.

| Epic | Module | Key Features |
|---|---|---|
| Epic 1 | Student Management | Registration, profiles, search, updates, and record management |
| Epic 2 | Course Management | Add courses, update course details, and assign students |
| Epic 3 | Attendance Management | Record attendance, view logs, and generate summaries |
| Epic 4 | Marks and Academic Performance | Enter marks, calculate grades, and generate result sheets |
| Epic 5 | Authentication and Security | Login, logout, password reset, sessions, and RBAC |
| Epic 6 | Notifications and Alerts | Attendance alerts, examination notifications, and result announcements |
| Epic 7 | Reporting and Analytics | Student reports, attendance reports, transcripts, and performance analytics |

## 7. User Stories and Acceptance Criteria

### US-01: User Login

**User Story:** As a registered user, I want to log in using my credentials so that I can access my personalized dashboard.

**Acceptance Criteria:**
- Valid credentials provide access to the appropriate dashboard.
- Invalid credentials display an error without exposing sensitive information.
- Sessions expire after the specified period of inactivity.
- The login page meets the planned response-time target.

### US-02: Student Registration

**User Story:** As an administrator, I want to register students with personal and academic details so that their records are maintained centrally.

**Acceptance Criteria:**
- Mandatory fields such as email, PRN, date of birth, and program are validated.
- Duplicate PRN or email entries are rejected.
- A unique Student ID is generated after successful registration.
- A confirmation email is planned upon successful creation.

### US-03: Student Search

**User Story:** As a faculty member or administrator, I want to search students by name, roll number, or department so that I can quickly access their profiles.

**Acceptance Criteria:**
- Search supports autocomplete.
- Results meet the defined response-time target.
- Results can be filtered by department, batch, and status.

### US-04: Record Attendance

**User Story:** As a faculty member, I want to record attendance for assigned lectures so that accurate attendance records are maintained.

**Acceptance Criteria:**
- Faculty can select a course and lecture date or slot.
- The student roster supports Present, Absent, and Late status.
- Saving attendance updates the record and logs a timestamp.
- Attendance summaries can be downloaded.

### US-05: Add Course

**User Story:** As an academic coordinator, I want to add courses with credits and syllabus details so that students can register for them.

**Acceptance Criteria:**
- Course code, title, credits, department, and faculty are captured.
- Course codes must be unique.
- Newly created courses default to Active status.

### US-06: Enter and Calculate Marks

**User Story:** As a faculty member, I want to enter student assessment marks so that grades and result sheets can be generated.

**Acceptance Criteria:**
- Negative marks and marks exceeding the maximum are rejected.
- Grades are calculated using the configured formula.
- Grade distributions can be presented visually.

### US-07: Attendance Alert

**User Story:** As a system administrator, I want alerts when attendance falls below 75% so that timely intervention can occur.

**Acceptance Criteria:**
- The planned alert process runs at the end of each week.
- Notifications are sent to the student and academic advisor.
- An audit record is generated.

### US-08: Generate Reports

**User Story:** As an administrator, I want to generate performance and attendance reports in PDF or Excel format so that official records can be archived.

**Acceptance Criteria:**
- Reports can be filtered by date range, department, and course.
- Export generates a formatted PDF or XLSX file within the specified target time.

## 8. Product Backlog and Story Points

Story points follow the Fibonacci estimation approach described in the project.

| Story Points | Complexity | Example |
|---:|---|---|
| 1 | Very Easy | Text change or simple lookup |
| 2 | Easy | Basic form validation |
| 3 | Moderate | Standard CRUD feature |
| 5 | Difficult | Multi-table query or file export |
| 8 | Very Difficult | Core module or authentication integration |
| 13 | Highly Complex | Complex integration or analytics engine |

### Prioritized Product Backlog

| Priority | User Story / Feature | Story Points | Target Sprint |
|---|---|---:|---|
| High | User login and session management | 5 | Sprint 1 |
| High | Student registration | 5 | Sprint 1 |
| High | Student search | 3 | Sprint 1 |
| High | Record lecture attendance | 8 | Sprint 2 |
| High | Add and update course | 5 | Sprint 2 |
| Medium | Assign students to courses | 5 | Sprint 2 |
| Medium | Enter assessment marks | 8 | Sprint 3 |
| Medium | Attendance and result reports | 5 | Sprint 3 |
| Medium | Low-attendance alerts | 5 | Sprint 3 |
| Low | Academic performance analytics UI | 8 | Sprint 4 |

## 9. Sprint Planning and Release Roadmap

### Sprint 1: Core Foundation and Authentication

- Initialize the Git repository and plan the CI/CD pipeline.
- Design the PostgreSQL schema for user profiles.
- Plan user registration and JWT authentication.
- Build the base dashboard layout.
- Plan unit and integration testing for the authentication API.

**Planned velocity:** 50 story points.

### Sprint 2: Student and Course Management

- Develop student add, update, and search APIs.
- Design the student profile interface.
- Build course creation and update forms.
- Plan student-to-course assignment.
- Validate RBAC permissions for administrators and faculty.

**Planned velocity:** 45 story points.

### Sprint 3: Attendance, Marks, and Reporting

- Develop the faculty attendance entry interface.
- Implement automated grade calculation.
- Plan PDF and Excel report exports.
- Configure low-attendance email alerts.

**Planned velocity:** 40 story points.

### Sprint 4: Analytics

- Plan the academic performance analytics interface.
- Review stakeholder feedback.
- Prioritize improvements for a future release.

## 10. Scrum Board Architecture

The project uses a five-stage workflow:

1. **Backlog:** Features and tasks awaiting prioritization.
2. **To Do:** Tasks selected and ready to begin.
3. **In Progress:** Tasks currently being developed.
4. **Testing / QA:** Tasks undergoing verification.
5. **Completed (Done):** Tasks that satisfy the agreed acceptance criteria.

Example work items include user login, student registration, attendance recording, course creation, marks entry, report generation, database schema migration, automated tests, and CI/CD setup.

## 11. Scrum Ceremonies

### Sprint Planning
The Product Owner presents prioritized backlog items. The team estimates effort, reviews capacity, and defines the Sprint Goal.

### Daily Scrum
A 15-minute meeting where team members discuss:
- What did I complete yesterday?
- What will I work on today?
- What blockers am I facing?

### Sprint Review
The team demonstrates the working software increment and collects stakeholder feedback.

### Sprint Retrospective
The team reviews what went well, what challenges occurred, and which improvements should be implemented in the next Sprint.

## 12. Comparison of Agile Frameworks

| Framework | Main Focus | Suitability for This Project |
|---|---|---|
| Scrum | Iterative Sprints, roles, and ceremonies | High |
| Kanban | Continuous flow and work-in-progress limits | Medium |
| Extreme Programming (XP) | TDD, pair programming, and engineering quality | High as complementary practices |
| Lean Development | Waste reduction and value delivery | Medium |
| Large-Scale Scrum (LeSS) | Scaling Scrum across teams | Low for the initial single-team scope |
| Scaled Agile Framework (SAFe) | Enterprise-scale planning and coordination | Low for the initial scope |
| Scrum@Scale | Scaling coordination across Scrum teams | Low for the initial scope |

### Framework Recommendation

**Scrum**, supported by Extreme Programming practices such as Continuous Integration/Continuous Delivery (CI/CD) and Test-Driven Development (TDD), is selected as the proposed primary methodology.

It provides structured planning, clear responsibilities, iterative delivery, and regular stakeholder feedback.

## 13. Proposed Technology and DevOps Practices

- **Version Control:** Git and GitHub
- **Database:** PostgreSQL
- **Authentication:** JWT-based authentication
- **CI/CD:** GitHub Actions
- **Testing:** Unit and integration testing
- **Future deployment planning:** Docker and related DevOps automation

These technologies are identified in the project plan; their inclusion does not mean that every component has been implemented.

## 14. Expected Outcomes

- Centralized student and academic records.
- More efficient course and attendance management.
- Improved tracking of academic performance.
- Clearer requirements and prioritized development tasks.
- Better collaboration through Scrum roles and ceremonies.
- A structured foundation for iterative software delivery.

## 15. Conclusion

This Unit 2 mini project applies Agile and Scrum practices to the Student Record and Academic Management Platform. It defines the product vision, stakeholder needs, Scrum responsibilities, project epics, user stories, acceptance criteria, prioritized backlog, sprint roadmap, Scrum board, and framework recommendation.

These planning artifacts provide a foundation for future implementation, testing, deployment, and continuous improvement.

---

## Author

**Shubham Deshmukh**  
**PRN:** 2125UDSM1027  
**Course:** DevOps — Unit 2 (Agile Methodology)

---

*This README documents the planned Agile project. Actual implementation status and performance should be updated as development progresses.*
