# CustomerRelationshipManagement

This CRM represents my way of administrating clients and the projects they
request. It includes an authentication system into the platform, projects 
request possibilities, real time check of the status of the working project,
included mailing system for a quicker intercommunication between client and
business owner and others.

![Website MainView](CRM_documentation/picture_1.png)

## Backend

Every part of the webapp is administrated from a control panel as shown
below.

![Website MainView](CRM_documentation/picture_2.png)

##### AUTHENTICATION AND AUTHORIZATION

This database all the clients of the business with basic details needed
for the authentication system. It includes last_login, last_logout and others.

##### CLIENTSMANAGEMENT

The clients management database includes four different tables..

##### Clients details

This table includes different informations about any specific client who
has an account in the platform. Information like size of the client, type of the client,
number of finished, proposed or planned projects even the projects who are
in progress of development. It also includes a profile image, a short description,
email, phone number, social media presence and personal website. The structure can be seen
below.

![Website MainView](CRM_documentation/picture_3.png)

This information is used not only for the business but also to create 
a profile of the client in the UI through CRUD operations.

![Website MainView](CRM_documentation/picture_4.png)