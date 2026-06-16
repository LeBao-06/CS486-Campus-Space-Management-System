---
name: 05-db-definition
description: "Phase 1 Task 5: Database Implementation. Generates SQL DDL to create the schema using Microsoft SQL Server."
version: 1.0.0
---

# 05-db-definition Skill

**Objective:**
Implement the logical design using Microsoft SQL Server DDL statements.

**Instructions for the Agent:**
1. Read the validated schema from `outputs/03-logical-design-G11.md` and `outputs/04-design-validation-G11.md`.
2. Generate the SQL Data Definition Language (DDL) queries.
3. Use Microsoft SQL Server syntax (compatible with SQL Server 2025).
4. Include `CREATE TABLE` statements, explicitly defining primary keys, foreign keys, and constraints (`CHECK`, `UNIQUE`, `NOT NULL`, Default values).
5. Ensure the table creation order respects foreign key dependencies (or use `ALTER TABLE` after creation).
6. Provide DROP statements at the beginning of the script (if exists) before creating tables to ensure it can be rerun cleanly.

**Output:**
Create or update `outputs/05-db-definition-G11.sql`.