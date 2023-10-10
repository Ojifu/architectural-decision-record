# Architectural Decisions Rationale

## Scenario 3: Food Delivery App
 ### Decision Title : UI Framework

**Context**
Choosing a UI framework to build the front-end of the app.

**Options considered**
- Android Jetpack
- Material Design
- Tailwind CSS

**Decision**
The front-end will be created with Tailwind CSS.

**Rationale**
- Familiarity with tailwind CSS is much higher than the other frameworks meaning that less time will be spent learning new frameworks.
- Tailwind CSS follows a mobile-first approach, which means the framework is designed to prioritize the mobile experience by default.
- Tailwind CSS has gained significant popularity and has an active community of developers which means we can benefit from community-driven resources, tutorials, and plugins.
- Android Jetpack and Material Design, while suitable for the job, will require additional time to learn, which is why we will not be using either for this project.

**Consequences**
- Tailwind CSS can limit your design freedom to an extent due to its reliance on predefined classes which may not cover all required design scenarios.
- Using Tailwind CSS introduces a dependency on the framework itself. If the framework undergoes significant changes or becomes unsupported in the future, it may require adjustments to your app's code.

**Follow-up actions**

- Setup Tailwind CSS into your project.
- Establish design guidelines and best practices for using Tailwind CSS within the development team.
- Start building your UI components using Tailwind CSS.
- Test and iterate the code as we develop it to ensure it works as expected.
- Optimize Tailwind CSS for production.
