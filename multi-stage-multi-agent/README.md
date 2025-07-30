# Jenkins Zero To Hero — Multi-Stage Multi-Agent Pipeline Example

This repository demonstrates a simple Jenkins pipeline that builds and runs a Java application using Maven, along with optional Node.js steps.

## Project Structure

- **Java Backend**: Simple Maven-based Java application located in  
  `multi-stage-multi-agent/backend/src/main/java/com/example/App.java`

- **Jenkins Pipeline**: Declarative pipeline with stages for checkout, build, and run.

## Java Application

The Java app is a basic "Hello World" program with the main class `com.example.App`.

## Maven Commands Used

- To compile the Java app:  
  ```bash
  mvn clean compile
