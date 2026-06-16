---
name: 06-sample-data
description: "Phase 1 Task 6: Sample Data Preparation. Generates realistic sample data in T-SQL."
version: 1.0.0
---

# 06-sample-data Skill

**Objective:**
Provide `INSERT` statements with realistic sample data for the new database.

**Instructions for the Agent:**
1. Read the database definition in `outputs/05-db-definition-G11.sql`.
2. Generate SQL `INSERT` statements for every table.
3. Use Microsoft SQL Server (T-SQL) syntax.
4. Ensure the sample data reflects realistic operational data for a University campus space management system (e.g. realistic user names, typical spaces like Auditoriums, actual booking entries, and maintenance logs).
5. Cover important exceptional cases and normal operations.
6. Ensure the order of `INSERT` statements respects foreign key dependencies (parent tables before child tables).

**Output:**
Create or update `outputs/06-sample-data-G11.sql`.