07 — Technical Analysis

This folder contains the technical analysis and system specifications for the **AspireX — Intelligent Career Readiness & Skills Gap Analysis Platform**.

Purpose

To translate business requirements into technical specifications and support communication between business stakeholders and the proposed development team.

Planned Deliverables

1. API Specifications — Define proposed API endpoints, request and response formats.
2. Business Rules Document — Defines the logic used for skills gap analysis and career readiness assessment.
3. Data Mapping Document — Explains how user, skills, and career data are processed.
4. Requirements Traceability Matrix (RTM)— Links business requirements to system features and test cases.
5. Technical Requirements Document — Describes system integrations, security, and technical constraints.

Key Technical Areas

- User authentication and authorization
- Student profile and skills management
- Career requirements management
- Skills gap calculation logic
- Learning recommendation rules
- Data validation and privacy
- REST API specifications
- Power BI reporting data requirements

 Business Analysis Focus

- Translate business needs into technical requirements.
- Define and document business rules.
- Identify system dependencies and constraints.
- Support communication between business and technical teams.
- Ensure technical specifications align with business objectives.

Tools and Technologies

- Microsoft Word
- Draw.io
- SQL (optional)
- Postman (optional)
- Power BI Desktop
- GitHub
Proposed Skills Gap Rules

- BRULE-001: Users select a target career.
- BRULE-002: Compare current and required skills.
- BRULE-003: Level 0 means missing skill.
- BRULE-004: Below required level means improvement needed.
- BRULE-005: Equal or higher means requirement met.

Skill Levels:
0 = None
1 = Basic
2 = Intermediate
3 = Advanced
Status

Power BI Report Plan

Page 1: Career Overview
- Student count
- Popular career paths

Page 2: Skills Gap Analysis
- Most common missing skills
- Skills gap by career

Page 3: Career Readiness
- Requirements-match score
- Learning progress

Data Source: Synthetic student dataset
Status: Planned
Planned — Technical analysis documents will be added during the project.

## API Requirements

### Overview
AspireX uses proposed REST APIs to support communication between the frontend and backend.

### Proposed API Endpoints

| Endpoint | Method | Description |

| `/api/auth/login` | POST | Authenticate a student |
| `/api/students/profile` | GET | Retrieve student profile details |
| `/api/students/skills` | PUT | Update student skill information |
| `/api/careers` | GET | Retrieve available career paths |
| `/api/skill-gap` | POST | Calculate gaps between current and required skills |
| `/api/recommendations` | GET | Retrieve personalized learning recommendations |
| `/api/progress` | GET | Retrieve student learning progress |

### Note
These APIs are proposed requirements for the AspireX system. They have not yet been implemented or tested.


