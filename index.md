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
| 2 | Tu 9/6 | 4. [Subqueries and Aggregation](https://docs.google.com/presentation/d/1H1B4Tx3FaxzOHNaKQkYpbTHXj_37Uo56/edit?usp=sharing&ouid=101709100734010871255&rtpof=true&sd=true) ([Recording](https://drive.google.com/file/d/1TNQffowL1IuRmSKMi91asb8D5hlGjCb1/view?usp=sharing), [Note](./resources/assets/notes/2.pdf))| | |
|  | Th 9/8 | 5. [Window Functions, Sampling, String Manipulation](https://docs.google.com/presentation/d/14nlI3Bov_LR7-JRYVEEHtke6YbNYW7ci/edit?usp=sharing&ouid=101709100734010871255&rtpof=true&sd=true) ([Recording](https://drive.google.com/file/d/1T0Q9mPb0cpek3sSx17d2GIoq54ybfndk/view?usp=sharing)) | | [Project 1](https://data101.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fcal-data-eng%2Ffa22&urlpath=tree%2Ffa22%2Fproj%2Fproj1%2Fproj1.ipynb&branch=main) (due 9/23) |
| 3 | Tu 9/13 | 6. [Updates, DDL, Referential Integrity, Constraints](https://docs.google.com/presentation/d/1CwLqU6vLo_onqtI-AGekMDhp28XxquuE/edit?usp=sharing&ouid=101709100734010871255&rtpof=true&sd=true) ([Recording](https://drive.google.com/file/d/1Ellx0gec7s4kRzb2qoEk9AgDVTlL31Zz/view?usp=sharing), [Note](./resources/assets/notes/3.pdf)) | [Discussion 1](https://drive.google.com/file/d/1xjwN6K9sexbh-l-VH0WsYILcdWlYgawI/view?usp=sharing) ([Slides](https://drive.google.com/drive/folders/1GRQa38gl36EToOETKUWgmLVyZVw-awuV?usp=sharing)) ([Solutions](https://drive.google.com/file/d/1sB0CTwCyuTaw87TIlaAmWK_Ac9Z4ce6b/view?usp=sharing)) | |
|  | Th 9/15 | **No Lecture** | | [Multivitamin 1](https://www.gradescope.com/courses/421137/assignments/2255543) (due 9/30) |
| 4 | Tu 9/20 | 7. [Foreign Keys, Index Selection](https://docs.google.com/presentation/d/1gfm0CVfotsOSB2jLkgCqvDPXkcNqWVlD/edit?usp=sharing&ouid=115426255420868042566&rtpof=true&sd=true) ([Recording](https://drive.google.com/file/d/1TA-OL6M5WCtVUhoxtFUXabfRfwPisWpL/view?usp=sharing), [Note](./resources/assets/notes/4.pdf)) | [Discussion 2](https://drive.google.com/file/d/15lBP4k3Kd0LqTh8-6JWOOHXmslfRE0DK/view?usp=sharing) ([Slides](https://drive.google.com/drive/folders/1GRQa38gl36EToOETKUWgmLVyZVw-awuV?usp=sharing)) ([Solutions](https://drive.google.com/file/d/1LUfpMVKVlOKLb-iha9K3TzhzDFJ6KfpJ/view?usp=sharing)) | |
|  | Th 9/22 | 8. [Index Selection, Query Processing & Optimization](https://docs.google.com/presentation/d/1wvhl7XgnyWsBpwRbz1TREMOVXDs5VxVb/edit?usp=sharing&ouid=101709100734010871255&rtpof=true&sd=true) ([Recording](https://drive.google.com/file/d/1iF2sLlHB1Z_-J2ECgof2wkjHceJj2Pj2/view?usp=sharing)) | | [Project 2](https://data101.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fcal-data-eng%2Ffa22&urlpath=tree%2Ffa22%2Fproj%2Fproj2%2Fproj2.ipynb&branch=main) (due 10/7) |
| 5 | Tu 9/27 | 9. [Query Processing & Optimization (II)](https://docs.google.com/presentation/d/1JV3lYNAydpJuHD4uAy1xX87WirvLwiHo/edit?usp=sharing&ouid=101709100734010871255&rtpof=true&sd=true) ([Recording](https://drive.google.com/file/d/1Gld5M6vlNoHRJhHAVLH_4hCUx08NRZGP/view?usp=sharing)) | [Discussion 3](https://drive.google.com/file/d/1ST-uzv0m_CKhHzrXuIDO3tFIQoOeoYCt/view?usp=sharing) ([Slides](https://drive.google.com/drive/folders/1GRQa38gl36EToOETKUWgmLVyZVw-awuV?usp=sharing)) ([Solutions](https://drive.google.com/file/d/1Nrds39H71Ko083cTiXaThU_HidOY5ROp/view?usp=sharing)) | |
|  | Th 9/29 | 10. [Relations, Tensors and Dataframes](https://docs.google.com/presentation/d/1W_LMiZQb5U5-nfK8iI3S7kEpSovgSMjw/edit?usp=sharing&ouid=101709100734010871255&rtpof=true&sd=true) ([Recording](https://drive.google.com/file/d/1Ji9oGGTwxTxPWPS_4JA6I2d54KM-8DCV/view?usp=sharing), [Note](./resources/assets/notes/5.pdf)) | | [Multivitamin 2](https://www.gradescope.com/courses/421137/assignments/2273057) (due 10/14) |
| 6 | Tu 10/4 | 11. [Data Preparation](https://drive.google.com/file/d/1HmRG4o2OlIpiU--ROtxI5f4TidJSTVUt/view?usp=sharing) ([Recording](https://drive.google.com/file/d/16gqL85BBLu66IK7m7wYKd--jpDefFz27/view?usp=sharing)) | [Discussion 4](https://drive.google.com/file/d/1biCy2CpBCcS7O9u0c7uOSm0vpaLfHlXu/view?usp=sharing) ([Slides](https://drive.google.com/drive/folders/1GRQa38gl36EToOETKUWgmLVyZVw-awuV?usp=sharing)) ([Solutions](https://drive.google.com/file/d/1P5GMu36PLOVVkpWRD5D1970rlFIovJ3M/view?usp=sharing)) | |
|  | Th 10/6 | 12. [Data Preparation (II)](https://drive.google.com/file/d/1HmRG4o2OlIpiU--ROtxI5f4TidJSTVUt/view?usp=sharing) ([Recording](https://drive.google.com/file/d/1h6L3l_2DoDGD_WYwySQharAuE3sHbNS7/view?usp=sharing), [Note](./resources/assets/notes/6.pdf)) | | [Multivitamin 3](https://www.gradescope.com/courses/421137/assignments/2322741/) (due 10/28) |
| 7 | Tu 10/11 | 13. [Data Cleaning](https://drive.google.com/file/d/1LIpgjGyN8m1hdKL1kC-Uix0Ha4pRwxh-/view?usp=sharing) ([Recording](https://drive.google.com/file/d/1dzK3laERjYwRrF08lwQqQQY8pqSGqShH/view?usp=sharing)) | [Discussion 5](https://drive.google.com/file/d/1Uxwk16h7CvPj_Phebpono9xAStt4POl5/view?usp=sharing) ([Slides](https://drive.google.com/drive/folders/1GRQa38gl36EToOETKUWgmLVyZVw-awuV?usp=sharing)) ([Solutions](https://drive.google.com/file/d/196zt3BtuVlgSRSksGjwSeFtrvdDkPn18/view?usp=sharing)) | |
|  | Th 10/13 |  14. [Data Cleaning (II)](https://drive.google.com/file/d/1LIpgjGyN8m1hdKL1kC-Uix0Ha4pRwxh-/view?usp=sharing) ([Recording](https://drive.google.com/file/d/1-lAdmLxq1D5-7On8WHEt98Mq5UjW-KVu/view?usp=sharing), [Note](./resources/assets/notes/7.pdf)) | | [Project 3](https://data101.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fcal-data-eng%2Ffa22&urlpath=tree%2Ffa22%2Fproj%2Fproj3%2Fproj3.ipynb&branch=main) (due 10/28) |
| 8 | Tu 10/18 | 15. [Normalization and ER](https://docs.google.com/presentation/d/1GogwyAylHrJoxer_apIkgnWDqC9LxTQ8/edit?usp=sharing&ouid=101709100734010871255&rtpof=true&sd=true) ([Recording](https://drive.google.com/file/d/1oe8IuMpwayJEoWOxY8Zpv1ruinE_VrBs/view?usp=sharing))| [Discussion 6](https://colab.research.google.com/drive/1DMVvMz3qUnP5nMrOnL0LA4dwoYQ4yn-c?usp=sharing) ([Slides](https://drive.google.com/drive/folders/1GRQa38gl36EToOETKUWgmLVyZVw-awuV?usp=sharing)) ([Solutions](https://colab.research.google.com/drive/1KQfZAXMMYbKOoXczu8yUOYfzO3YsRpKZ?usp=sharing)) | |
|  | Th 10/20 | 16. [NoSQL & Semistructured Data](https://docs.google.com/presentation/d/1ns2-alpBdQ0dnMs_YWhEBwgr-nYx05ufWgr9SGTGAfc/edit) ([Recording](https://drive.google.com/file/d/19lFU3Hb8d2XI1c7zwAQ0aTsRqFaT3Y4A/view?usp=sharing))| | [Multivitamin 4](https://www.gradescope.com/courses/421137/assignments/2362462) (due 11/4) |
| 9 | Tu 10/25 |17. [Querying Semistructured Data](https://docs.google.com/presentation/d/1WmX_haSo2rymN5cRjGIMXO-glBz2jo3d/edit?usp=sharing&rtpof=true&sd=true) ([Notebook](https://drive.google.com/file/d/1AEtgHVQSrIjRT4qDMjnR5q9mNRCdrJvj/view?usp=sharing)) ([Recording](https://drive.google.com/file/d/1m8yOKZ93VZYGnCL1ZvdWZ3Ke8HyIEfgm/view?usp=sharing)) | [Discussion 7](https://drive.google.com/file/d/1b0-6krjHOQBEkXxrr6yYPkWrDO0eYPXy/view?usp=sharing) ([Slides](https://drive.google.com/drive/folders/1GRQa38gl36EToOETKUWgmLVyZVw-awuV?usp=sharing)) ([Solutions](https://drive.google.com/file/d/1AaXKBTTu1hE14iV2-agHQaebTV6jo66I/view?usp=sharing)) | [Mid-Semester Survey](https://forms.gle/iYoxLkqadXW8sEWB7) (due 11/4) |
|  | Th 10/27 | 18. [Querying Semistructured Data (II)](https://docs.google.com/presentation/d/1WmX_haSo2rymN5cRjGIMXO-glBz2jo3d/edit?usp=sharing&rtpof=true&sd=true) ([Recording](https://drive.google.com/file/d/12080DlcGWIOGCgubbmSu-TAD8cMB3gFn/view?usp=sharing), [Note](./resources/assets/notes/9.pdf)) | | [Project 4](https://data101.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fcal-data-eng%2Ffa22&urlpath=tree%2Ffa22%2Fproj%2Fproj4%2Fproj4.ipynb&branch=main) (checkpoint 11/10, due 11/18) |
| 10 | Tu 11/1 | 19. [SQL Modifications, Transactions and Recovery](https://docs.google.com/presentation/d/14u7_0M7ZniHTsUip2yFOLzOVgnV_MJgS/edit?usp=share_link&ouid=101709100734010871255&rtpof=true&sd=true) ([Recording](https://drive.google.com/file/d/18o7TEb7egc8SrgRyax0M8TNBBmE2jgyR/view?usp=share_link), [Note](./resources/assets/notes/8.pdf)) | [Discussion 8](https://drive.google.com/file/d/1qUQe1kOpkQ_reXstN-0MAFD4EUFuwjoc/view?usp=share_link) ([Slides](https://drive.google.com/drive/folders/1GRQa38gl36EToOETKUWgmLVyZVw-awuV?usp=sharing)) ([Solutions](https://drive.google.com/file/d/1bvjOa2iauJWuMcmacB6Ec4I0oXHeRk0X/view?usp=share_link)) | |
|  | Th 11/3 | 20. [Parallel and Distributed Computing](https://drive.google.com/file/d/1cx4WY76STJb6y97OKXjIpUTbl66wjmif/view?usp=share_link) ([Recording](https://drive.google.com/file/d/1QF58Bp9k90Cd2KtOZSZ4n-s7sxpNMUy-/view?usp=share_link)) | | [Multivitamin 5](https://www.gradescope.com/courses/421137/assignments/2404589) (due 11/18) |
| 11 | Tu 11/8 | **No Lecture (Election Day)** | [Discussion 9](https://drive.google.com/file/d/1Zdnc_EA28VjSV8uCPnj8EE-Yv5sZiaDi/view?usp=sharing) ([Slides](https://drive.google.com/drive/folders/1GRQa38gl36EToOETKUWgmLVyZVw-awuV?usp=sharing)) ([Solutions](https://drive.google.com/file/d/1CuQzVDQrQzcUBaIn52-Y8Y3JaNVLvx9X/view?usp=sharing)) | |
|  | Th 11/10 | 21. [Data Pipelines](https://docs.google.com/presentation/d/1qb_s6qW1Ya2CozM-5FD-BrDf8M7s8bBT/edit?usp=sharing) | | |
| 12 | Tu 11/15 | 22. Storage Types | [Discussion 10](https://drive.google.com/file/d/1jvaDGW2pkzEbN53U_8ms_ZNTN-JdxbX5/view?usp=share_link) ([Solutions](https://drive.google.com/file/d/1bXINfHWTIpPuePFgwMHOVGtshYDytPWX/view?usp=share_link)) | Project 5 (due 12/2) |
|  | Th 11/17 | 23. ML: Model Training, Serving, and Monitoring | | |
| 13 | Tu 11/22 | **No Lecture (Thanksgiving)** | | |
|  | Th 11/24 | **No Lecture (Thanksgiving)** | | |
| 14 | Tu 11/29 | 24. Distributed Transactions | | |
|  | Th 12/1 | Closing Thoughts | | |
| 15 | Tu 12/6 | **RRR Week** | | |
|  | Th 12/8 | **RRR Week** | | |
| 16 | Th 12/15 | **Final Exam (11:30am - 2:30pm)** | | |
