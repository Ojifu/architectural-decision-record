# Architectural Decisions Rationale

## Scenario 3: Food Delivery App

### Decision Title : Determining whether to create a native, web or hybrid app.

 

**Context**

Determining the type of app we will develop and the platform(s) that it will be designed and optimized for.

 

**Options considered**

Native, web and hybrid apps are being considered.

- Native app for android only development

- Web app for most mobile devices

- Hybrid app for android and iOS

 

**Decision**
With the requirements from scenario 3 in mind, we have chosen to **develop the app for android as a native app.** 
 

**Rationale**
- Because the app needs to use location services, display notifications and utilize payment methods, a native app will allow full access to these features.
- Android was chosen because it has a larger user base which will make the app accessible to more people.
- We did not choose to develop a web or hybrid app because we won’t have access to the android features required to fulfill all of the apps specifications.

 

**Consequences**
- Less market reach than creating a hybrid app for both android and iOS.
- If the decision is made to create an iOS version of the app, it would have to be made all over again from scratch due to the different OS' utilizing different programming languages.
- The app must be approved by the App Store which means that there will be extra guidelines that must be followed in order for it to be published.
- Greater amounts of maintenance will be required in order to keep the app up to date with operating system updates and changes to the android operating system.
 

**Follow-up actions**
- Begin the development process by selecting the appropriate development tools (such as Android Studio), and establishing coding standards and guidelines.
- Create UI/UX guidelines specific to android to ensure consistency throughout the app.
- Prioritize and implement the core features of the app, such as GPS tracking, various payment gateways, integrate with the restaurants' inventory management systems, etc...
- Conduct testing of the app to ensure it functions as expected, including compatibility testing across various Android devices and OS versions.
- Implement security measures to protect user data and transactions.
- Prepare your app for submission to the Play Store. Ensure that the app complies with the Play Store's guidelines, including content policies, privacy policies, and any specific requirements related to food delivery apps.
- Allocate resources for ongoing maintenance, bug fixing, and updates. Stay up to date with the latest android OS releases to ensure compatibility.
