### Decision Title: User Permissions

**Context:**
Ensure only authorized users access features like ordering food, viewing order history, leaving reviews, and managing payment information. Ensure users must be signed in to access features. 

**Options Considered** 
Role-Based Access Control (RBAC)
Token-Based authentication 
Both Role-Based Access Control & Token-Based authentication

**Decision** 
User Role-Based access control (RBAC) combined with token based authentication for login services.

**Rationale**
Role based access control simplifies the assignments and management of permissions based on role. It allows a user to have different permissions than a guest, admin, or technical support. Using token based authentication for verifying accounts will ensure that the users access control will be reflective based on the account type. It makes most sense to have these both separate as users will have different dashboards based on their position as technical support will have a different interface compared to a user. Allowing role based access control will allow users the authorization to access different interfaces, while having token based authentication will allow users to keep their accounts secure.

**Consequences:**
Simplified management of user permissions
Dependency on token generation and validation mechanisms with an exterior sources

**Follow-up Actions**
Develop a permission map out to user roles and respected access levels. ie admin, technical support, user and guest roles
Implement token refreshing system to ensure security for user accounts
