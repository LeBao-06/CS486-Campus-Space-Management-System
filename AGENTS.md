# AGENTS.md — cs486-demo

CS486 database systems teaching demo. Repository is empty; expect code to be added during sessions.

## Recurring context

- Root directory: `E:/CS486-Campus-Space-Management-System`
- This is a demo project, not production.
- Run `ls -la` to detect new files before assuming anything exists.

# Database Design Agent Rules

This project transforms business requirements into database design artifacts.

<!---YOU COULD CHANGE THE FOLLOW SECTIONS --->
## Workflow Order
Always follow this order:

1. Business Requirement Analysis
2. Conceptual Database Design (ERD using Crow's Foot)
3. Logical Database Design
4. Database Design Validation
5. Database Implementation (DDL for SQL Server)
6. Sample Data Preparation (INSERT statements)
7. Query Design (5 Business Queries)

Do not jump directly to DDL. The documents from the prior steps should be followed in the later steps.

## Required Outputs

- `outputs/01-business-req-analysis-G11.md`
- `outputs/02-erd-design-G11.md`
- `outputs/03-logical-design-G11.md`
- `outputs/04-design-validation-G11.md`
- `outputs/05-db-definition-G11.sql`
- `outputs/06-sample-data-G11.sql`
- `outputs/07-query-design-G11.sql`

## DBMS

Use Microsoft SQL Server unless the user specifies another DBMS.

## Design Rules

- Record assumptions explicitly.
- Record open questions explicitly.
- Preserve traceability from requirement → entity → relationship → table → constraint.
- Use Mermaid `erDiagram` for ERD.
- Do not silently invent business rules.
