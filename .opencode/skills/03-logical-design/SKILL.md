---
name: 03-logical-design
description: "Phase 1 Task 3: Logical Database Design. Converts the ERD into a relational schema."
version: 1.0.0
---

# 03-logical-design Skill

**Objective:**
Convert the conceptual ERD into a logical relational schema.

**Instructions for the Agent:**
1. Read the ERD from `outputs/02-erd-design-G11.md`.
2. Convert the ERD into a relational schema.
3. List all relations (tables) with their attributes.
4. Clearly identify Primary Keys (PK), Foreign Keys (FK), and Candidate Keys, using standard notation e.g., RelationName(PK, Attribute, FK).
5. Specify key constraints and referential integrity constraints.
6. Ensure that many-to-many relationships are properly resolved into associative tables.

**Output:**
Create or update `outputs/03-logical-design-G11.md`.