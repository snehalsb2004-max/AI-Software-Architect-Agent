# AI Agent Prompts


---

# Overview

The **prompts** folder contains the prompt templates used by the **AI Software Architect Agent**. Each prompt is designed for a specific AI agent responsible for performing a dedicated task in the software architecture planning process.

Instead of embedding prompts directly inside the source code, all prompts are stored separately in this folder. This modular approach makes the system easier to maintain, update, and improve without modifying the application logic.

Each prompt acts as an instruction set that guides the Large Language Model (LLM) in generating structured and consistent outputs.

---

# Purpose

The purpose of this folder is to centralize all prompt templates used by the AI agents.

This approach provides several benefits:

- Easy prompt management
- Better maintainability
- Version control
- Prompt reusability
- Faster experimentation
- Separation of business logic and AI instructions

---

# AI Agent Workflow

```
                    User
                      │
                      ▼
        Requirement Analysis Agent
                      │
                      ▼
          Architecture Agent
                      │
                      ▼
         Database Design Agent
                      │
                      ▼
               API Agent
                      │
                      ▼
            Security Agent
                      │
                      ▼
         Documentation Agent
                      │
                      ▼
            Roadmap Agent
                      │
                      ▼
          Final Project Report
```

---

# Prompt Design Principles

Every prompt in this folder follows the same structure to maintain consistency.

Each prompt contains:

- Agent Overview
- Purpose
- Objectives
- Responsibilities
- Input
- Output
- Workflow
- Prompt Template
- Example Input
- Example Output
- Error Handling
- Future Improvements

---

# Folder Structure

```
prompts/

│── README.md
│── RequirementAgent.md
│── ArchitectureAgent.md
│── DatabaseAgent.md
│── APIAgent.md
│── SecurityAgent.md
│── DocumentationAgent.md
│── RoadmapAgent.md
```

---

# Description of Each Agent

## Requirement Analysis Agent

Analyzes the user's software idea and generates:

- Functional Requirements
- Non-Functional Requirements
- User Stories
- Constraints
- Assumptions

---

## Architecture Agent

Analyzes project requirements and recommends:

- Software Architecture Pattern
- System Components
- Communication Strategy
- Technology Recommendations
- Scalability Plan

---

## Database Design Agent

Designs an optimized relational database by generating:

- Entities
- Attributes
- Relationships
- SQL Scripts
- Normalized Database Schema

---

## API Agent

Generates REST API specifications including:

- Endpoints
- HTTP Methods
- Request Body
- Response Body
- Status Codes
- Authentication Strategy

---

## Security Agent

Provides security recommendations such as:

- Authentication
- Authorization
- Encryption
- JWT
- RBAC
- API Security
- Secure Coding Practices

---

## Documentation Agent

Automatically generates:

- Software Requirement Specification
- Software Design Document
- API Documentation
- User Manual
- Developer Guide
- Final Project Report

---

## Roadmap Agent

Creates the software development roadmap including:

- Project Timeline
- Development Phases
- Milestones
- Deliverables
- Sprint Planning

---

# Prompt Lifecycle

```
User Input

↓

Prompt Selection

↓

Prompt Processing

↓

Large Language Model

↓

AI Response

↓

Validation

↓

Structured Output

↓

Next AI Agent
```

---

# Prompt Engineering Guidelines

The prompts are designed according to the following principles:

- Clear Instructions
- Context Awareness
- Role Definition
- Structured Output
- Step-by-Step Reasoning
- Error Prevention
- Reusability

---

# Integration with Backend

The Spring Boot backend reads these prompt templates and sends them to the configured Large Language Model (LLM), such as OpenAI GPT or Google Gemini.

Typical workflow:

1. User submits project details.
2. Backend selects the required prompt.
3. Prompt is combined with user input.
4. Request is sent to the LLM.
5. AI-generated response is validated.
6. Output is forwarded to the next AI agent.

---

# Advantages

- Modular architecture
- Easier prompt updates
- Better version control
- Improved maintainability
- Consistent AI responses
- Cleaner backend code
- Easy experimentation with prompt versions

---

# Future Improvements

Future versions of this folder may include:

- Prompt Versioning
- Dynamic Prompt Selection
- Multi-language Prompts
- Context-aware Prompt Optimization
- Prompt Evaluation Metrics
- Automatic Prompt Testing
- Prompt Performance Comparison

---

# Best Practices

- Keep prompts modular.
- Use descriptive filenames.
- Maintain version history.
- Test prompts before deployment.
- Document every prompt update.
- Avoid hardcoding prompts inside Java code.
- Store reusable templates in this folder.

---

# Status

**Current Status:** Planning Phase

The prompt templates are currently being designed. During implementation, these prompts will be integrated into the Spring Boot backend and used by the AI agents to communicate with Large Language Models such as OpenAI GPT or Google Gemini.

---

# Author

**Snehal Bhosale**

B.Tech – Computer Science (Artificial Intelligence & Data Science)

Pimpri Chinchwad University

---

# License

This documentation is part of the **AI Software Architect Agent** project and is intended for educational and research purposes.
