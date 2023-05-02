# Praktikumsprozesses unter Verwendung des Bonita Workflow Frameworks

** The process of the internship is a business workflow that would be worked on in this project. This process needs to be implemented using Bonita framework. The process includes several steps or tasks that need to be completed in order to complete the subject internship confirmation process in the university.

# Motivation
The digitization of administrative workflows has become an important topic in recent years.The introduction of digital solutions can bring various benefits, such as more efficient processes, faster response times, better data management and greater transparency. In this context, this project will be developed using the Bonita Framework to show how Business workflow frameworks lead to a better productivity from all angles.

<img src="https://i.ibb.co/6Fm9832/Screenshot-2023-05-02-174203.png" width="550" title = "screenshot">


# Technology stack:
- Bonita: An open-source BPM and workflow automation platform
- Java: The primary programming language used to develop Bonita processes
- SendinBlue SMTP Server: An email server that handles outgoing email messages for the Bonita processes

# Feature List
- [x] The application is a web application that uses an open source BPM framework
- [x] The application has multiple users to whom the tasks (Tasks) are to be assigned
- [x] The BPM process runs automatically and assigns the right task to the right user
- [x] Users can provide data through data inputs (Data Inputs) on different web pages by interacting with the web application
- [x] The data provided by the different users is stored in a database and can be controlled by a database management system
- [x] An automatically triggered email is sent to each user when they have a pending task
- [x] At the end of the whole process, an email will be sent to the examination office after the required validation has been done by the university staff
- [x] It will be possible to add attachments to the web application, which will be stored in the database and passed between the different web pages, such as PDF or text files
- [x] This attachment, if any, will be included in the sent e-mails at the beginning of a given task


# Testing Emails:
- rami.bachelorarbeit@gmail.com				pw: Test123456789**

- rami.bachelorarbeit@gmail.com				pw: Test123456789**

- betreuer1.bachelorarbeit@gmail.com   		 	pw: Test123456789*

- betreuer2.bachelorarbeit@gmail.com			pw: Test123456789*

- betreuer3.bachelorarbeit@gmail.com			pw: Test123456789*

# SMTP configuration:
- SMTP Server:	smtp-relay.sendinblue.com
- Port:	        587
- Login:	rami.bachelorarbeit@gmail.com
- Passwort: xsmtpsib-a5c4598fd4e649b96a29f7a0b8e54151404527ed17edc3dfd65a3871e578eec9-zx6wWqtRmCP7fkIO


# Email SMTP Server setup:

1) Login to sendinblue account on https://app.sendinblue.com/

		rami.bachelorarbeit@gmail.com				pw:Rami123456789

2) Navigate to SMTP & API and make sure the SMPT with the name "bachelorarbeit "is active otherwise set it to active

# How to run the project:

1) Install Bonita 7.15

2) Download the .bos file

3) Click on "File" in the Bonita App, "Import Project" and browse to the .bos file

4) Click on next and wait for the project to be imported(make sure to choose the UNI.organization and "0571352" is the default username)

5) The bonita web page will be opened on the browser where the process can be tested with the default user logged in.

6) Go to "Processes" tab and start the process with the name "Praktikum"


- Note: The user list, usernames list and emails assigned to each user are set to default emails and can be edited to the needed correspondents in the Organizations tab

# License
**MIT** © **HTW Berlin - IngenieurInformatik WS22** - **Rami Hammouda**


