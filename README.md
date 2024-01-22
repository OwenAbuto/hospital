
# Hospital Management

# Software Development Project.

 - This is a simple hospital management system implemented in Python and HTML, designed to help healthcare professionals manage patient records and identify patients efficiently, as well as manage traffic between patients and doctors for a Software Development Course.

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

# UML Diagrams
 - To enhance the understanding of the system's structure and behavior, UML diagrams have been created for the core classes: (Diagrams attached in the UML Diagrams folder)

- Class Diagram: Illustrates the relationships and attributes of the classes involved in the system.

- Activity Diagrams: Depict the workflows for user interactions and system operations

- Sequence diagrams: Interaction between objects in a simplified manner.

# Requirements Engineering
- Trello. https://trello.com/invite/b/3hH7ab2E/ATTI85ce7491f5828f31ac2e068fa4a8625f191259CE/olympus-project

- Atlassian. https://id.atlassian.com/invite/p/jira-software?id=JlS24y0bS4WjJJHFuwCRZw

# Usage
- Basic user management by users and advanced user management by administrator

- Report generation to users, hospitals, and doctors for seamless hospital management

- DDD Implementation

- Symptom inputs and generated outputs

# Developer
  - Owen Abuto Okoth 2023/2024.

---

