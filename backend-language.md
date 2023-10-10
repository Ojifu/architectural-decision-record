# Architectural Decisions Rationale

## Scenario 3: Food Delivery App

### Decision Title : Backend language

**Context**
- Determining which backend coding language to utilize in the development of the app based on scenario 3.

**Options Considered**
- Java
- Kotlin
- Node.js

**Decision**
The backend coding language we will use is Java which will be the best for efficient code and allowing the best user experience.

**Rationale**
- Java's performance is known for its speed and efficiency from its object-oriented programming concepts.
- Java is recognized for its emphasis on reliability and stability as it enforces comprehensive error handling, reducing the likelihood of runtime errors.
- Java has a massive developer community worldwide, which means there is extensive documentation, tutorials, and resources available.
- Java is in principle created with an emphasis on security which is important when creating an app that will store user information and facilitate payments.
- We did not choose Kotlin or Node.js because we are interested in the write once, run anywhere (WORA) principle that Java provides. Java applications can run on any platform that supports Java without the need for major modifications.


**Consequences**
- Java programs typically require more system resources in comparison to other coding languages which can affect app hosting costs.
- Java can sometimes require more code to do the same thing as other coding languages, which can be a cause of slower development.

**Follow-up actions**
- Set up the backend development environment for Java.
- Plan and design the architecture of your backend system.
- Implement the backend functionality of the app using Java.
- Integrate a suitable database for storing and retrieving data.
- Conduct thorough testing of the code to ensure functionality, reliability, performance, and security.
- Prepare the Java backend application for deployment.
