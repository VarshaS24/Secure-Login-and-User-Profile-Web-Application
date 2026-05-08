# Secure-Login-and-User-Profile-Web-Application


OIDC App Integration:
Configured a new Single-Page Application (SPA) integration in the Okta Admin Console using the OpenID Connect (OIDC) protocol for token-based authentication.  

Grant Type & Security:
Implemented the Authorization Code grant type with Proof Key for Code Exchange (PKCE) to ensure secure token delivery for the client-side application.  

Redirect URI Configuration:
Managed the "secure handshake" by setting up a specific Sign-in redirect URI (http://127.0.0.1:5500) to ensure authentication responses are only sent to the trusted local development environment.  

Application Assignments:
Created and assigned specific user groups, such as Admin_group and User_group, to the application to manage access control from the Okta dashboard.  

Custom Identity Claims:
Defined custom claims (like roles and email) in the Okta Authorization Server using Regex and profile mapping to include metadata in the ID Token.  

JavaScript Implementation:
Developed the frontend logic using the Okta Auth SDK, initializing the OktaAuth client with the unique Client ID and Issuer URL to handle the signInWithRedirect and handleLoginRedirect flows.  

Dynamic UI Rendering:
Built a dynamic interface that toggles between a "Login" view and a "User Info" view, successfully rendering claims like Name, Email, and Roles extracted from the decoded ID Token. 

DEMO VIDEO:



https://github.com/user-attachments/assets/9e58f8e3-ecd8-467e-80a6-6969dcd46189

