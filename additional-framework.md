# Architectural Decisions Rationale

## Scenario 3: Food Delivery App

### Decision Title: Additional Frameworks 

**Context:**
Build a mobile application that offers users an easy experience to be able to order food for pick up or delivery, as well as allowing users to store an account for easy ordering in the future. This application will allow real-time updates, and a review system for orders. 

**Options Considered:**
Native app development for Android (Kotlin)
Backend framework like Node.js
      -     Both Kotlin & Node.js

**Decision**
Develop the mobile application using Kotlin for Android and using Node.js for backend


**Rationale:**
Using Kotlin makes the most sense as it is supported by Google for Android development. Using Node.js for the backend framework is a great idea as it provides a non-blocking, event driven system which is optimized for real time applications and integration. Using Kotlin allows for the developers to create a precise database which is easier to write, and maintain. This allows the developers to ensure safety and consistent uptime while having the ability to integrate java is needed or wanted. Using Node.js will be crucial in connecting all the pieces together as it is great in integrating real time applications like ordering food, driver location and consistent real time updates. Using both of these allows us to integrate a rich experience for Android users, and provide a real-time backend solution which provides updates and supports the demand of a food ordering system. 

**Consequences**
Using Kotlin to its full potential for smooth Android deployment
Depend on Android SDK and Kotlin for updates
Relying on Node.js community for backend updates and patches

**Follow up actions**
Set up a continuous integration and deployment pipeline specifically suited for Android app development
Regularly monitor and update dependencies to ensure security, compatibility, and alignment with our application and Androids practices
