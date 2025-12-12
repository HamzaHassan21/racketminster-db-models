# Racketminster Booking and Management System – Conceptual and Logical Data Models

## Overview

This repository contains the conceptual and logical data models for the Racketminster Booking and Court Management System, developed as part of the 5COSC020W Database Systems module at the University of Westminster.

The models were created using Draw.io and exported in PDF format. They represent the system’s data requirements, relationships, and business rules, following good database design practices. The diagrams demonstrate the use of Specialization, relationship modelling, and entity structuring based on the project brief.

## Contents

W2044381BOTHERRD.drawio.pdf – The combined Draw.io diagram containing both the conceptual and logical models.

W2044381ERRDCW+(1).pdf – The written coursework report explaining modelling choices, entity design, attributes, constraints, and multiplicities.

## Conceptual Model

The conceptual model presents a high-level view of the system, focusing on the main entities and their relationships without detailing implementation-specific attributes or constraints. It provides a clear representation of the system’s structure, including:

## Key Entities

Person, Player, Instructor, Caretaker, Court, Park, Playing Session
Booking, Maintenance Log, Equipment.

## Specialization and Generalization

Court → Tennis, Pickleball, Multipurpose

Playing Session → Supervised, Unsupervised

Caretaker → Park Caretaker, Court Caretaker

Person → Player, Instructor, Caretaker

## Major Relationships

Instructors supervising sessions

Players participating in sessions

Caretakers responsible for maintenance

Equipment assigned to courts

Booking and block-booking relationships

This model emphasises the business rules and operational requirements of the Racketminster system.

## Logical Model

The logical model refines the conceptual design into a structure suitable for relational database implementation. It includes:

Primary keys, foreign keys, and detailed attributes for each entity

Relationship constraints, cardinalities, and roles

Ternary and recursive relationship modelling (e.g., player–session–court participation)

Logical design decisions such as:

Each playing session occurs on one court only

Block bookings apply exclusively to unsupervised sessions

Maintenance logs connect caretakers and equipment

Referral relationships track player-to-player recommendations

The logical model ensures that the system is ready for translation into a physical schema.

## Key Features and Improvements

Extensive use of specialization to reflect real-world distinctions

Well-defined entity attributes and identifiers

Accurate representation of business rules within relationship constraints

Inclusion of ternary and recursive relationships where needed

Scalable and modular entity structure for future system expansion

## How to View the Models

Open W2044381BOTHERRD.drawio.pdf to view the full conceptual and logical diagrams.

Open W2044381ERRDCW+(1).pdf for detailed explanations of entities, relationships, and design rationale.

## Author

Hamza Hassan - Final-Year Computer Science Student Cloud & DevOps Enthusiast Focused on Serverless and Edge Architectures

License

This repository was produced for academic assessment. Redistribution or reuse of this material without permission from the author or the University of Westminster is not permitted.

## 📫 Connect with Me
[LinkedIn](https://www.linkedin.com/in/hamzahassan21/)
[Youtube](https://www.youtube.com/channel/UC51JEAEBV8WXwf2ZLROvUJw)
