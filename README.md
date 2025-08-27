# Simple-Job-Application-Management-System
Title: Simple Job Application Management System Tech: PHP, MySQL, Bootstrap  Features:  Candidate can apply for a job (form submission → DB).  Recruiter can view applications in a table.  CRUD (Add, View, Delete applications).  Bonus: Add search by job title/email.
1. Introduction

Purpose: A web-based platform for employers to post jobs and candidates to apply with resumes. System extracts candidate skills from resumes using a parsing module.

Scope: Job seekers create profiles, upload resumes. Employers post jobs, filter applicants by skills. Admin monitors overall system.

Users: Job Seeker, Employer, Admin.

2. Functional Requirements

User registration & login (Employer/Job Seeker).

Job posting by employers.

Resume upload by candidates.

Resume parser extracts name, email, phone, skills.

Skill-based job recommendation.

Employer shortlists candidates.

Admin manages users & job listings.

3. Non-Functional Requirements

Secure authentication (hashed passwords).

Scalability: Should support multiple job listings.

Availability: Web app accessible 24/7.

Usability: Simple UI with Bootstrap.

4. System Models

Database:

Users (id, name, email, password, role)

Jobs (id, title, description, employer_id, skills_required)

Applications (id, job_id, user_id, parsed_skills, status)
