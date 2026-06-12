# Peer Review Report

> **Instructions:** Complete this form **individually and independently**.
> Do not discuss your ratings with teammates before submitting.
> Submit via EEClass as a **separate, confidential submission** — not in the shared team repo.
> Your teammates will not see this report.
>
> Reference the team's `WORK_ALLOCATION_TEMPLATE.md` when completing this form.

---

## Your Details

| Field | Your answer |
|-------|------------|
| Full Name | 商逢育 |
| Student ID | 	113403513 |
| Team ID | Team 06 |
| Date submitted | 2026/6/12 |

---

## Rating Scale

| Rating | Meaning |
|--------|---------|
| **5** | Exceeded expectations — delivered more than agreed; helped teammates; consistently high quality |
| **4** | Met expectations fully — delivered exactly what was agreed; on time; good quality |
| **3** | Mostly met expectations — minor shortfalls; one or two items completed late or with help |
| **2** | Partially met expectations — noticeable gaps; teammates had to cover some tasks |
| **1** | Did not meet expectations — significant tasks left incomplete; very limited contribution |

---

## Section A — Self-Assessment

### A1. What did you personally implement?

List the specific tasks, functions, files, or document sections that you were the primary author of.
Be specific (e.g., "I designed all 12 tables in schema.sql and implemented query_national_rail_availability and execute_booking").

> *Your answer:*
I implemented the PostgreSQL data seeding logic and relational queries, and fixed the database schema and password storage. I also corrected the Neo4j labels (e.g., changing RailStation to NationalRailStation) and resolved Cypher syntax errors in graph queries. Furthermore, I addressed edge cases (B1 available_seats, B6 year_of_birth, C5 hops=0) and added inline code comments to meet the Code Quality marks. On the documentation side, I authored and updated the Work Allocation report and the Design Document (including adding ERD images). Lastly, I managed and resolved several complex Git merge conflicts.
---

### A2. What challenges did you face?

Describe any technical or collaboration difficulties you personally encountered and how you resolved them.

> *Your answer:*
The primary technical challenge was resolving complex Git merge conflicts when synchronizing multiple branches with origin/main. Additionally, debugging edge cases (such as handling hops=0 and year_of_birth constraints) and fixing Cypher syntax errors required significant time and repeated testing to ensure the database queries met the project specifications.

---

### A3. Self-rating

| Criterion | Rating (1–5) | Justification (1–2 sentences) |
|-----------|-------------|-------------------------------|
| I delivered the tasks assigned to me in the work allocation | 5 | I successfully completed the core PostgreSQL features, crucial bug fixes across both databases, and extensive documentation updates. |
| The quality of my work was satisfactory | 5 | My code passed all tested edge cases, and I ensured high code quality by adding comprehensive inline comments. |
| I communicated well and kept the team informed | 5 | I actively communicated with the team while resolving critical merge conflicts and 
| I met deadlines agreed within the team | 5 | I delivered all my code contributions and documentation files on schedule. |
| **Overall self-rating** | 5 | I successfully delivered my components and played a major role in integrating the system and fixing critical cross-module bugs. |


---

### A4. Estimated contribution percentage

What percentage of the total team effort do you estimate you personally contributed?

> My estimated contribution: **33%**

---

## Section B — Peer Assessments

Complete one subsection per teammate. Add or remove subsections to match your team size.
If your team has 2 members, complete B1 only. If 3 members, complete B1 and B2.

---

### B1. Assessment of Teammate 1

| Field | Your answer |
|-------|------------|
| Teammate's full name | 張靖賦 |
| Teammate's student ID | 113403051 |

#### What did this teammate deliver?

List the tasks, functions, files, or document sections that this teammate was the primary author of,
based on what you observed during the project (compare against the work allocation).

> *Your answer:*
He implemented the PostgreSQL seeders and missing schema tables, as well as the core Neo4j graph implementation (including seeding and 6 graph query functions). He also wrote comprehensive setup and test documentation. Moreover, he implemented the Task 6 extension (delay records), added the required `# TASK 6 EXTENSION:` comments to modified files, and wrote Sections 5, 6, and 7 of the Design Document.

#### Did their actual contribution match the agreed work allocation?
Yes. He perfectly delivered the Graph database features and successfully implemented the optional extension as planned.

> *Your answer (Yes / Mostly / Partially / No — with explanation):*

#### Peer rating for this teammate

| Criterion | Rating (1–5) | Justification (1–2 sentences) |
|-----------|-------------|-------------------------------|
| Delivered the tasks assigned in the work allocation | 4 | Delivered all assigned Neo4j functionalities and the complete Task 6 extension.
| Quality of their work was satisfactory | 4 | The code quality was high, supported by thorough setup documentation and clear extension comments. |
| Communicated well and kept the team informed | 4 | Provided clear commit messages and kept the team updated on the progress of the extension features. |
| Met deadlines agreed within the team | 4 | Finished all database seeding, graph queries, and document sections on time. |
| **Overall rating for this teammate** | 4 | An excellent contributor who secured the advanced features and bonus marks for the team. |

#### Estimated contribution percentage for this teammate

> My estimate of their contribution: **33%**

---

### B2. Assessment of Teammate 2

| Field | Your answer |
|-------|------------|
| Teammate's full name | 李庭宇 |
| Teammate's student ID | 113403523 |

#### What did this teammate deliver?

> *Your answer:*
He primarily managed version control and code review for the repository. He reviewed and merged multiple critical pull requests, including the password storage fix, the Neo4j label corrections, and the code-quality enhancements. He also ensured our main branch was successfully synchronized with the teaching repository's main branch.

#### Did their actual contribution match the agreed work allocation?

> *Your answer (Yes / Mostly / Partially / No — with explanation):*
Yes. He successfully managed branch integration, which was essential for maintaining a stable main branch while we developed in parallel.

#### Peer rating for this teammate

| Criterion | Rating (1–5) | Justification (1–2 sentences) |
|-----------|-------------|-------------------------------|
| Delivered the tasks assigned in the work allocation | 4 | Successfully handled code integration and pull request management. |
| Quality of their work was satisfactory | 4 | Ensured that merged code did not introduce regressions, maintaining system stability. |
| Communicated well and kept the team informed | 4 | Always communicated before merging major pull requests to prevent conflicts. |
| Met deadlines agreed within the team | 4 | Reviewed and merged branches promptly, never blocking the development pipeline. |
| **Overall rating for this teammate** | 4 | Provided excellent repository management, ensuring a smooth collaboration process for the whole team. |


#### Estimated contribution percentage for this teammate

> My estimate of their contribution: **34%**

---

## Section C — Contribution Percentage Summary

All members (including yourself) must sum to 100%.

| Member | Your estimated % | Notes |
|--------|----------------|-------|
| Yourself | 33% | |
| Teammate 1 | 33% | |
| Teammate 2 | 34% |  |
| **Total** | **100%** | |

---

## Section D — Overall Team Reflection

### D1. What went well in the team's collaboration?

> *Your answer (2–4 sentences):*
Our division of labor was highly effective and complementary. We had members specifically focusing on the relational database and documentation, the graph database and extensions, and repository management/integration. Utilizing Git branches and pull requests allowed us to develop in parallel safely and integrate all components smoothly at the end.

---

### D2. What would you do differently if you did this project again?

> *Your answer (2–4 sentences):*
If we did this project again, we would enforce strict Git configuration rules from the very beginning (e.g., ensuring everyone correctly sets their `user.name` and `user.email`). This would prevent multiple aliases (like default computer names) from appearing in the commit history and causing confusion. We would also increase communication prior to major structural changes to reduce merge conflicts.

---

### D3. Is there anything else the markers should know about team dynamics or individual contributions?

This is optional. Use it only if there is important context that the ratings above do not capture
(e.g., a member had a documented personal emergency, or a member was unresponsive for a significant period).

> *Your answer (or "Nothing to add"):*
Nothing to add.
---

## Declaration

I confirm that this peer review reflects my honest and independent assessment.
I understand it will be kept confidential from my teammates.

**Signed:** 商逢育 **Date:** 2026/6/12
