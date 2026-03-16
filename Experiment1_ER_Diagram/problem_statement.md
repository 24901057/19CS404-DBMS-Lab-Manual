# ER Diagram Workshop – Submission Template

## Objective
To understand and apply ER modeling concepts by creating ER diagrams for real-world applications.

## Purpose
Gain hands-on experience in designing ER diagrams that represent database structure including entities, relationships, attributes, and constraints.

---

# Scenario A: City Fitness Club Management

**Business Context:**  
FlexiFit Gym wants a database to manage its members, trainers, and fitness programs.

**Requirements:**  
- Members register with name, membership type, and start date.  
- Each member can join multiple programs (Yoga, Zumba, Weight Training).  
- Trainers assigned to programs; a program may have multiple trainers.  
- Members may book personal training sessions with trainers.  
- Attendance recorded for each session.  
- Payments tracked for memberships and sessions.

### ER Diagram:

![Image](https://github.com/user-attachments/assets/b0392874-cdca-4724-81bf-b6512bc0b335)
### Entities and Attributes
```
1.Member
Attributes: ID (Primary Key), Name, Membership Type
2.Program
Attributes: Program ID (Primary Key), Program Name
3.Trainer
Attributes: Name, Contact No, Experience
4. Session
Attributes: Date, Day, Trainer Name
5. Payment
Attributes: Name, Date, Amount
6. Attendance
Attributes: Date, Status
```
### Relationship Between Entities
```
1. Member — Makes — Payment
 A member makes a payment.
 One member can make multiple payments.
 Each payment belongs to one member.
 Cardinality is 1: M
2. Member— Register — Program
 A member registers for a program.
 A member can register for multiple programs.
 A program can have multiple members.
 Cardinality is M: N
3. Program — Assigns — Trainer
 A program is assigned to a trainer.
 A program may have multiple trainers
 A trainer may handle multiple programs.
 Cardinality is M: N
4. Trainer— Conducts — Session
 A trainer conducts sessions.
 One trainer can conduct many sessions.
 Each session is conducted by one trainer.
 Cardinality is 1: M
5. Session — Records — Attendance
 Attendance is recorded for each session.
 One session can have multiple attendance records.
 Each attendance record belongs to one session.
 Cardinality is 1: M
```
### Assumptions
- 
- 
- 

---

# Scenario B: City Library Event & Book Lending System

**Business Context:**  
The Central Library wants to manage book lending and cultural events.

**Requirements:**  
- Members borrow books, with loan and return dates tracked.  
- Each book has title, author, and category.  
- Library organizes events; members can register.  
- Each event has one or more speakers/authors.  
- Rooms are booked for events and study.  
- Overdue fines apply for late returns.

### ER Diagram:

![Image](https://github.com/user-attachments/assets/c2131fa3-c682-48b2-b17c-fab26464540c)

### Entities and Attributes

| Entity | Attributes (PK, FK) | Notes |
|--------|--------------------|-------|
|        |                    |       |
|        |                    |       |
|        |                    |       |
|        |                    |       |
|        |                    |       |

### Relationships and Constraints

| Relationship | Cardinality | Participation | Notes |
|--------------|------------|---------------|-------|
|              |            |               |       |
|              |            |               |       |
|              |            |               |       |

### Assumptions
- 
- 
- 

---

# Scenario C: Restaurant Table Reservation & Ordering

**Business Context:**  
A popular restaurant wants to manage reservations, orders, and billing.

**Requirements:**  
- Customers can reserve tables or walk in.  
- Each reservation includes date, time, and number of guests.  
- Customers place food orders linked to reservations.  
- Each order contains multiple dishes; dishes belong to categories (starter, main, dessert).  
- Bills generated per reservation, including food and service charges.  
- Waiters assigned to serve reservations.

### ER Diagram:

![Image](https://github.com/user-attachments/assets/e042b8a0-0182-463e-84ed-4118d5c8f040)


### Entities and Attributes

| Entity | Attributes (PK, FK) | Notes |
|--------|--------------------|-------|
|        |                    |       |
|        |                    |       |
|        |                    |       |
|        |                    |       |
|        |                    |       |

### Relationships and Constraints

| Relationship | Cardinality | Participation | Notes |
|--------------|------------|---------------|-------|
|              |            |               |       |
|              |            |               |       |
|              |            |               |       |

### Assumptions
- 
- 
- 

---

## Instructions for Students

1. Complete **all three scenarios** (A, B, C).  
2. Identify entities, relationships, and attributes for each.  
3. Draw ER diagrams using **draw.io / diagrams.net** or hand-drawn & scanned.  
4. Fill in all tables and assumptions for each scenario.  
5. Export the completed Markdown (with diagrams) as **a single PDF**
