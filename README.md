# Advanced-Software-Design--University-course-registration-reengineering
Advanced Software Design project demonstrating legacy system assessment, optimization, microservices reengineering, security improvements, and validation strategies.

# University Course Registration System Reengineering

## Overview

This project presents the analysis, optimization, and reengineering of a legacy University Course Registration System as part of an Advanced Software Design course.

The original system is a monolithic application that experiences performance bottlenecks, database inconsistencies, security vulnerabilities, and scalability limitations during peak enrollment periods.

The proposed solution redesigns the system into a modern microservices architecture while incorporating software optimization techniques, security engineering, DevSecOps practices, and comprehensive testing strategies.

---

## Objectives

- Analyze the legacy monolithic architecture
- Identify technical and operational issues
- Optimize database and application performance
- Redesign the system using Microservices
- Improve system security and reliability
- Design API communication between services
- Propose a DevSecOps CI/CD pipeline
- Validate the solution using testing and performance metrics

---

## Existing System

The legacy application contains:

- Authentication
- Course Enrollment
- Payment Processing
- Academic Records
- Notifications

All modules share a single application and database, resulting in:

- Poor scalability
- Tight coupling
- Slow performance
- Database deadlocks
- Security weaknesses
- Difficult maintenance

---

## Proposed Solution

The redesigned architecture separates the application into independent microservices:

- Authentication Service
- Enrollment Service
- Payment Service
- Notification Service
- Academic Record Service

Each service owns its own database and communicates through an API Gateway and an Event Bus.

---

## Technologies & Concepts

- Software Reengineering
- Microservices Architecture
- REST APIs
- API Gateway
- Event-Driven Architecture
- Domain-Driven Design (DDD)
- JWT Authentication
- Role-Based Access Control (RBAC)
- Multi-Factor Authentication (MFA)
- Redis Caching
- Database Normalization (3NF)
- SQL Optimization
- Docker
- Kubernetes
- DevSecOps
- CI/CD
- Prometheus & Grafana
- ELK Stack
- OpenTelemetry

---

## Deliverables

- Legacy System Assessment
- Risk Assessment Matrix
- UML Diagrams
- Optimization Report
- Database Design
- SQL Optimization
- Refactored Pseudocode
- Microservices Architecture
- API Design Specification
- DevSecOps Pipeline
- Security Assessment
- Threat Model
- Incident Response Plan
- Validation Strategy
- Performance Comparison

---

## Project Structure

```
├── report/
│   └── Advanced_Software_Design_Reengineering_Project.pdf
│
├── diagrams/
│   ├── Current Architecture
│   ├── UML Diagrams
│   ├── Microservice Architecture
│   └── Threat Model
│
├── presentation/
│   └── Presentation Slides
│
└── README.md
```

---

## Key Improvements

- Reduced response time during peak enrollment
- Independent service scalability
- Improved security with RBAC and MFA
- Database optimization using indexing and normalization
- Event-driven communication
- Fault tolerance and automated recovery
- CI/CD with integrated security checks

---

## Authors

- Ramya Mercy Rajan
- Dheeraj Erpa

---

## Course Information

**Course:** Advanced Software Design

**Project Type:** Software Reengineering & System Modernization

**Instructor:** Dr. Mohamed Nazeh Alimam

---

## License

This repository is created for academic purposes as part of a university coursework submission.
