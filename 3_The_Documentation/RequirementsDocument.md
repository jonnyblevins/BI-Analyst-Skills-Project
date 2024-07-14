# Project Requirements Document

## 1. Project Overview
**Project Name:** Library Digitization Project  
**Description:** This project aims to digitize the library's paper-based card catalog system, replacing it with a modern digital app that improves efficiency, accessibility, and data management. The new system will support various media types, enhance user experience, and integrate with existing library systems.

## 2. Functional Requirements
- **User Requirements**
  - The system must allow librarians to add, update, and delete catalog entries.
  - Patrons should be able to search for and reserve books through the app.
- **System Requirements**
  - The system must support different media types, including books, e-books, and audiobooks.
  - The system must provide functionality for managing lending periods, renewals, and late fees.
- **Use Cases**
  - **Use Case 1:** A patron searches for a book, views its details, and reserves it.
  - **Use Case 2:** A librarian updates the catalog to add a new book entry.

## 3. Non-Functional Requirements
- **Performance Requirements**
  - The system should handle up to 100 concurrent users without performance degradation.
  - Search results should be displayed within 2 seconds.
- **Security Requirements**
  - The system must require authentication for librarians to access management features.
  - Patron data must be encrypted both in transit and at rest.
- **Usability Requirements**
  - The app should have an intuitive interface accessible to users of all tech-savviness levels.
  - The system must comply with accessibility standards (e.g., WCAG).
- **Reliability Requirements**
  - The system must have an uptime of 99.9%.
  - The system should perform automated daily backups.

## 4. Data Requirements
- **Data Models**
  - **Data Model 1:** Catalog entries including title, author, genre, and availability status.
  - **Data Model 2:** User accounts including name, email, and borrowing history.
- **Data Sources**
  - Existing paper-based card catalog.
  - Patron registration forms.
- **Data Management**
  - **Data Management Process 1:** Regular synchronization with existing library systems.
  - **Data Management Process 2:** Secure storage and retrieval of patron data.

## 5. Technical Requirements
- **Hardware Requirements**
  - Servers for hosting the application and database.
  - Workstations for librarians to manage the catalog.
- **Software Requirements**
  - Operating systems: Windows Server for servers, Windows 10 for workstations.
  - Application framework: .NET Core.
  - Database: SQL Server.
- **Integration Requirements**
  - Integration with the existing library management system.
  - Integration with third-party e-book and audiobook providers.

## 6. Transitional Requirements
- **Migration Plan**
  - **Migration Step 1:** Digitize existing paper catalog entries.
  - **Migration Step 2:** Import digitized data into the new system.
- **Training Plan**
  - **Training Step 1:** Develop training materials for librarians.
  - **Training Step 2:** Conduct training sessions for librarians on the new system.
- **Deployment Plan**
  - **Deployment Phase 1:** Pilot testing with a small user group.
  - **Deployment Phase 2:** Full rollout to all users.

## 7. Constraints and Assumptions
- **Constraints**
  - The project must be completed within the allocated budget of $40,000 - $70,000.
  - The digitization process must not disrupt regular library operations.
- **Assumptions**
  - The library staff coordinator will cooperate fully with the digitization process.
  - Adequate funding will be available throughout the project.
  - Necessary hardware and software will be procured on time.

  [Back to The Documentation](https://github.com/jonnyblevins/TWCSkillsAssessment/blob/main/3_The_Documentation/3_The_Documentation.md)