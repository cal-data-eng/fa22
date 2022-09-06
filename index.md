---
layout: page
title: Home
nav_order: 1
description: A week-to-week description of the content covered in the course.
---

<link rel="stylesheet" href="css/index.css">

# Data Engineering
{: .mb-2 }
UC Berkeley, Fall 2022
{: .mb-0 .fs-6 .text-grey-dk-000 }

<div>

{% assign instructors = site.staffers | where: 'role', 'Instructor Home' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}

</div>

Welcome to the first official offering of Data 101! The schedule and dates listed below are tentative and may be subject to change. Check out the syllabus for course information.

</div>

<br>

| Week | Date | Lecture | Discussion | Assignment |
| :--: | :--: | :--: | :--: | :--: |
| 0 | Th 8/25 | 1. [Introduction & Data Science Lifecycle](https://docs.google.com/presentation/d/1Gt1-JjGJfBlEAXjjrYehG-SBz5_Z03Ba/edit?usp=sharing&rtpof=true&sd=true) ([Recording](https://drive.google.com/file/d/1oFiC7cLAOT42-lOsfkKxaJw2-0cnZstB/view?usp=sharing)) | | [Pre-semester Survey](https://docs.google.com/forms/d/e/1FAIpQLSclpNZ2_prU96JD9Uz59EU3Pk9-1gWQDmvpaBBxQtKUlA8rew/viewform) |
| 1 | Tu 8/30 | 2. [Relational Model & Algebra](https://docs.google.com/presentation/d/1bkp06s17Z5v5zZI4QPaoqFyX3VEWSU8w/edit?usp=sharing&ouid=104245339946787511318&rtpof=true&sd=true) ([Recording](https://drive.google.com/file/d/15s_RF0qYY2MJq6BVGk7zT8AiqkDOuTC4/view?usp=sharing)) | | |
|  | Th 9/1 | 3. [SQL Intro](https://docs.google.com/presentation/d/1RdDhxbL73BLpgxPR86qZ5JWT6uEZsKpU/edit?usp=sharing&ouid=115426255420868042566&rtpof=true&sd=true) ([Recording](https://drive.google.com/file/d/1Kt7NASzW8rWYRpHxHTzNVki5PjaPv4lE/view?usp=sharing), [Note](./resources/assets/notes/1.pdf))| | |
| 2 | Tu 9/6 | 4. Views | | |
|  | Th 9/8 | 5.  Subqueries and Aggregation | | Project 1 (due 9/23) |
| 3 | Tu 9/13 | 6. Window Functions, Sampling, String Manipulation | | |
|  | Th 9/15 | 7. Updates, DDL, Referential Integrity, Constraints | | Multivitamin 1 (due 9/30)|
| 4 | Tu 9/20 | 8. Index Selection, Query Processing & Optimization | | |
|  | Th 9/22 | 9. Index Selection, Query Processing & Optimization (II) | | Project 2 (due 10/7) |
| 5 | Tu 9/27 | 10. Relations, Tensors, Dataframes | | |
|  | Th 9/29 | 11. Relations, Tensors and Dataframes (II) | | Multivitamin 2 (due 10/14) |
| 6 | Tu 10/4 | 12. Data Preparation | | |
|  | Th 10/6 | 13. Data Preparation (II) | | Project 3 (due 10/21) |
| 7 | Tu 10/11 | 14. Data Cleaning | | |
|  | Th 10/13 |  15. Data Cleaning (II) | | Multivitamin 3 (due 10/28) |
| 8 | Tu 10/18 | 16. Normalization and ER | | |
|  | Th 10/20 | 17. Semistructured Data | | |
| 9 | Tu 10/25 | 18. Querying Semistructured Data | | |
|  | Th 10/27 | 19. Spreadsheets | | Project 4 (due 11/11) |
| 10 | Tu 11/1 | 20. Graph Data: Property Graph Models, Triples/RDF | |
|  | Th 11/3 | 21. SQL Modifications, Transactions and Recovery | | Multivitamin 4 (due 11/18) |
| 11 | Tu 11/8 | **No Lecture (Election Day)** | | |
|  | Th 11/10 | 22. Data Pipelines | | |
| 12 | Tu 11/15 | 23. Storage Types | | Project 5 (due 12/2) |
|  | Th 11/17 | 24. ML: Model Training, Serving, and Monitoring | | |
| 13 | Tu 11/22 | 25. Parallelization: Map-Reduce, Spark, Parallel DBMS, Dask/Modin | | Multivitamin 5 (due 12/2) |
|  | Th 11/24 | **Thanksgiving Break** | | |
| 14 | Tu 11/29 | 26. Distributed Transactions | | |
|  | Th 12/1 | Closing Thoughts | | |
| 15 | Tu 12/6 | **RRR Week** | | |
|  | Th 12/8 | **RRR Week** | | |
| 16 | Th 12/15 | **Final Exam (11:30am - 2:30pm)** | | |
