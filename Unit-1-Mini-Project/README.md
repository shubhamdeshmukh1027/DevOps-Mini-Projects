# Enterprise Student Record & Academic Management Platform

**Unit 1 Mini Project — Design Thinking & Product Planning**

**Student Name:** Shubham Deshmukh  
**PRN:** 2125UDSM1027  
**Course:** DevOps — Unit 1  
**Training Division:** Careertiq Training & Engineering Division

---

## 1. Executive Summary

The Enterprise Student Record and Academic Management Platform is a proposed cloud-native software solution designed to simplify academic administration in higher education institutions.

The platform aims to manage student admissions, course registration, attendance, examinations, and result processing through a centralized system.

This Unit 1 project focuses on domain understanding, human-centered Design Thinking, stakeholder personas, functional and non-functional requirements, product planning, and repository structure initialization.

## 2. Project Objectives

- Understand the challenges of manual academic record management.
- Apply human-centered Design Thinking methodology.
- Identify stakeholders and their requirements.
- Define functional and non-functional requirements.
- Plan a Minimum Viable Product (MVP).
- Establish a modular repository structure following DevOps practices.

## 3. Programming vs Software Product Engineering

| Dimension | Programming / Coding | Software Product Engineering |
|---|---|---|
| Primary Goal | Writing executable code | Building scalable and maintainable solutions |
| Scope | Individual functions and scripts | Full software development lifecycle |
| Success Metric | Code correctness | User adoption, availability, performance, and business outcomes |
| Mindset | How do I write this function? | What problem are we solving for users? |

## 4. Manual Operational Bottlenecks and Proposed Solutions

| Operational Bottleneck | Proposed Solution | Expected Outcome |
|---|---|---|
| Paper-based attendance registers | Automated attendance logging | Reduced attendance processing time |
| Manual result processing | Database-driven grading and calculations | Faster result generation |
| Physical course registration slips | Self-service course registration portal | Reduced queues |
| Missing or damaged academic records | Centralized database, access controls, and audit logs | Improved record integrity |

The outcomes are targets and expectations, not measured results from an implemented system.

## 5. Design Thinking Methodology

The project follows five stages of Design Thinking:

1. **Empathize:** Understand the challenges faced by students, faculty, and academic administrators.
2. **Define:** Identify operational delays, data errors, and fragmented record management as key problems.
3. **Ideate:** Explore solutions such as GPA calculators, course registration portals, attendance alerts, and digital transcripts.
4. **Prototype:** Plan wireframes for the Student Dashboard, Faculty Grading Portal, and Admin Analytics Panel.
5. **Test:** Validate navigation and task completion before backend development.

## 6. IBM Design Thinking and IBM Loop

### Core Principles

- **Focus on User Outcomes:** Prioritize improvements that make academic tasks easier for users.
- **Restless Reinvention:** Continuously refine the product using feedback and usage observations.
- **Diverse Empowered Teams:** Encourage collaboration between product managers, UX designers, DevOps engineers, and system architects.

### IBM Loop: Observe → Reflect → Make

- **Observe:** Study user interactions and administrative bottlenecks.
- **Reflect:** Analyze findings, review metrics, and prioritize improvements.
- **Make:** Design, develop, test, and improve the solution.

## 7. Stakeholder Analysis and User Personas

| Stakeholder | Primary Objectives | Challenges | Proposed Features |
|---|---|---|---|
| Student | Register for courses and track attendance and GPA | Queues, delayed results, missing records | Responsive portal, transcripts, notifications |
| Faculty | Submit grades and monitor attendance | Manual grade entry and calculation errors | Bulk grade entry and attendance dashboard |
| Academic Administrator | Maintain records and generate reports | Fragmented data and manual audits | Analytics dashboard, report export, access controls |

## 8. Requirements Engineering Specification

### 8.1 Functional Requirements

- **FR-01 Authentication and RBAC:** Secure access for administrators, faculty, students, and examination staff.
- **FR-02 Student Registration:** Student onboarding, profile updates, and document verification.
- **FR-03 Course Registration:** Course selection, seat availability validation, and prerequisite checking.
- **FR-04 Attendance Engine:** Attendance logging, percentage calculation, and low-attendance alerts.
- **FR-05 Examination and Results:** Grade entry, GPA/CGPA calculation, and digital transcript generation.

### 8.2 Non-Functional Requirements

- **NFR-01 Security:** Password hashing, secure session management, and HTTPS/TLS encryption.
- **NFR-02 Performance:** A proposed target of sub-500 ms response time for searches and API queries under a load of 5,000 concurrent users.
- **NFR-03 Scalability and Availability:** Containerized deployment, horizontal scaling, and a proposed 99.99% uptime target.
- **NFR-04 Maintainability:** Modular architecture and infrastructure automation using tools such as Terraform and Ansible.

These are proposed requirements and targets, not verified performance measurements.

## 9. Product Vision

> To deliver a cloud-native, automated, and secure Academic Management Platform that eliminates manual administrative friction, unifies student lifecycle records, and empowers higher education institutions with real-time academic analytics.

## 10. Minimum Viable Product (MVP)

The initial release is planned to include:

- Student registration
- Role-based authentication
- Course enrollment
- Basic attendance logging
- Result generation

Advanced features such as AI-based grade prediction and third-party fee payment gateways are deferred to a later phase.

## 11. Product Engineering Roadmap

1. Domain analysis, Design Thinking, and requirements specification.
2. UI/UX prototyping, database schema design, and Git architecture setup.
3. Agile backlog grooming and sprint planning.
4. Core application development and backend APIs.
5. Docker containerization and GitHub Actions CI/CD.
6. Infrastructure provisioning with Terraform and configuration management with Ansible.
7. Kubernetes deployment, monitoring with Prometheus/Grafana, and continuous improvement.

## 12. Proposed Technology and DevOps Practices

- **Version Control:** Git and GitHub
- **CI/CD:** GitHub Actions
- **Containerization:** Docker
- **Orchestration:** Kubernetes
- **Infrastructure as Code:** Terraform
- **Configuration Management:** Ansible
- **Monitoring:** Prometheus and Grafana
- **Application Components:** Frontend, backend, database, and automated tests

These technologies form the proposed roadmap; their inclusion does not imply that implementation is complete.

## 13. System Architecture and Repository Structure

The proposed project structure supports modular development, documentation, testing, and future DevOps automation.

```text
Unit-1-Mini-Project/
├── README.md
├── docs/
│   └── Unit-1-Project-Document.docx
├── app/
│   ├── modules/
│   ├── database/
│   └── tests/
├── .github/
│   └── workflows/
├── docker/
├── kubernetes/
├── terraform/
├── ansible/
└── monitoring/
```

Directories can be added as the project progresses. The application and automation components are proposed structure, not necessarily implemented components.

## 14. Expected Outcomes

- Reduced dependence on paper-based academic processes.
- Easier access to academic information.
- More efficient course registration and result processing.
- Better access control for sensitive student records.
- A foundation for scalable and automated academic management.

## 15. Conclusion

This Unit 1 mini project establishes the foundation for the Enterprise Student Record and Academic Management Platform through domain analysis, Design Thinking, stakeholder analysis, requirements engineering, MVP planning, and repository design.

The next phases can build on this planning work to develop prototypes, implement application features, and introduce DevOps automation.

---

## Author

**Shubham Deshmukh**  
**PRN:** 2125UDSM1027  
**Course:** DevOps — Unit 1  
**Training Division:** Careertiq Training & Engineering Division

---

*This document describes the proposed design and product plan. Features and performance targets should be validated during implementation and testing.*
