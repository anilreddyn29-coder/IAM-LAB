# SAML 2.0 – Single Sign-On (SSO)

## Project Overview

This project demonstrates Single Sign-On (SSO) using Security Assertion Markup Language (SAML 2.0). It explores how a user authenticates through an Identity Provider (IdP) and accesses a Service Provider (SP) using SAML-based authentication.

## Purpose

The purpose of this lab is to understand the SAML 2.0 authentication flow, the communication between an Identity Provider and a Service Provider, and how user attributes are shared through SAML assertions.

## Technologies Used

- SAML 2.0
- Authgear SAML Testing Tool
- Identity Provider (IdP)
- Service Provider (SP)
- XML Assertions
- Single Sign-On (SSO)

## Key Concepts Covered

- SAML authentication flow
- Identity Provider (IdP) and Service Provider (SP)
- SAML authentication requests
- SAML responses and assertions
- User attributes and claims
- NameID and attribute mapping
- SAML response validation

## Authentication Flow

1. The user attempts to access a Service Provider.
2. The Service Provider initiates SAML authentication.
3. The user is redirected to the Identity Provider.
4. The user authenticates with the Identity Provider.
5. The Identity Provider generates a SAML response.
6. The Service Provider processes the response and grants access after validation.

## Lab Screenshots

### 1. SAML User Attributes

The Authgear SAML testing tool displays user attributes returned during the authentication process.

![SAML User Attributes](./Screenshot%202026-08-08%20191007%281%29.png)

### 2. SAML Authentication Success

This screenshot demonstrates JWT token validation and decoded claims.

![JWT Validation](./Screenshot%202026-08-09%20124947%281%29.png)

### 3. SAML Response Validation

This screenshot demonstrates a successful OAuth authorization flow.

![OAuth Authorization Success](./Screenshot%202026-08-09%20172309%281%29.png)

## Learning Outcomes

- Understood the fundamentals of SAML 2.0.
- Learned the roles of Identity Providers and Service Providers.
- Explored SAML authentication and user attribute sharing.
- Understood how SAML assertions support Single Sign-On.

## Project Author

Anil Kumar Reddy
