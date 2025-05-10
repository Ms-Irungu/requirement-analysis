# Requirement Analysis in Software Development.
This repository provides an in-depth overview of Requirement Analysis, a crucial phase in the Software Development Lifecycle (SDLC). It outlines its importance, processes, types, and tools used to define and validate system requirements.

## What is Requirement Analysis?

Requirement Analysis is a critical phase in the software development lifecycle (SDLC) where the project team gathers, analyzes, and defines the requirements of the software product to be developed. It ensures that all stakeholders have a shared understanding of what the system should do and how it should perform.

This process involves communicating with stakeholders, understanding business needs, translating them into technical requirements, and ensuring they are feasible and testable. It sets the foundation for successful system design, development, and deployment.

## Why is Requirement Analysis Important?

- **Clarity and Understanding:** Reduces ambiguity by clearly capturing stakeholders' expectations.
- **Scope Definition:** Clearly defines the scope, preventing scope creep and feature bloat.
- **Basis for Design and Development:** Ensures the design and development teams build exactly what is needed.
- **Cost and Time Estimation:** Enables realistic budgeting and scheduling.
- **Quality Assurance:** Leads to a product that meets user needs, ensuring satisfaction.

## Key Activities in Requirement Analysis

This section outlines the five core activities involved in the requirement analysis process during software development. Each step ensures that the system is aligned with stakeholder expectations and can be successfully developed and delivered.

## 1. Requirement Gathering 🗂️

- **Interviews**: Conducting interviews with stakeholders to gather detailed information about their needs and expectations.  
- **Surveys/Questionnaires**: Distributing surveys to collect requirements from a larger audience.  
- **Workshops**: Organizing workshops with stakeholders to discuss and gather requirements.  
- **Observation**: Observing end-users in their working environment to understand their needs.  
- **Document Analysis**: Reviewing existing documentation and systems to understand current functionalities and requirements.

## 2. Requirement Elicitation ✍️

- **Brainstorming**: Conducting brainstorming sessions to generate ideas and gather requirements.  
- **Focus Groups**: Holding focus group discussions with selected stakeholders to gather detailed requirements.  
- **Prototyping**: Creating prototypes to help stakeholders visualize the system and refine their requirements.

## 3. Requirement Documentation 📚

- **Requirement Specification Document**: Creating a detailed document that lists all functional and non-functional requirements.  
- **User Stories**: Writing user stories to describe functionalities from the user’s perspective.  
- **Use Cases**: Creating use case diagrams to show interactions between users and the system.

## 4. Requirement Analysis and Modeling 📊

- **Requirement Prioritization**: Prioritizing requirements based on their importance and impact on the project.  
- **Feasibility Analysis**: Assessing the feasibility of requirements in terms of technical, financial, and time constraints.  
- **Modeling**: Creating models (e.g., data flow diagrams, entity-relationship diagrams) to visualize and analyze requirements.

## 5. Requirement Validation ✅

- **Review and Approval**: Reviewing the documented requirements with stakeholders to ensure accuracy and completeness.  
- **Acceptance Criteria**: Defining clear acceptance criteria for each requirement to ensure they meet the expected standards.  
- **Traceability**: Establishing traceability matrices to ensure all requirements are addressed during development and testing.

## Types of Requirements

### Functional Requirements ⚙️
These describe what the system should do.

**Examples:**
- **Search Properties:** Filter by location, price, availability.
- **User Registration:** Register with email, name, and password.
- **Property Listings:** Display property details and images.
- **Booking System:** Book and manage property reservations.
- **User Authentication:** Secure login and sign-up.

### Non-functional Requirements 🛡️
These describe how the system should perform.

**Examples:**
- **Performance:** Load pages within 2 seconds, handle 1000+ users.
- **Security:** Secure login, encrypted user data.
- **Scalability:** Support future growth in traffic and users.
- **Usability:** Easy-to-use, responsive design.
- **Reliability:** 99.9% uptime and fast recovery.

## Use Case Diagrams

Use case diagrams visually represent user interactions with the system to accomplish specific goals.

**Benefits:**
- Easy communication between developers and stakeholders.
- Clear visualization of system functionalities.
- Helps in identifying necessary features.

![Booking System Use Case Diagram](https://github.com/user-attachments/assets/7f88e2ca-4bca-413a-89af-dd86b18dd976)

## Acceptance Criteria

Acceptance Criteria are specific, measurable conditions that a system feature must meet to be accepted by stakeholders.

### Importance:
- Provides clarity on what "done" means.
- Guides testing and validation.
- Ensures mutual understanding between teams and stakeholders.

### Example: Checkout Feature (Booking System)

- Users should select available dates from a calendar.
- Booking should be confirmed only if the selected dates are available.
- A confirmation email should be sent within 2 minutes after booking.
- Users should be redirected to a confirmation page showing booking ID and summary.

Each of these must pass before the feature is marked complete.
