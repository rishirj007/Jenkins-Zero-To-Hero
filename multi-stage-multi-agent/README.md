Jenkins Zero To Hero — Multi-Stage Multi-Agent Pipeline Example
This repository demonstrates a simple Jenkins pipeline that builds and runs a Java application using Maven, along with optional Node.js steps.

Project Structure
Java Backend: Simple Maven-based Java application located in
multi-stage-multi-agent/backend/src/main/java/com/example/App.java

Jenkins Pipeline: Declarative pipeline with stages for checkout, build, and run.

Java Application
The Java app is a basic "Hello World" program with the main class com.example.App.

Maven Commands Used
To compile the Java app:

bash
Copy
Edit
mvn clean compile
To run the Java app:

bash
Copy
Edit
mvn exec:java
Jenkins Pipeline Stages
Checkout SCM — Clones the GitHub repository.

Build Java — Runs Maven compile on the Java backend.

Run Java — Executes the Java application using Maven.

Install Node.js Packages — (Optional step for Node.js apps)

Run Node.js App — (Optional step for Node.js apps)

How to Run Locally
Navigate to the Java backend directory:

bash
Copy
Edit
cd multi-stage-multi-agent/backend
Build the Java project:

bash
Copy
Edit
mvn clean compile
Run the Java application:

bash
Copy
Edit
mvn exec:java
