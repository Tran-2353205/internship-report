---
title: "Week 8 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---

### Week 8 Objectives:

* Begin the backend implementation of the Library Management Website project using Django.
* Set up the Django project structure and connect it to the database.
* Implement the core Django apps and expose them as RESTful APIs with Django REST Framework.
* Apply the AWS knowledge acquired during the training to the development process.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| T2 | - Initialize the Django project structure in the GitHub repository <br>&emsp;+ Create the Django project and the initial apps (books, readers, accounts) <br>&emsp;+ Set up development branches <br>&emsp;+ Agree on the Django coding conventions with the team | 27/07/2026 | 27/07/2026 | Team Discussion |
| T3 | - Set up the Django development environment <br>&emsp;+ Configure Docker and Docker Compose <br>&emsp;+ Define the Django models and run makemigrations/migrate <br>&emsp;+ Connect Django to the database via Django ORM | 28/07/2026 | 28/07/2026 | Team Discussion |
| T4 | - Develop the Book Management module <br>&emsp;+ Book model, serializer, and DRF viewset (CRUD) <br>&emsp;+ Category model, serializer, and DRF viewset (CRUD) <br>&emsp;+ Test the core APIs with Postman | 29/07/2026 | 29/07/2026 | Team Discussion |
| T5 | - Develop the Reader Management module <br>&emsp;+ Reader model, serializer, and DRF viewset (CRUD) <br>&emsp;+ User Account Management API (Django's authentication system) <br>&emsp;+ Perform integration testing between Django and the database | 30/07/2026 | 30/07/2026 | Team Discussion |
| T6 | - Attend the Sprint 1 review meeting <br> - Review the Django implementation progress <br> - Fix identified issues and update the backend development plan for the following week | 31/07/2026 | 31/07/2026 | Team Discussion |

### Week 8 Achievements:

* Completed the Django project initialization and configured the local development environment.

* Set up the Django project structure (apps for books, readers, and accounts) in the GitHub repository and agreed on a common development workflow with the team.

* Successfully configured Docker and Docker Compose and established a stable connection between Django and the database via the Django ORM.

* Developed the core backend functionalities of the system using Django REST Framework:
  * Book Management API
  * Category Management API
  * Reader Management API

* Successfully tested the core APIs with Postman and verified that data was stored and retrieved correctly through the Django ORM.

* Completed the first backend development sprint and identified the tasks to be carried out during the next phase of refinement.
