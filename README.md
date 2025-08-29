# requirement-analysis
# Requirement Analysis in Software Development

## Introduction
This repository is dedicated to documenting and understanding **Requirement Analysis** in software development.  
Requirement analysis is the process of gathering, analyzing, and defining what a software system should do.  
The goal of this repository is to provide notes, examples, and resources that explain how requirement analysis helps ensure software meets user needs and business goals.
## Why is Requirement Analysis Important?
Requirement Analysis is a critical step in the **Software Development Life Cycle (SDLC)** because it ensures the system being developed truly addresses the needs of its users and stakeholders. Key reasons include:

1. **Avoids Miscommunication**  
   Clear requirements reduce misunderstandings between clients, developers, and stakeholders.  

2. **Saves Time and Cost**  
   Identifying problems early prevents expensive fixes later in the development cycle.  

3. **Improves Quality**  
   Well-defined requirements ensure the final product meets user expectations and business goals.  

---

## Key Activities in Requirement Analysis
Requirement Analysis involves several key activities that help transform vague user needs into clear, actionable requirements:

- **Requirement Gathering**  
  Collecting initial requirements from stakeholders through interviews, surveys, and observation.  

- **Requirement Elicitation**  
  Engaging with users and stakeholders to deeply understand their needs and constraints.  

- **Requirement Documentation**  
  Writing down the requirements in a clear, structured format for reference.  

- **Requirement Analysis and Modeling**  
  Breaking down requirements into logical models such as use cases, diagrams, or workflows.  

- **Requirement Validation**  
  Confirming that documented requirements are correct, complete, and agreed upon by stakeholders.  

---

## Types of Requirements

### Functional Requirements
Functional requirements define **what the system should do**.  
They describe features and functions the system must support.  

**Example (Booking Management System):**
- Users should be able to **search for available rooms**.  
- The system should allow **customers to book and cancel reservations**.  
- Admin should be able to **add, edit, and delete room details**.  

### Non-Functional Requirements
Non-functional requirements define **how the system should perform** rather than specific features.  
They describe quality attributes, constraints, and performance requirements.  

**Example (Booking Management System):**
- The system should respond to booking requests within **2 seconds**.  
- The application should be available **24/7 with 99.9% uptime**.  
- All sensitive user data (like payment info) should be **encrypted**.  

---

## Use Case Diagrams
**Use Case Diagrams** visually represent the interactions between **actors** (users or systems) and the system itself.  
They help in:  
- Understanding user roles and their interactions with the system.  
- Communicating system functionality at a high level.  
- Identifying missing requirements.  

### Booking Management System Use Case Diagram
Actors:  
- **Customer** (books and cancels reservations, makes payments).  
- **Admin** (manages rooms, views reports).  
- **Payment Gateway** (handles checkout process).  

![Booking System Use Case Diagram](alx-booking-uc.png)  

---

## Acceptance Criteria
**Acceptance Criteria** define the conditions that a software feature must satisfy to be accepted by stakeholders.  

### Importance
- Provides a clear definition of “done.”  
- Ensures developers, testers, and stakeholders share the same expectations.  
- Reduces ambiguity and improves testability.  

### Example (Checkout Feature in Booking System)
**Feature:** Checkout after booking  
**Acceptance Criteria:**  
- User must be able to review booking details before payment.  
- System must integrate with the payment gateway to process transactions.  
- Successful payment should generate a confirmation receipt emailed to the user.  
- If payment fails, the system should show an error and allow retry.  

---

## Manual Check
- Repository is named **requirement-analysis**.  
- `README.md` is created with all mandatory sections.  
- Use case diagram file `alx-booking-uc.png` is linked in README.
