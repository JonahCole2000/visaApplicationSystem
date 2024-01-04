# Inclusion of Security Considerations in System Architecture

* Date: 20-12-2023

## Context and Problem Statement

The system architecture must incorporate security measures to ensure privacy, security, authentication and confidentiality for all users of the system. The authentication and authorization mechanisms must be designed to restrict or allow access dependent on the user's role and tasks.

## Considered Options

* Comprehensive security measures including authorization controls and password encryption with salt and hashing.
* Basic authentication without encryption.
* Encryption without salt or hashing.

## Decision Outcome

Chosen option: "Comprehensive security measures including authorization controls and password encryption with salt and hashing.", because this approach addresses authentication, authorization, non-repudiation and password security.
