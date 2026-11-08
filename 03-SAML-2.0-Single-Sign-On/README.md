# SAML 2.0 Single Sign-On (SSO) Lab

## Project Overview

This hands-on lab demonstrates Single Sign-On (SSO) authentication using the SAML 2.0 protocol.

The lab focuses on configuring an Identity Provider (IdP) and a Service Provider (SP) to enable secure authentication using SAML assertions.

## Technologies Used

- SAML 2.0
- Auth0
- Identity Provider (IdP)
- Service Provider (SP)
- XML
- Single Sign-On (SSO)

## Authentication Flow

1. User accesses the Service Provider application.
2. Service Provider generates a SAML authentication request.
3. User is redirected to the Identity Provider.
4. Identity Provider authenticates the user.
5. IdP generates a signed SAML response.
6. Service Provider validates the SAML assertion.
7. User receives authenticated access to the application.

## Key Learning Outcomes

- Understanding SAML 2.0 architecture
- Identity Provider and Service Provider configuration
- SAML authentication requests and responses
- XML-based SAML assertions
- Single Sign-On implementation
- SAML-based federated authentication

## Lab Screenshots

### 1. Identity Provider Configuration

![Identity Provider Configuration](screenshots/01-idp-configuration.png)

### 2. Service Provider Configuration

![Service Provider Configuration](screenshots/02-sp-configuration.png)

### 3. SAML Authentication Request

![SAML Authentication Request](screenshots/03-saml-request.png)

### 4. SAML Response

![SAML Response](screenshots/04-saml-response.png)

### 5. Successful SSO Authentication

![Successful SSO](screenshots/05-sso-success.png)

## Conclusion

Successfully explored SAML 2.0 Single Sign-On, IdP and SP configuration, SAML assertions, and federated authentication.
