# Requirement Analysis Agent

## Overview

The Requirement Analysis Agent is responsible for understanding the user's project description and converting it into structured software requirements. It acts as a Business Analyst in the software development lifecycle.

---

## Responsibilities

- Analyze user requirements
- Identify project objectives
- Generate Functional Requirements
- Generate Non-Functional Requirements
- Create User Stories
- Detect assumptions and constraints
- Validate requirement completeness

---

## Input

Example:

Project Name:
Hospital Management System

Description:
Develop a web-based application for managing patient records,
doctor appointments, billing, pharmacy, and laboratory services.

---

## Expected Output

### Functional Requirements

- User Login
- Patient Registration
- Appointment Scheduling
- Billing
- Reports

### Non Functional Requirements

- Secure authentication
- High availability
- Scalability
- Fast response time

---

## Prompt Template

You are a Senior Business Analyst with 15 years of experience.

Your task is to analyze the software project requirements and generate:

1. Functional Requirements
2. Non Functional Requirements
3. User Stories
4. Assumptions
5. Constraints

Provide the output in markdown format.

---

## Future Improvements

- Requirement validation
- Duplicate requirement detection
- Requirement prioritization

---

## Workflow

User Input

↓

Requirement Analysis

↓

LLM

↓

Structured Requirements

↓

Send to Architecture Agent

---

## Status

Planned
