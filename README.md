
# Souqly
### Multi-Vendor E-Commerce Platform

**Advanced Database Systems — Course Project**

Souqly is a multi-vendor e-commerce platform designed to support multiple independent vendors and stores within a shared system. The project focuses on database design, multi-tenancy, transaction management, query optimization, and scalable system architecture.

---

## Project Overview

Souqly aims to provide a centralized marketplace where multiple vendors can manage their stores, products, customers, orders, and payments while sharing a common platform.

The system is designed around a multi-tenant database architecture, ensuring logical separation of tenant data while maintaining centralized management.

## Main Objectives

- Design a reliable multi-tenant database architecture.
- Support multiple vendors and stores.
- Maintain data integrity and consistency.
- Implement efficient transaction processing.
- Optimize database queries and indexing.
- Support concurrent users and operations.
- Build a modern and responsive user interface.
- Develop a maintainable and scalable application architecture.

## Technology Stack

| Layer | Technology |
|---    |---         |
| Backend | Laravel (PHP) |
| Frontend | To be finalized |
| Database | MySQL 8 |
| Version Control | Git & GitHub |
| Development Environment | Docker (planned) |

## Core Database Modules

The initial database design includes:

- **Tenants:** Platform tenants and subscription information.
- **Stores:** Vendor stores and their configuration.
- **Products:** Product catalog, prices, and inventory.
- **Customers:** Customer information.
- **Orders:** Customer orders and order statuses.
- **Order Items:** Individual products within orders.
- **Payments:** Payment records and transaction statuses.
- **Events:** User and system activity tracking.

## System Architecture

Souqly follows a modular architecture consisting of:

- **Frontend:** User-facing application and interfaces.
- **Backend:** Business logic, APIs, authentication, and application services.
- **Database:** Shared relational database with multi-tenant data organization.
- **Infrastructure:** Development and deployment configuration.

## Repository Structure

```text
souqly/
├── backend/
├── frontend/
├── database/
│   ├── schema/
│   ├── seeds/
│   ├── optimization/
│   └── benchmarks/
├── docs/
│   ├── architecture/
│   ├── requirements/
│   ├── api/
│   └── setup/
├── infra/
│   └── docker/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   └── workflows/
├── .gitignore
└── README.md
```

## Database Engineering Focus

The project emphasizes advanced database concepts, including:

- Multi-Tenant Database Design
- Relational Modeling and Normalization
- Primary and Foreign Key Constraints
- Indexing and Query Optimization
- Transaction Management
- Concurrency Control
- Isolation Levels
- Performance Benchmarking

## Team



- Moqtada Shehadeh
- Batool AbuYaman
- Masa AbuLawi

## Development Workflow

The project uses GitHub for collaborative development.

- `main`: Main project branch.
- Individual member branches: Independent working branches.
- Pull Requests: Used to review and integrate changes into the main branch.

All team members work on the complete project structure and coordinate their changes through Git.

## Project Status

**Current Phase:** Repository Setup and System Foundation.

The project is currently being organized, with database design, backend development, and frontend development planned as the next stages.

---

*Souqly — One Platform, Multiple Vendors.*
