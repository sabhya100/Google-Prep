# Database Management System (DBMS) Notes

## 1. Introduction
- DBMS = software to store, retrieve, and manage data.
- Examples: MySQL, PostgreSQL, MongoDB, Oracle.

## 2. Normalization
- Process of organizing data to reduce redundancy.
- Normal Forms:
  - 1NF → Atomic values, no repeating groups.
  - 2NF → 1NF + no partial dependency.
  - 3NF → 2NF + no transitive dependency.
  - BCNF → Stronger version of 3NF.

## 3. Transactions
- Properties = **ACID**:
  - Atomicity: All or none.
  - Consistency: DB remains valid.
  - Isolation: Transactions don’t interfere.
  - Durability: Results are permanent.

## 4. Indexing
- Improves search performance.
- Types:
  - Primary Index
  - Secondary Index
  - Clustered Index
  - Non-clustered Index

## 5. SQL vs NoSQL
- **SQL (Relational)**
  - Structured data, fixed schema.
  - Uses tables with rows & columns.
  - Examples: MySQL, PostgreSQL.
- **NoSQL (Non-Relational)**
  - Schema-less, flexible.
  - Types: Document (MongoDB), Key-Value (Redis), Column (Cassandra), Graph (Neo4j).
