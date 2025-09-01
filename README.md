# Requirement Analysis in Software Development

## 📌 What is Requirement Analysis?
Requirement Analysis is the process of gathering, understanding, and documenting what a software system (or project) needs to do. It’s one of the first and most important phases in the Software Development Life Cycle (SDLC).

## 🔑 Why is Requirement Analysis Important?
1. Ensures the software solves the right problem.  
2. Reduces the chances of costly mistakes later in development.  
3. Serves as a blueprint for designers, developers, and testers.  

---

## 🛠️ Key Activities in Requirement Analysis
Requirement Analysis ensures that the system being developed truly meets the needs of users and stakeholders. Below are the five key activities:

### 1. Requirement Gathering
The process of collecting requirements from stakeholders, users, and other sources.  
*Example:* Conducting interviews, surveys, or reviewing existing systems.

---

### 2. Requirement Elicitation
Requirement Elicitation goes beyond gathering — it involves actively engaging with stakeholders to uncover hidden needs, clarify vague requirements, and explore alternatives.  
*Example:* Workshops, brainstorming sessions, and use-case discussions to refine needs.

---

### 3. Requirement Documentation
All gathered and elicited requirements must be documented clearly and precisely. The most common form is the **Software Requirement Specification (SRS)** document.  
*Example:* Writing down functional requirements (“The system must send confirmation emails”) and non-functional requirements (“The system must respond within 2 seconds”).

---

### 4. Requirement Analysis and Modeling
At this stage, requirements are analyzed for feasibility, completeness, and consistency. Modeling techniques such as use-case diagrams, data flow diagrams (DFD), or UML diagrams may be used to visualize how the system will function.  
*Example:* Using UML to model the relationship between users and booking functionality in a travel system.

---

### 5. Requirement Validation
Validation ensures that the documented requirements truly reflect the needs of stakeholders. This step involves reviews, walkthroughs, or prototyping to confirm accuracy before moving into design and development.  
*Example:* Sharing the SRS with stakeholders to confirm that nothing is missing or misunderstood.

---

## 🧩 Types of Requirements
When developing a system, requirements are classified into **Functional** and **Non-functional**.  
Functional requirements focus on *what the system should do*, while Non-functional requirements focus on *how the system should perform*.

### 🔹 Functional Requirements
**Definition:**  
Functional requirements describe the specific tasks, services, and functions that the system must perform.  

**Examples for Booking Management Project:**  
- The system must allow customers to create, view, update, and cancel bookings.  
- The system must send confirmation notifications via email or SMS after a booking.  
- The system must let administrators manage available rooms and schedules.  
- The system must generate booking and payment reports for managers.  
- The system must allow users to search for available rooms by date, category, and price.  

---

### 🔹 Non-functional Requirements
**Definition:**  
Non-functional requirements define the **quality attributes** and constraints of the system.  

**Examples for Booking Management Project:**  
- The system should process booking requests within **2 seconds**.  
- The system must be available **24/7** with at least **99.9% uptime**.  
- The user interface must be mobile-responsive and accessible to people with disabilities.  
- All sensitive user data must be encrypted and comply with **GDPR** regulations.  
- The system must handle at least **1,000 concurrent users** without crashing.  

---

## 🎭 Use Case Diagrams

**Definition:**  
A Use Case Diagram is a visual representation that shows the interactions between **actors** (users or external systems) and the **system** itself. It captures the **functional requirements** of the system in a simple and easy-to-understand way.  

**Benefits of Use Case Diagrams:**  
- Provides a clear overview of system functionality.  
- Helps identify the roles of different actors and their interactions.  
- Bridges the communication gap between stakeholders and developers.  
- Supports requirement validation and ensures alignment with business goals.  

---

### 📌 Use Case Diagram for Booking Management System

**Actors:**  
- **Customer**: Makes bookings, cancels bookings, views booking details, receives notifications.  
- **Admin**: Manages room availability, approves/rejects bookings, generates reports.  
- **Payment Gateway**: Processes payments for bookings.  

**Use Cases:**  
- Create Booking  
- Cancel Booking  
- View Booking Details  
- Receive Confirmation  
- Manage Rooms  
- Approve/Reject Booking  
- Generate Reports  
- Process Payment  

---

📷 **Diagram:**  

![Use Case Diagram](images/alx-booking-uc.png)

