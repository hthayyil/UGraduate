# UGraduate

## Description

Overview: uGraduate is going to be an application that centralizes the current
in place systems students use to register. Students currently use 3 different
applications/systems to register for a semester. uAchieve, Register XE,
and uAdvise. All of the systems are not consistent and they are not centered
around the user experience. uGraduate will allow students to register, drop
classes, visually see all required courses through graduation in a tree like
fashion, and see available resources. All access control will be done through
administrators that have the ability to not only drop/add students to classes,
but they will indicate whether or not a student passes or fails a class and
updates the DB and GUI accordingly.

 ## Functionalities
 --Functionalities/Classes
 
 A user can register and login as either a student or admin. Students can: 
 
Register,
Search class,
See all the classes until graduation,
Unregister,
See available classes for registration,
See completed classes,
No. Seats availble for classes 

Admins can: 

Add students,
Add Classes,
Remove classes and students,
Update class completion,
Update class information,
Add other admins,
Remove other admins,

These classes are created in our DB for querying 

• Major
• Students
• Colleges
• Admins
• Classes

## Authors

| Member | Web dev level | Specialization |
| --- | --- | --- |
| Fabian Miranda Corpuz the Intermediate | Dabbled with a lot of Java and Spring MVC | Security. I want to learn how to properly utilize security in a non-trivial way. I will customize the IAM on AWS and use credential-less storing so we are not storing keys on the repo. 2f authentication. Since there is no incredibly obvious security solution for this registration system, I will designate all security aspects of the application as my specialization |
| Hanna Thayyil | Novice | --- |
| Jonathan Vega the Intermediate | Took IT202, flew through most content though.. | Front-end. Bootstrap, JQuery, React |
| Stephen Lambert | Novice | --- |


# Installation

AWS Deployment Instructions:
- Intall Intellij or Eclipse
- Import this project folder as a MAVEN project
- Run mvn clean package. This will create a directory called target and add folders and files inside. Inside the file, there is a .war file (not the .war.original). This is the file that will be used to deploy on the server
- On AWS, create a new instance of Elastic Beanstalk and upload the .war file from the project directory
- Good to go
