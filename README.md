<h1>Medical Scheduling System</h1>

<h2>Description</h2>


For my capstone project, I was tasked with enhancing a previous project or creating a new project. I chose to improve the scheduling system. It had previously been used as a class scheduler. It required UI/UX updates to build a database using MySQL and code changes for interactions. It can detect the system language and translate the screens; currently, it supports English, Spanish, and French. Functions for a database of patients and appointments, as well as a reporting feature, are included. The user can add, update, and delete patients and appointments. If a patient has an appointment, they can not be deleted. It provides a feature to detect the system time zone and translate times, and when saving them, it logs them in the database as EST time. The system has built-in validation for the constraints of 8 am and 10 PM business hours. It also validates that all sections are filled in. The project uses FXML to design the layouts in IntelliJ IDEA and Java code to manipulate the data and buttons.

<h3>Uses</h3>



The project is a scheduling system that could be utilized by a medical facility. It is adaptable to other functions with minor tweaks to the UI/UX. It has the ability to create,delete and modify patient records and appointments. It can run reports for how many times a patient has been seen, how many appointments are for that week or month. It also has a report for how many appointments a specific user has. It has login validation to protect unwanted access as well as masks password while typing. By utilizing the MySQL database new users could be added or removed upon seperation. A patient can not be deleted if there are associated appointments for them. Future updates could include screens to add or remove users without having to directly access the database. 


![Login](https://github.com/user-attachments/assets/0f2ab65a-43aa-434e-83d0-f9ea988a2193)


<h4>Technologies</h4>


The layout is FXML using the built in scenebuilder in IntelliJ IDEA. The code used is Java.
