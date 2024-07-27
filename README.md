Appointment Management Project

--> The Appointment Management Project files are located in "apollo.fastappointments" repository.

--> apollo.fastappointments is a spring MVC based web project that I created using spring/spring-boot framework, thymeleaf and postgresql database. 

--> A user can be the admin, patient or a doctor. Admin can administer patients and doctors on the website, Patients can login and schedule appointments with doctors and Doctors can monitor and manage their respective appointments with patients.

--> 3 Database tables work in the backend, one is "patient" which holds the patient information, another is "doctor" which holds the doctor information and lastly "appointments" which holds data of appointments of patients with doctors. The "appointments" database table represents m:n relation between patient and doctor entities where one patient can schedule appointments with multiple doctors and multiple patients can schedule appointments with one doctor.

--> Thus appointment management system provides a foundational prototype for large scale hospital appointment management systems.
