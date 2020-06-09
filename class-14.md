# read 14

## Access Controls
* Access Controls are the selective restriction of resources. 
* Access Controls are implemented everywhere in computer systems. UNIX files have read, write, and execute permissions assigned to owners, groups, and everyone else. Websites have limited access to pages based on the credentials of a user. APIs restrict access to internal and external developers differently.
* In our RESTful APIs, it is *important to limit access* to clients based on credentials.Limiting what actions a user can preform on a given resource is called *Access Control*.
* A user can be given a token at signup and login, and that user can pass that token back to the server on requests with limited access controls. Once the server parses the token, it can determine if the user is authorized to preform the request.
* not all applications have the same degree of access, based on user the user type and UI requirement, a CMS might, give th admin all access, editor read write and delete access, guest read access, and user read write but not update.

1. Back End (API Layer)
* Manage the login cycle with the front-end application
* Maintain the User’s database
* Maintain roles for each user
* Authenticate users (basic and bearer)
* Create, manage, and apply Role Based Access Controls
* Maintain and reference their capabilities, based on their role
* Restrict access to features (like routes) based on capabilities Express Middleware could be used to restrict access to routes Mongoose Middleware/Hooks could be use to restrict access to business logic

2. Front End (Client Layer)
* Initiate the login process
* Store login tokens as cookies
* Manage login state, capabilities
* Control physical & visual access (hide/show/alter) to components based on RBAC rules
* Alter behaviors based on RBAC rules


## Access control types
### Access control systems come in three variations:
* Discretionary Access Control (DAC)
* Mandatory Access Control (MAC)
* Role Based Access Control (RBAC)