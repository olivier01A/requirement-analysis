# What is Requirement Analysis?

# Key Activities in Requirement Analysis

## .Requirement Gathering (Elicitation):

Collecting requirements from stakeholders through interviews, surveys, workshops, observation, and documentation review.

Identifying both functional requirements (what the system should do) and non-functional requirements (performance, security, scalability, etc.).

## .Requirement Modeling:

Using diagrams (use case diagrams, data flow diagrams, ER diagrams) and models to represent requirements visually.

Helps simplify complex requirements for clarity and validation.

## .Documentation:

Creating detailed documents like the Software Requirements Specification (SRS), use cases, and user stories.

These documents become the official reference for design and development.

## .Requirement Validation:

Ensuring requirements are correct, complete, feasible, consistent, and testable.

Reviewing with stakeholders to confirm that the documented requirements truly reflect their needs.

## .Requirement Prioritization:

Ranking requirements based on business value, urgency, and feasibility.

Ensures that critical features are delivered first and resources are allocated effectively.

# Importance of Requirement Analysis in SDLC

## .Defines Project Scope Clearly:

Establishes boundaries for what the system will and won’t do, reducing the risk of scope creep.

## .Minimizes Errors and Rework:

Early identification and correction of unclear or conflicting requirements prevent costly fixes later in development.

## .Improves Communication:

Acts as a bridge between stakeholders and the technical team, ensuring mutual understanding.

## .Supports Better Design and Development:

A well-defined set of requirements provides a clear roadmap for designers and developers to build the system.

## .Facilitates Testing and Validation:

Test cases and acceptance criteria are derived directly from the requirements, ensuring the final product meets expectations.

Ensures Customer Satisfaction:

By capturing stakeholders’ real needs accurately, the final software product is more likely to satisfy business goals and user expectations.

# Why is Requirement Analysis Important?

Here are three key reasons why Requirement Analysis is critical in the Software Development Life Cycle (SDLC):

## 1. Defines Clear Project Scope and Objectives

Requirement Analysis ensures that stakeholders’ needs and expectations are accurately gathered and documented.

This clarity prevents scope creep (uncontrolled changes or additions), keeping the project focused and aligned with business goals.

A well-defined scope also helps developers, testers, and managers understand exactly what needs to be built.

## 2. Improves Communication Between Stakeholders

It acts as a bridge between clients, end-users, and the development team.

By documenting requirements through models, specifications, and use cases, it ensures that all parties share the same understanding of the system.

This reduces misunderstandings and minimizes rework later in the project.

## 3. Reduces Development Costs and Time

Detecting and correcting requirement errors early is far less expensive than fixing them during coding or after deployment.

With well-analyzed requirements, developers build the right features the first time, avoiding wasted resources.

This leads to better time management, optimized resource allocation, and cost savings.

✅ In summary: Requirement Analysis is critical in the SDLC because it sets a clear direction, ensures stakeholder alignment, and prevents costly mistakes.

# Key Activities in Requirement Analysis

## .Requirement Gathering

Initial step in the requirements process.

Focuses on collecting raw information about what stakeholders need.

Techniques include interviews, surveys, questionnaires, and observations.

Ensures all potential requirements are captured before refinement.

## .Requirement Elicitation

.Involves actively engaging with stakeholders to clarify, refine, and expand gathered requirements.

.Uses workshops, brainstorming sessions, prototyping, and use case scenarios.

.Aims to uncover hidden, implicit, or conflicting requirements.

.Builds a deeper understanding of the problem domain.

## .Requirement Documentation

.Converts gathered and elicited requirements into formal, structured documents.

.Common outputs: Software Requirement Specification (SRS), user stories, or use case diagrams.

.Ensures requirements are clearly communicated to all team members.

.Provides a baseline for project scope and future reference.

## .Requirement Analysis and Modeling

.Examines requirements to identify feasibility, dependencies, and conflicts.

.Prioritizes requirements based on business value and technical constraints.

.Uses modeling techniques (e.g., UML diagrams, data flow diagrams, prototypes) to visualize system behavior.

.Helps in understanding how requirements will be implemented.

## .Requirement Validation

.Confirms that documented requirements accurately reflect stakeholder needs.

.Involves reviews, walkthroughs, inspections, and stakeholder approval sessions.

.Ensures requirements are consistent, complete, and testable.

.Reduces risk of costly rework during later SDLC phases.

# Types of Requirements

##  Functional Requirements

These describe what the system should do — the specific features and functions it must provide.

Examples for Booking Management System:

*User Authentication:

.Users must be able to register and log in securely.

.Admins must be able to log in with special privileges.

*Property/Event Listing:

.The system should allow admins to add, edit, and remove listings (e.g., hotels, rooms, flights, or events).

*Search and Filter:

.Users should be able to search for bookings by date, location, type, or price range.

*Booking Process:

.Users must be able to select available options and make reservations.

*Payment Processing:

.The system should support multiple payment methods (credit card, PayPal, mobile money).

*Booking Confirmation & Notifications:

.The system must send confirmation emails/SMS after successful booking.

*Cancellation & Refunds:

.Users should be able to cancel or modify bookings, with applicable refund rules.

*Reporting & Analytics:

.Admins can generate reports on revenue, occupancy, and booking trends.

##  Non-Functional Requirements

These describe how the system should perform — focusing on quality attributes rather than specific features.

*Examples for Booking Management System:

*Performance:

.The system should handle at least 500 concurrent users without performance degradation.

.Search results must be displayed in under 3 seconds.

*Scalability:

.system must be able to scale horizontally to support future growth in users and bookings.

*Security:

.All user data (especially payment details) must be encrypted.

.The system should comply with PCI-DSS standards for payment security.

*Availability/Reliability:

.The system should have 99.9% uptime.

.Data backups must be performed daily.

*Usability:

.The interface should be responsive and work on desktops, tablets, and mobile devices.

*Maintainability:

.The system’s code should follow modular architecture to ease updates and bug fixes.

*Compatibility:

.Must support major browsers (Chrome, Edge, Safari, Firefox).

*Localization:

.The system should support multiple languages and currencies

# Use Case Diagrams

A Use Case Diagram is a type of Unified Modeling Language (UML) diagram used in software engineering to visually represent how different users (called actors) interact with a system. It focuses on the functional requirements of the system, showing what the system should do from the perspective of its users rather than how it is implemented.

## Key Elements in a Use Case Diagram

Actors → External entities (users, other systems, or devices) that interact with the system.

Use Cases → The specific actions or services the system performs in response to an actor (e.g., "Book Ticket," "Login").

System Boundary → Defines the scope of the system, showing what functions belong inside the system.

Relationships → Connections between actors and use cases (e.g., associations, inclusions, extensions).

## Benefits of Use Case Diagrams

Clear Visualization of System Functionality

Helps stakeholders quickly understand what the system will do without going into technical details.

Defines System Scope

Clearly shows what is inside and outside the system’s boundary, avoiding scope creep.

Improves Communication

Provides a common language between developers, business analysts, and stakeholders.

Captures User Requirements

Focuses on what users want to achieve, ensuring the system is designed to meet user needs.

Helps in Requirement Analysis

Identifies key interactions and dependencies early, making requirement gathering structured.

Foundation for Test Cases

Use cases can be transformed into test scenarios to validate system functionality.

Supports System Design

Serves as a blueprint for detailed modeling, including sequence diagrams, activity diagrams, and system architecture.

 In short: Use Case Diagrams provide a high-level, user-centered view of a system, making them essential for clarifying requirements, aligning stakeholders, and guiding system design.


|[image alt]([image_url](https://raw.githubusercontent.com/olivier01A/requirement-analysis/f23adb1ed5540dce7eb3a646c3d2728988bc7125/alx-booking-uc.png.png))




 
