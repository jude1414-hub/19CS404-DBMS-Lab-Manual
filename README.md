## NAME : Jude Clement Jose G
## REG : 212224230109
## AIM
To design and analyze a Gym Management System, City Library Event & Book Lending System, Restrarunt Table Reservation and Ordering using an Entity Relationship (ER) diagram by identifying entities, attributes, relationships, and constraints, and to understand how the ER model helps in organizing and managing database information efficiently.
## THEORY
### Step 1: Identify the Entities

      The main entities in the Gym Management System are:
      
      Member
      Trainer
      Program
      Booking
      
      These entities represent the major objects involved in the system.

## Step 2: Define the Attributes

      Each entity contains attributes that describe its details.
      
      Member
      member_id
      name
      email
      phone
      Trainer
      trainer_id
      name
      speciality
      Program
      program_id
      program_name
      duration
      Booking
      payment_id
      member_id
      payment_date
      amount
## Step 3: Identify Primary Keys

      Primary keys uniquely identify each record.
      
      member_id → Primary Key of Member
      trainer_id → Primary Key of Trainer
      program_id → Primary Key of Program
      payment_id → Primary Key of Booking
## Step 4: Identify Relationships
      Member — Booking
      One member can register many bookings.
      Relationship: Registers
      Cardinality: 1 : N
      Member — Trainer
      Members can book trainers.
      Trainers can train multiple members.
      Relationship: Booking
      Cardinality: M : N
      Trainer — Program
      Trainers can teach many programs.
      Programs can be taught by many trainers.
      Relationship: Teaches
      Cardinality: M : N
      Booking — Program
      Payments are made for programs.
      Relationship: Pays
## Step 5: Define Constraints

      The ER diagram follows these constraints:
      
      Primary Key constraint
      Entity Integrity constraint
      Referential Integrity constraint
      
      These constraints help maintain accurate and consistent data.

## Step 6: Explain the Purpose of the ER Diagram
      The ER diagram is used to:
      
      Organize gym data efficiently
      Reduce data redundancy
      Maintain relationships between entities
      Manage bookings and payments
      Improve database consistency
      
### ER-DIAGRAM FOR Gym Management System

<img width="1051" height="717" alt="image" src="https://github.com/user-attachments/assets/44ab363d-7cea-45e7-96cf-6707a835d973" />

### ER-DIAGRAM FOR City Library Event & Book Lending System

<img width="1133" height="873" alt="image" src="https://github.com/user-attachments/assets/bae58698-5c6d-4481-9784-5686f32dfec3" />

### ER-DIAGRAM FOR Restrarunt Table Reservation and Ordering


<img width="890" height="865" alt="image" src="https://github.com/user-attachments/assets/5f4960a3-fda0-4221-bb8c-81eb1185ab7c" />

### RESULT

Thus, the ER diagram for the Gym Management System, City Library Event & Book Lending System, Restrarunt Table Reservation and Ordering was successfully designed by identifying the entities, attributes, relationships, and constraints. The ER model clearly represents the interaction between members, trainers, programs, bookings, and payments, and helps in creating an efficient and well-structured database system.
