### Decision Title: Data Storage

**Context:**
Store datasets from user profiles and order histories to allow users to view previous orders, and reviews

**Options Considered:**
Relational databases (MySQL)
NoSQL database (MongoDB)
Hybrid database (MySQL & MongoDB)

**Decision**
Adopt a hybrid approach while using a relational database for user end feedback, while using NoSQL database for reviews and ratings. 

**Rationale:**
Use both databases to have a structured relational database, but have the flexibility of NoSQL database as well. Using a relational database for user accounts will make the most sense as it is a secure measure of having a consistent user account without constantly changing information. The reason we will be using NoSQL database is because of the constantly changing user-wide feedback based on food quality and restaurants which allows our system to take in reviews with the masses.  

**Consequences** 
Difficult to manage two databases
Optimized performance may require diverse data requirements 

**Follow-Up Actions:**
Design a normalized schema for relational database
Plan a backup and recovery mechanism for both systems
