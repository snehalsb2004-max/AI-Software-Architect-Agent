# Activity Diagram

---

# Overview

The Activity Diagram represents the complete workflow of the **AI Software Architect Agent**. It illustrates how the system processes user requests, coordinates multiple AI agents, and generates software design artifacts such as software architecture, database schema, REST APIs, security recommendations, technical documentation, and a project development roadmap.

Unlike structural diagrams that focus on system components, the Activity Diagram emphasizes the sequence of actions performed by both the user and the system. It helps developers understand the execution flow from the beginning of the process to the final output.

The diagram serves as a blueprint for implementing the application's business logic and ensures that all major activities are properly connected and executed in the correct order.

---

# Purpose

The primary purpose of the Activity Diagram is to model the dynamic behavior of the AI Software Architect Agent.

It provides a visual representation of how different activities are executed, how decisions are made, and how data moves through the system.

This diagram helps developers understand the logical flow before implementation begins and reduces confusion during development.

---

# Objectives

The Activity Diagram has the following objectives:

- Represent the complete workflow of the application.
- Illustrate interactions between the user and AI agents.
- Show the sequence of system activities.
- Identify decision points within the workflow.
- Support software design and implementation.
- Improve collaboration among development team members.
- Provide documentation for future maintenance.

---

# Why Activity Diagram is Important

The Activity Diagram is one of the most useful UML diagrams because it focuses on the business process rather than the software structure.

It helps developers answer questions such as:

- What happens after the user submits project requirements?
- Which AI agent is executed first?
- How does information move from one agent to another?
- What happens if the input is invalid?
- When is the final report generated?

By answering these questions visually, the Activity Diagram simplifies complex workflows and improves communication between developers and stakeholders.

---

# Workflow Description

The workflow begins when the user accesses the application and creates a new software project.

The user provides project details, including the project name, description, preferred technology stack, functional requirements, and non-functional requirements.

The system validates the submitted information before forwarding it to the Requirement Analysis Agent.

The Requirement Analysis Agent extracts and organizes the project requirements and passes the structured information to the Architecture Agent.

The Architecture Agent recommends an appropriate software architecture, such as Layered Architecture or Microservices.

The Database Design Agent then creates the database schema based on the identified entities and relationships.

The API Agent generates REST API endpoints for communication between the frontend and backend.

The Security Agent analyzes the system and recommends authentication, authorization, encryption, and secure coding practices.

The Documentation Agent combines all generated outputs into technical documentation.

Finally, the Roadmap Agent prepares a project development roadmap, including milestones, sprint planning, and estimated timelines.

The generated reports are presented to the user, who can review and download the project documentation.

---

# Activity Flow

```text
Start

↓

User Login

↓

Create New Project

↓

Enter Project Requirements

↓

Validate Input

↓

Requirement Analysis Agent

↓

Architecture Agent

↓

Database Design Agent

↓

API Agent

↓

Security Agent

↓

Documentation Agent

↓

Roadmap Agent

↓

Generate Final Report

↓

Display Results

↓

Download Documentation

↓

End
```

---

# Major Activities

## User Authentication

The user signs in to the application using secure authentication.

Output:

- Authenticated session
- User dashboard

---

## Project Creation

The user creates a new software project by entering project details.

Inputs include:

- Project Name
- Project Description
- Functional Requirements
- Non-Functional Requirements
- Preferred Technologies

---

## Requirement Analysis

The Requirement Analysis Agent analyzes the project description and identifies:

- Functional Requirements
- Non-Functional Requirements
- Business Objectives
- User Stories
- Constraints

---

## Architecture Generation

The Architecture Agent recommends an appropriate software architecture based on the project requirements.

Possible outputs include:

- Layered Architecture
- Microservices
- Event-Driven Architecture
- MVC Architecture

---

## Database Design

The Database Design Agent designs the database by generating:

- Entities
- Attributes
- Relationships
- Primary Keys
- Foreign Keys
- SQL Scripts

---

## API Generation

The API Agent creates RESTful APIs.

Generated information includes:

- API Endpoints
- HTTP Methods
- Request Body
- Response Format
- Status Codes
- Authentication Requirements

---

## Security Analysis

The Security Agent recommends:

- JWT Authentication
- Role-Based Access Control (RBAC)
- HTTPS
- Password Hashing
- Input Validation
- Secure Coding Practices

---

## Documentation Generation

The Documentation Agent prepares:

- Software Requirement Specification (SRS)
- Software Design Document (SDD)
- API Documentation
- Database Documentation
- User Manual
- Developer Guide

---

## Roadmap Generation

The Roadmap Agent creates:

- Development Phases
- Sprint Planning
- Milestones
- Timeline
- Deployment Plan

---

## Report Generation

The application combines all outputs into a final downloadable report.

Supported formats:

- PDF
- Markdown
- DOCX

---

# Decision Points

The workflow includes several decision points.

### Input Validation

If the project description is incomplete, the system requests additional information before proceeding.

### Architecture Selection

The Architecture Agent selects the most suitable architecture based on project complexity.

### Security Requirements

The Security Agent determines the appropriate security mechanisms depending on the application type.

---

# AI Agents Involved

| AI Agent | Responsibility |
|-----------|----------------|
| Requirement Analysis Agent | Analyze project requirements |
| Architecture Agent | Generate software architecture |
| Database Design Agent | Create database schema |
| API Agent | Generate REST APIs |
| Security Agent | Recommend security strategies |
| Documentation Agent | Generate technical documentation |
| Roadmap Agent | Create development roadmap |

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| Java 21 | Backend Development |
| Spring Boot | Application Framework |
| Spring AI | AI Integration |
| React.js | Frontend Development |
| MySQL | Database Management |
| OpenAI / Gemini | Large Language Model |
| Maven | Dependency Management |
| Git & GitHub | Version Control |
| Docker | Deployment |

---

# Advantages

- Clearly represents the workflow of the application.
- Helps developers understand business logic.
- Simplifies implementation planning.
- Improves communication between stakeholders.
- Reduces development errors.
- Supports future maintenance and enhancements.

---

# Limitations

- Large workflows can become difficult to visualize.
- The diagram requires updates whenever the workflow changes.
- It does not describe the internal implementation of each component.

---

# Future Improvements

Future versions of the Activity Diagram may include:

- Parallel execution of AI agents.
- Real-time collaboration workflows.
- Cloud deployment processes.
- Continuous Integration/Continuous Deployment (CI/CD) workflow.
- Monitoring and logging activities.
- Error recovery and retry mechanisms.

---

# References

1. OMG Unified Modeling Language (UML) Specification
2. IEEE Software Engineering Standards
3. Software Engineering – Ian Sommerville
4. Clean Architecture – Robert C. Martin
5. Spring Boot Documentation

---

# Document History

| Version | Date | Description |
|----------|------|-------------|
| 1.0 | August 2026 | Initial Activity Diagram documentation |

---

# Author

**Snehal Bhosale**

B.Tech – Computer Science (Artificial Intelligence & Data Science)

Pimpri Chinchwad University

---

# Related Diagrams

- Use Case Diagram
- Class Diagram
- Sequence Diagram
- ER Diagram
- Deployment Diagram

These diagrams complement the Activity Diagram by describing different aspects of the AI Software Architect Agent system.
