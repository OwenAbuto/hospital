
# Hospital Management

# Software Development Project.

 - This is a simple hospital management system implemented in Python and HTML, designed to help healthcare professionals manage patient records and identify patients efficiently, as well as manage traffic between patients and doctors for a Software Development Course.

 # UML Diagrams (No.2 in instructions)
 - To enhance the understanding of the system's structure and behavior, UML diagrams have been created for the core classes: (Diagrams attached in the UML Diagrams folder)

- Class Diagram: Illustrates the relationships and attributes of the classes involved in the system.

- Activity Diagrams: Depict the workflows for user interactions and system operations

- Sequence diagrams: Interaction between objects in a simplified manner.

# Requirements Engineering (No. 3 in instructions)
- Trello. https://trello.com/invite/b/3hH7ab2E/ATTI85ce7491f5828f31ac2e068fa4a8625f191259CE/olympus-project

- Atlassian. https://id.atlassian.com/invite/p/jira-software?id=JlS24y0bS4WjJJHFuwCRZw

# Analysis of System. (No. 4 in instructions)
- To correctly ensure that the system has met all the functions that it is supposed to, a pdf document named "Analysis Checklist for the Hospital Management System" has been attached. The checklist goes over both functional and non functional requirements of what a good system should be, and rates each item giving a score from 1-10 on the use, effectiveness and functionality of the system. 

# Domain Driven Design (DDD) (No.5 and 10 in instructions)
- From events mapping, to project mapping of the entire project, a web based IDE tool has been utilized known as "ContextMapper". This tool makes use of VSCode and shows mapping in the entire project. Screenshots of the tool in use are attached under the folder "Screenshots>ContextMapper tool"
- The tool hasn#t been fully utilized but has shown the basics of DDD as well as met the basic requirements. Other tools proved difficult to use with the project.

# Metrices used in the project (No.6 in requirements)
- The "CircleCI" tool has been used in this project for development. Unfortunately the original tool "SonarQube" did not run effectively and hence a substitute was used. The screenshots for this tool in use are located under the folder "Screenshots>CircleCI tool". Some errors came about but were resolved hence the build management showed no errors and bugs and issues fixed. 
- Link to the project tool can be found here: https://app.circleci.com/pipelines/circleci/35xbAuKJhaXhf3o2wacv6p

# Clean Code Development (No.7 in requirements)
- A cheat sheet for the project has been attached to the project under the name "CheatSheet(2).pdf". This cheat sheet has been self developed to ensure that the user is able to run the program effectively as well as utilize all functions and parameters of the system. 

# Build Management and Unit Tests (No. 8 and 9 in requirements)
- For the build Management, the tool "Codacy (Codebeamer)" has been used to call tests and test the structure, nature and functionality of the system, security as well provide a path for issues, trivial errors that may have been missed and provide a clean code for deployment. The screenshots can be found under the folder "Screenshots>Codacy tool"
- The link to the Codacy tool for this project can be found here : [![Codacy Badge](https://app.codacy.com/project/badge/Grade/c8ffd6f731e2456dbd0156f75c84679e)](https://app.codacy.com/gh/OwenAbuto/hospital/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)

# Functional Requirements
# Features/Characteristics
- Patient Registration: Medical services experts and non experts can enroll new patients and store their data safely.

- Patient Search: Effectively search and distinguish patients in view of their name, date of birth, or different rules.

- Patient Profiles: View point by point patient profiles, including clinical history, current prescriptions, and sensitivities.

- Client Authentication: Secure client validation for medical services experts.

- Security: Patient and Doctor information is put away safely with legitimate encryption and access controls.

- Information Reinforcement and Recovery: Normal information reinforcement and recuperation techniques to forestall information misfortune.

# Prerequisites
- Python 3.x
- HTML
- Django 3.0.5
- Django widget tweaks 1.4.8
- SQlite

## Functions

# Log In

- User Management: Create, edit, and delete user profiles, including essential information like name, address, symptoms, username and password.

- Symptom Input: Record a wide range of symptoms experienced by users, allowing for comprehensive symptom analysis.

- Report Generation: Generate detailed reports summarizing user symptoms, potential diagnoses, and preventive measures from Doctor analysis, as well as generate medical bill reports and invoices.

- Domain-Driven Design (DDD): Employ DDD principles to create a maintainable and scalable architecture, ensuring system robustness and flexibility.

- Communication with Doctors and Patients

- Communication with hospital

### Admin
- Signup their account. Then Login (No approval Required).

- Can register/view/approve/reject/delete doctor (approve those doctor who applied for job in their hospital).

- Can admit/view/approve/reject/discharge patient (discharge patient when treatment is done).

- Can Generate/Download Invoice pdf (Generate Invoice according to medicine cost, room charge, doctor charge and other charge).

- Can view/book/approve Appointment (approve those appointments which is requested by patient).

### Doctor
- Apply for job in hospital. Then Login (Approval required by hospital admin, Then only doctor can login).

- Can only view their patient details (symptoms, name, mobile ) assigned to that doctor by admin.

- Can view their discharged(by admin) patient list.

- Can view their Appointments, booked by admin.

- Can delete their Appointment, when doctor attended their appointment.

### Patient
- Create account for admit in hospital. Then Login (Approval required by hospital admin, Then only patient can login).

- Can view assigned doctor's details like ( specialization, mobile, address).

- Can view their booked appointment status (pending/confirmed by admin).

- Can book appointments.(approval required by admin)

- Can view/download Invoice pdf (Only when that patient is discharged by admin).

# Usage
- To see how the different users interact with each other, browse to the folder "Screenshots>Project screenshots test". Here you will see all folders of the admin class, patients class, and doctors class. 

- Basic user management by users and advanced user management by administrator

- Report generation to users, hospitals, and doctors for seamless hospital management

- DDD Implementation

- Symptom inputs and generated outputs

- All necessary tools are located in the requirements.txt file. 

- To run the program, a cheat sheet and screenshots have been attached for the entire procedure.

# Developer
  - Owen Abuto Okoth 2023/2024.

---

