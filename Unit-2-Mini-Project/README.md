# Student Record and Academic Management Platform
## Agile Mini-Project Solution Report — DevOps Unit 2

**Student Name:** Shubham Deshmukh  
**PRN:** 2125UDSM1027  
**Department:** AI & Data Science  
**Training Division:** Careertiq Training & Engineering Division  
**Report Date:** September 6, 2026

---

## 1. Project Overview

The Student Record and Academic Management Platform is intended to help manage student information and academic records in a structured and accessible way. The project applies Agile principles to organize requirements, prioritize features, plan sprints, and track development work.

## 2. Business Problem and Vision

Student-related information can become difficult to maintain when records are managed through disconnected files or manual processes. The proposed platform aims to organize student records and academic information in one system.

**Vision:** Build a reliable, user-friendly platform that supports efficient student record management and academic administration.

## 3. Stakeholder Personas

The project considers the needs of the following stakeholders:

- **Administrator:** Maintains system information and manages access.
- **Faculty Member:** Uses student and academic information for academic activities.
- **Student:** Needs convenient access to relevant personal and academic records.

## 4. Minimum Viable Product (MVP)

The MVP focuses on the essential capabilities required to demonstrate the platform's core value.

- Maintain student records.
- Organize academic information.
- Support authorized access to relevant information.
- Provide a clear and usable interface.
- Validate input and handle errors appropriately.

Additional features can be prioritized after feedback from stakeholders.

## 5. Product Roadmap

The roadmap is organized into incremental stages:

1. Requirement analysis and backlog preparation.
2. MVP planning and interface design.
3. Core student-record functionality.
4. Academic information and validation.
5. Testing, feedback, and improvements.
6. Final review and project documentation.

## 6. Agile Methodology

Agile development delivers work in small increments, encourages collaboration, and adapts to feedback. Scrum is recommended as the primary framework for planning and reviewing project work.

### Scrum Roles

- **Product Owner:** Prioritizes the product backlog and communicates product goals.
- **Scrum Master:** Supports Scrum practices and helps remove impediments.
- **Developers:** Design, implement, test, and deliver increments.

## 7. Project Epics

The product backlog is organized into these seven epics:

1. Student Record Management
2. Academic Information Management
3. User Access and Permissions
4. Search and Record Retrieval
5. Data Validation and Error Handling
6. User Interface and Usability
7. Testing, Quality, and Documentation

## 8. User Stories and Acceptance Criteria

### US-01: Create a Student Record
**User story:** As an administrator, I want to create a student record so that student information can be maintained centrally.

**Acceptance criteria:**
- Required fields are validated.
- Valid information can be saved.
- Invalid input produces a clear error message.

### US-02: View Student Details
**User story:** As an authorized user, I want to view student details so that I can access the required information.

**Acceptance criteria:**
- The selected student's information is displayed clearly.
- Missing or unavailable records are handled appropriately.
- Access is restricted according to permissions.

### US-03: Update Student Information
**User story:** As an authorized administrator, I want to update student details so that records remain accurate.

**Acceptance criteria:**
- Existing information can be edited.
- Changes are validated before saving.
- The updated information is reflected when viewed again.

### US-04: Manage Academic Information
**User story:** As a faculty member, I want academic information to be organized so that it can be reviewed efficiently.

**Acceptance criteria:**
- Academic information is associated with the appropriate student.
- Required values are validated.
- Information is displayed in an understandable format.

### US-05: Search Student Records
**User story:** As an authorized user, I want to search for student records so that I can find information efficiently.

**Acceptance criteria:**
- Search input is validated.
- Matching records are displayed.
- A useful message is shown when no records match.

### US-06: Control User Access
**User story:** As an administrator, I want access to be controlled so that student information is available only to authorized users.

**Acceptance criteria:**
- Access permissions are applied consistently.
- Unauthorized actions are rejected.
- Errors do not expose sensitive information.

### US-07: Validate Data
**User story:** As a system user, I want input validation so that incomplete or incorrect data can be detected.

**Acceptance criteria:**
- Mandatory fields are checked.
- Invalid data is rejected with understandable feedback.
- Valid data can proceed through the workflow.

### US-08: Test and Review the Platform
**User story:** As a project team member, I want core functionality to be tested so that issues can be identified before delivery.

**Acceptance criteria:**
- Important workflows have test cases.
- Defects are recorded and reviewed.
- The team reviews completed work against acceptance criteria.

## 9. Story Points and Prioritized Backlog

Fibonacci story points (1, 2, 3, 5, 8, 13) can be used to estimate relative effort, complexity, and uncertainty.

The Product Owner prioritizes backlog items according to user value, dependencies, risk, and effort. Core record creation, viewing, updating, and validation should be considered before lower-priority enhancements.

Story-point values should be agreed upon by the team during estimation rather than treated as exact hours.

## 10. Sprint Roadmap

### Sprint 1: Planning and Foundation
- Confirm project vision and requirements.
- Create the initial product backlog.
- Define personas and acceptance criteria.
- Prepare the basic design and development plan.

### Sprint 2: Core Student Records
- Implement the essential record workflow.
- Add input validation.
- Review functionality against acceptance criteria.

### Sprint 3: Academic Information and Access
- Organize academic information.
- Apply appropriate access rules.
- Improve search and error handling.

### Sprint 4: Testing and Delivery
- Test core workflows.
- Resolve identified defects.
- Collect feedback and make improvements.
- Complete documentation and final review.

Sprint scope should be adjusted to actual team capacity and progress.

## 11. Scrum Board

A five-column Scrum/Kanban-style board can track work through these stages:

| Backlog | To Do | In Progress | Testing/Review | Done |
|---|---|---|---|---|
| Future work | Selected work ready to start | Work currently being developed | Work awaiting verification | Accepted completed work |

Tasks move across the board as their status changes. Work-in-progress limits can help the team focus on completing tasks instead of starting too many at once.

## 12. Scrum Ceremonies

- **Sprint Planning:** Establish the sprint goal and select work.
- **Daily Scrum:** Inspect progress and identify impediments.
- **Sprint Review:** Demonstrate the increment and gather stakeholder feedback.
- **Sprint Retrospective:** Identify improvements for the next sprint.
- **Backlog Refinement:** Clarify, split, and prioritize upcoming work.

## 13. Agile Framework Comparison

| Framework | Main Focus | Suitable Use |
|---|---|---|
| Scrum | Time-boxed sprints and defined roles | Incremental product development |
| Kanban | Visualizing flow and limiting work in progress | Continuous workflow |
| Extreme Programming (XP) | Engineering practices and frequent feedback | Improving software quality |
| Lean | Reducing waste and maximizing value | Improving process efficiency |
| LeSS | Scaling Scrum across multiple teams | Larger products with multiple teams |
| SAFe | Coordinating Agile work across an enterprise | Large organizations |
| Scrum@Scale | Scaling Scrum using interconnected teams | Multi-team Scrum environments |

## 14. Recommended Approach

Scrum augmented with selected Extreme Programming practices is recommended for this mini-project.

Scrum provides sprint planning, backlog prioritization, reviews, and retrospectives. XP practices such as frequent testing, refactoring, and continuous integration can improve code quality and reduce the risk of defects.

The approach should remain proportionate to the project size and available team resources.

## 15. Deliverables Checklist

- [ ] Project vision and problem statement
- [ ] Stakeholder personas
- [ ] MVP scope and roadmap
- [ ] Product backlog and user stories
- [ ] Acceptance criteria
- [ ] Story-point estimation
- [ ] Sprint plan
- [ ] Scrum board
- [ ] Agile framework comparison
- [ ] Testing and review notes
- [ ] Final project documentation

## 16. Conclusion

This mini-project applies Agile planning to the Student Record and Academic Management Platform. By organizing work into epics, user stories, prioritized backlog items, and sprints, the team can deliver the core functionality incrementally and improve it through testing and stakeholder feedback.

The recommended Scrum approach, supported by selected XP engineering practices, provides a structured way to manage work, review progress, and focus on quality.

---

**Prepared by:** Shubham Deshmukh  
**PRN:** 2125UDSM1027  
**DevOps Unit 2 Mini-Project**
