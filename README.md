# RevaP1
## Description
The Expense Reimbursement System (ERS) will manage the process of reimbursing employees for expenses incurred while on company time. All employees in the company can login and submit requests for reimbursement and view their past tickets and pending requests. Finance managers can log in and view all reimbursement requests and past history for all employees in the company. Finance managers are authorized to approve and deny requests for expense reimbursement.

## Technologies Used
- JavaScript
- HTML
- CSS
- SQL
- Java
- Javalin
- Mockito
- JUnit

## Features
- Manager can approve/deny requests
- Once created, expenses cannot be deleted
- Easy to navigate menu
- Employes and managers can submit expenses
- Managers cannot approve/deny their own expenses
- JWT security tokens
- Username and password protected access

## Usage
compile: `./gradlew fatJar`  
run: `java -jar {appname}.java`  

To view webpage, navigate to the ClientSideTech directory in the project home directory. Copy the path to the login.html. It should appear similar to, file:///C:/Users/<user name>/<home project directory name>/ClientSide/login.html Once Gradle has built and javalin server is running, open Google Chrome Web Browser and go to the file path above. From there, a valid user can login with credientials and begin using the prorgram.
