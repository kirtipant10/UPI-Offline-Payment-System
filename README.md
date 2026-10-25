UPI Without Internet — Offline Payment System

Overview
UPI Without Internet is a software project that explores how digital payments could work when an internet connection is unavailable. The project demonstrates an offline payment workflow using Java and Spring Boot, with a focus on secure communication, transaction handling, and reliable payment processing.

The system explores the concept of transferring payment information between devices through an offline communication mechanism. It is designed as a prototype to demonstrate the technical concepts involved in offline digital payments.

NOTE : 
This project is a prototype for educational and demonstration purposes. It is not an official UPI application and does not process real bank transactions.


Features
1. Offline Payment Workflow         :       Demonstrates a payment flow designed for situations without internet connectivity.
2. Secure Data Handling             :       Explores encryption techniques to protect sensitive payment information.
3. Spring Boot Backend              :       Uses Java and Spring Boot to implement backend functionality.
4. Transaction Processing           :       Demonstrates the handling of payment requests and transaction states.
5. Duplicate Transaction Protection :       Explores idempotency to help prevent the same transaction request from being processed multiple times.
6. Modular Architecture             :       Separates backend responsibilities into components for easier maintenance and development.


Tech Stack
1. Language                 :   Java
2. Backend Framework        :   Spring Boot
3. Build Tool               :   Maven
4. Security                 :   RSA-OAEP and AES-256-GCM encryption concepts
5. Development Environment  :   Visual Studio Code

The listed technologies and security mechanisms should be verified against the actual project implementation.


Prerequisites
Before running the project, install:
1. Java JDK 17
2. Visual Studio Code

Git (optional, for version control)
Getting Started

Clone the Repository
```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
```


Open the Project
Open the downloaded project folder in Visual Studio Code.


Verify Java Installation
Open the VS Code terminal and run:
```powershell
java -version
```
You should see the installed Java version.


Run the Application
If the project contains the Maven Wrapper file `mvnw.cmd`, run the following command in the project root directory:
```powershell
.\mvnw.cmd spring-boot:run
```
Alternatively, if Maven is installed on your system, you can run:

bash
mvn spring-boot:run
Wait for Spring Boot to finish starting. Check the terminal output for the application URL and any startup errors.


Security Considerations
Security is an important aspect of offline payment systems. This project explores concepts such as encryption, secure data exchange, and transaction deduplication.

However, a working prototype does not automatically guarantee production-level security. Real-world deployment would require extensive security testing, key management, transaction reconciliation, fraud prevention, and integration with authorized banking infrastructure.


Project Objectives
1. Explore the challenges of digital payments without continuous internet connectivity.
2. Understand backend development using Java and Spring Boot.
3. Study encryption concepts for protecting payment-related data.
4. Explore transaction processing and duplicate-request prevention.
5. Build a foundation for further experimentation with offline payment architectures.


Future Enhancements
1. Implement and test device-to-device communication.
2. Improve transaction verification and reconciliation.
3. Add comprehensive automated tests.
4. Develop a user-friendly interface for initiating and tracking payments.
5. Strengthen key management and security validation.
6. Evaluate the system under unreliable connectivity and device failure scenarios.


Disclaimer
This project is intended for learning, experimentation, and demonstration only. It is not affiliated with or endorsed by the National Payments Corporation of India (NPCI) or any bank. It must not be used to initiate real financial transactions.


Author
Kirti Pant
B.Tech — Computer Science and Engineering
GitHub: [kirtipant10](https://github.com/kirtipant10)
