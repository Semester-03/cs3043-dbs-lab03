# Lab 03 — Views, Outer Joins and Intermediate SQL

CS3043 – Database Systems  
Department of Computer Science and Engineering, University of Moratuwa

## Overview

- SQL View creation (CREATE VIEW), update restrictions, and WITH CHECK OPTION
- Outer join semantics: LEFT OUTER JOIN, RIGHT OUTER JOIN, and FULL OUTER JOIN
- Handling NULL values in join conditions and conditional COALESCE expressions
- Intermediate nested subqueries in FROM, WHERE, and HAVING clauses
- Set operations: UNION, INTERSECT, and EXCEPT / MINUS queries

## Module Alignment

- **Curriculum Context**: Practical work covering intermediate SQL operations, database view abstraction, and complex join semantics.
- Theory and foundations are documented in the [CS3043-Weekly-Notes](https://github.com/CS3043-Database-Systems/CS3043-Weekly-Notes) repository.

## Repository Structure

```text
.
├── supplied/
├── queries/
├── evidence/
└── README.md
```

## Engineering & Git Standards

- **Commit Conventions**: All commits follow the Conventional Commits format (`feat:`, `fix:`, `docs:`, `chore:`, `refactor:`).
- **Branching Workflow**: Tasks and deliverables utilize feature branches prior to merging into `main`.
- **Reproducibility**: SQL scripts, relational schemas, and terminal execution logs are systematically preserved in `evidence/`.

## Academic Context

Department of Computer Science and Engineering, University of Moratuwa.
