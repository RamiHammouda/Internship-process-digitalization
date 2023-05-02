# Praktikumsprozesses unter Verwendung des Bonita Workflow Frameworks

** Der Prozess des Praktikums ist ein Business Workflow, der in diesem Projekt bearbeitet werden soll. Dieser Prozess muss unter Verwendung des Bonita Frameworks implementiert werden. Der Prozess umfasst mehrere Schritte oder Aufgaben, die erledigt werden müssen, um den Bestätigungsprozess für das Fachpraktikum an der Hochschule abzuschließen.

# Motivation

** Die Digitalisierung von Verwaltungsabläufen ist in den letzten Jahren zu einem wichtigen Thema geworden. Die Einführung digitaler Lösungen kann verschiedene Vorteile mit sich bringen, wie z.B. effizientere Prozesse, schnellere Reaktionszeiten, bessere Datenverwaltung und höhere Transparenz. In diesem Zusammenhang wird dieses Projekt unter Verwendung des Bonita Frameworks entwickelt, um zu zeigen, wie Business-Workflow-Frameworks zu einer besseren Produktivität aus allen Perspektiven führen.

<img src="https://i.ibb.co/6Fm9832/Screenshot-2023-05-02-174203.png" width="550" title = "screenshot">

# Technologie-Stack: 
- Bonita: Eine Open-Source-Plattform für BPM und
Workflow-Automatisierung 
- Java: Die primäre Programmiersprache für die
Entwicklung von Bonita-Prozessen 
- SendinBlue SMTP-Server: Ein
E-Mail-Server, der ausgehende E-Mail-Nachrichten für die Bonita-Prozesse
verarbeitet

# Feature-Liste 
- [x] Die Anwendung ist eine Webanwendung, die ein Open-Source-BPM-Framework verwendet 
- [x] Die Anwendung hat mehrere Benutzer, denen die Aufgaben (Tasks) zugewiesen werden sollen 
- [x] Der BPM-Prozess läuft automatisch und weist die richtige Aufgabe an den richtigen Benutzer zu 
- [x] Benutzer können Daten über Dateneingaben (Data Inputs) auf verschiedenen Webseiten durch die Interaktion mit der Webanwendung bereitstellen 
- [x] Benutzer können Daten über Dateneingaben (Data Inputs) auf verschiedenen Webseiten durch die Interaktion mit der Webanwendung bereitstellen 
- [x] Eine automatisch ausgelöste E-Mail wird an jeden Benutzer gesendet, wenn er eine ausstehende Aufgabe hat 
- [x] Am Ende des gesamten Prozesses wird eine E-Mail an das Prüfungsamt gesendet, nachdem die erforderliche Validierung durch das Hochschulpersonal erfolgt ist 
- [x] Es wird möglich sein, der Webanwendung Anhänge hinzuzufügen, die in der Datenbank gespeichert und zwischen den verschiedenen Webseiten weitergegeben werden, wie zum Beispiel PDF- oder Textdateien 
- [x] Dieser Anhang wird, wenn vorhanden, in den gesendeten E-Mails am Anfang einer bestimmten Aufgabe angehängt

# Test-E-Mails: 
- rami.bachelorarbeit@gmail.com - pw: Test123456789**

- rami.bachelorarbeit@gmail.com - pw: Test123456789**

- betreuer1.bachelorarbeit@gmail.com - pw: Test123456789*

- betreuer2.bachelorarbeit@gmail.com - pw: Test123456789*

- betreuer3.bachelorarbeit@gmail.com - pw: Test123456789*

# SMTP-Konfiguration: 
- SMTP Server: smtp-relay.sendinblue.com 
- Port:587 
- Login: rami.bachelorarbeit@gmail.com 
- Passwort: xsmtpsib-a5c4598fd4e649b96a29f7a0b8e54151404527ed17edc3dfd65a3871e578eec9-zx6wWqtRmCP7fkIO

# E-Mail SMTP Server einrichten:

1) Melden Sie sich bei Ihrem sendinblue-Konto auf https://app.sendinblue.com/ an.

2) Navigieren Sie zu SMTP & API und stellen Sie sicher, dass das SMPT mit dem Namen "bachelorarbeit" aktiv ist, andernfalls setzen Sie es auf aktiv

# So führen Sie das Projekt aus:

1) Installieren Sie Bonita Studio 7 https://www.bonitasoft.com/downloads

2) Laden Sie die .bos-Datei herunter

3) Klicken Sie in der Bonita App auf \"Datei\", \"Projekt importieren\" und suchen Sie die .bos Datei

4) Klicken Sie auf "Weiter" und warten Sie, bis das Projekt importiert wurde (stellen Sie sicher, dass Sie die UNI-Organisation auswählen und "0571352" der Standard-Benutzername ist)

5) Die bonita-Webseite wird im Browser geöffnet, wo der Prozess mit dem Standardbenutzer "0571352" getestet werden kann.

6) Gehen Sie auf die Registerkarte "Prozesse" und starten Sie den Prozess mit dem Namen "Praktikum" (Testen Sie die Erledigung verschiedener Aufgaben durch Ab-und Anmelden mit verschiedenen Benutzern und die Testadressen überprüfen)

# Bonita Standardbenutzer: 
- 0571352 		- pw: 123 		- email: rami.bachelorarbeit@gmail.com 
- Erik.Rodner 		- pw: 123 		- email: erik.bachelorarbeit@gmail.com 
- Betreuer1 		- pw: 123 		- email: betreuer1.bachelorarbeit@gmail.com 
- Betreuer2 		- pw: 123 		- email: betreuer2.bachelorarbeit@gmail.com 
- Betreuer3 		- pw: 123 		- email: betreuer3.bachelorarbeit@gmail.com

- Hinweis: Die Benutzerliste, die Liste der Benutzernamen und die jedem Benutzer zugewiesenen E-Mails sind auf Standard-E-Mails eingestellt und können auf der Registerkarte "Organisationen" auf die benötigten
Korrespondenten geändert werden

# License
**MIT** © **HTW Berlin - IngenieurInformatik WS22** - **Rami Hammouda**
