# Bynry Backend Engineering Case Study Submission

## Candidate
Vaishnavi Nehare

## Overview
This repository contains my submission for the Backend Engineering Intern case study based on **StockFlow**, a B2B inventory management platform.

The submission focuses on backend engineering concepts including:
- API debugging and code review
- Database schema design
- Low-stock alert API implementation
- Data integrity and ACID transactions
- Scalability and backend tradeoffs

---

## Case Study Sections

### Part 1 — Code Review & Debugging
Reviewed the provided Flask endpoint for product creation and identified issues related to:
- Input validation
- SKU uniqueness
- Transaction safety
- Multi-warehouse data modeling
- Error handling
- Monetary precision using Decimal

Included a corrected production-oriented implementation with reasoning.

---

### Part 2 — Database Design
Designed a normalized schema covering:
- Companies
- Warehouses
- Products
- Inventory
- Suppliers
- Product Bundles
- Inventory History

Also included:
- Constraints and indexes
- Requirement gaps/questions for product team
- Design tradeoff explanations

---

### Part 3 — API Implementation
Implemented a low-stock alert endpoint:

GET /api/companies/{company_id}/alerts/low-stock

Included:
- Warehouse-level alert logic
- Supplier information for reordering
- Edge case handling
- Scalability considerations
- Assumptions and tradeoffs

---

## Included Files
- Detailed formatted case study submission document (PDF/DOCX)
- README summary

---

## Notes
Where requirements were intentionally incomplete, I documented assumptions and reasoning explicitly, focusing on correctness, maintainability, and practical backend design decisions.
