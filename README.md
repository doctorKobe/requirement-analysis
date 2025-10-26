# requirement-analysis
A project for documenting and analyzing requirements in software development.
# Requirement Analysis in Software Development

## Introduction
This repository focuses on the Requirement Analysis phase in software development. 
It provides a structured approach to gathering, documenting, and analyzing requirements for a booking management system. 
The aim is to create a clear blueprint to guide the development process and ensure the system meets stakeholder expectations.

## What is Requirement Analysis?

Requirement Analysis is a critical phase in the Software Development Life Cycle (SDLC) that involves identifying, documenting, and managing the needs and expectations of stakeholders for a software project. 

This process ensures that the software solution aligns with business objectives and user needs while minimizing risks and costly errors during development. Requirement Analysis helps answer the fundamental question: *“What exactly should the software do, and how should it behave?”*

Key activities include:

- **Requirement Elicitation:** Gathering information from stakeholders through interviews, surveys, and workshops.
- **Requirement Documentation:** Creating clear and structured documents, including functional and non-functional requirements.
- **Requirement Validation:** Reviewing requirements with stakeholders to ensure they are accurate, complete, and feasible.
- **Use Case & Acceptance Criteria Definition:** Designing scenarios and conditions that the software must meet to be considered successful.

By performing thorough Requirement Analysis, development teams gain clarity, improve communication, and lay a solid foundation for building scalable, reliable, and high-quality software solutions.

## Why is Requirement Analysis Important?

Requirement Analysis is a cornerstone of successful software development. Its significance in the SDLC cannot be overstated. Here are three key reasons why it is critical:

1. **Ensures Clear Understanding of Project Goals**  
   By carefully gathering and analyzing requirements, development teams understand exactly what stakeholders expect. This reduces misunderstandings and prevents costly mistakes later in the project.

2. **Minimizes Risks and Reduces Costs**  
   Identifying potential challenges and ambiguities early in the development process allows teams to address them before implementation. This proactive approach saves time, resources, and prevents rework.

3. **Improves Communication and Collaboration**  
   Documented requirements provide a single source of truth that stakeholders and development teams can refer to. This ensures everyone is aligned, enhances collaboration, and sets clear expectations for deliverables.

4. **Facilitates Better Planning and Resource Allocation**  
   Knowing the scope and priorities of the project helps in efficient planning, scheduling, and allocation of resources, ensuring that essential features are developed first and deadlines are met.

By emphasizing Requirement Analysis, software projects are more likely to be completed on time, within budget, and meet the quality expectations of stakeholders.

## Key Activities in Requirement Analysis

Requirement Analysis involves several structured activities that help ensure the software meets stakeholder needs and aligns with business goals. The key activities include:

- **Requirement Gathering**  
  This is the process of collecting high-level requirements from stakeholders, clients, and users. It involves understanding the project’s objectives, constraints, and expectations to establish a foundation for detailed analysis.

- **Requirement Elicitation**  
  Elicitation goes beyond gathering and involves actively interacting with stakeholders to refine and clarify requirements. Techniques include interviews, questionnaires, workshops, brainstorming sessions, and observing existing systems to uncover both explicit and implicit needs.

- **Requirement Documentation**  
  Once requirements are gathered and elicited, they need to be formally documented. This includes writing detailed specifications, user stories, use cases, and diagrams that provide a clear reference for developers, testers, and project managers throughout the SDLC.

- **Requirement Analysis and Modeling**  
  During this phase, requirements are analyzed for feasibility, consistency, completeness, and potential conflicts. Modeling techniques, such as use case diagrams, flowcharts, and data models, are often used to visually represent the system and interactions between users and the system.

- **Requirement Validation**  
  Validation ensures that the documented requirements accurately reflect stakeholder needs and are achievable within project constraints. This involves reviewing requirements with stakeholders, verifying correctness, and confirming that the requirements are complete, consistent, and testable.

By systematically performing these activities, software development teams can reduce misunderstandings, avoid costly changes, and ensure that the final product meets both user expectations and business goals.

## Types of Requirements

In Requirement Analysis, understanding the different types of requirements is crucial for ensuring the system functions as expected and meets user expectations. The two main categories are Functional and Non-functional Requirements.

### Functional Requirements
Functional requirements define **what the system should do**. They describe specific behavior, actions, or features of the software.

**Examples for the Booking Management System:**
- **Property Search:** Users can search for available properties based on location, date, and type.
- **User Registration and Login:** Users must be able to create accounts, log in, and manage their profiles.
- **Booking Management:** Users can make, modify, or cancel bookings.
- **Payment Processing:** The system should process secure payments for bookings.
- **Notifications:** Users receive confirmation emails or alerts for bookings and cancellations.

### Non-functional Requirements
Non-functional requirements define **how the system performs** rather than what it does. These requirements often focus on quality attributes, constraints, and standards.

**Examples for the Booking Management System:**
- **Performance:** The system should load search results in under 2 seconds.
- **Security:** User data must be encrypted, and secure authentication must be enforced.
- **Scalability:** The system should handle up to 10,000 simultaneous users without performance degradation.
- **Usability:** The interface should be intuitive, ensuring users can book properties easily.
- **Availability:** The system should be operational 99.9% of the time.

By distinguishing between functional and non-functional requirements, developers and stakeholders can ensure the system not only works correctly but also provides a high-quality user experience.

## 🧭 Use Case Diagrams

### What is a Use Case Diagram?

A **Use Case Diagram** is a visual representation that shows how users (actors) interact with a system to achieve specific goals.  
It helps stakeholders and developers understand the system’s **functional requirements** and the relationships between **users** and **use cases**.

### 💡 Benefits of Use Case Diagrams
- **Clarifies system scope** – defines what is inside and outside the system boundary.  
- **Identifies system actors** – highlights who interacts with the system (e.g., customers, admins).  
- **Improves communication** – provides a simple, visual way for both technical and non-technical stakeholders to understand the system.  
- **Supports requirement validation** – ensures all user interactions are captured before design and implementation.

---

### 🧑‍💼 Actors in the Booking Management System
1. **Customer** – Makes, modifies, or cancels bookings.  
2. **Admin** – Manages users, services, and booking records.  
3. **System** – Sends notifications, processes payments, and manages availability.

---

### 🏷️ Use Cases
- Create Booking  
- Modify Booking  
- Cancel Booking  
- Make Payment  
- Receive Confirmation  
- View Booking History  
- Manage Users (Admin)  
- Manage Services (Admin)  
- Generate Reports (Admin)

---

### 🖼️ Use Case Diagram

Below is the use case diagram for the **Booking Management System**:

![Booking System Use Case Diagram](./alx-bookin-uc.png)

*Figure: Use Case Diagram showing interactions between actors and the system.*

---

### 🧠 Interpretation

- **Customer** interacts with the system to create, modify, and cancel bookings.  
- **System** handles backend processes like payment and notifications.  
- **Admin** oversees management functions such as user control and report generation.  

This diagram helps visualize all major user interactions and ensures no critical scenario is overlooked during requirement analysis.

✅ Acceptance Criteria
What is Acceptance Criteria?

Acceptance Criteria are the conditions that a software product must satisfy to be accepted by a user, customer, or stakeholder.
They define what success looks like for a specific feature or requirement and ensure that development teams clearly understand when a feature is considered “done.”

Acceptance Criteria serve as the bridge between requirements and testing — helping developers know what to build, and testers know what to verify.

💡 Importance of Acceptance Criteria

Clarifies expectations – ensures developers and stakeholders share the same understanding of what each feature must do.

Improves quality – defines measurable outcomes that must be met before delivery.

Guides testing – provides the foundation for test cases and validation.

Reduces ambiguity – prevents misunderstandings and scope creep during development.

Supports agile development – commonly used in user stories to determine “Done” criteria.

🧾 Example: Acceptance Criteria for the Checkout Feature

Feature: Checkout (Booking Confirmation and Payment)

Acceptance Criteria:

The system must display a booking summary (property name, date, duration, total cost) before payment.

Users must be able to choose a payment method (credit card, PayPal, or bank transfer).

The system must validate payment information and display an error message for invalid entries.

Upon successful payment, a confirmation message and booking reference number must be displayed.

The system must send a confirmation email to the user within one minute of payment.

The booking status must automatically change to “Confirmed” in the user’s booking history.

📘 By defining clear acceptance criteria, teams ensure that all stakeholders agree on what success means for each feature before implementation begins.
