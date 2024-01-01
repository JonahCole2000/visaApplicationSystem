# Chosen Architectural Style

* Status: proposed
* Date: 2024-01-01

## Context and Problem Statement

My original design for the system involved one front-end application for all users (visa applicants, visa support officers and administrators). Though a monolithic architecture can make the development and deployment of an application simpler. According to Atlassian "Monoliths can be convenient early on in a project's life for ease of code management, cognitive overhead, and deployment. This allows everything in the monolith to be released at once¹." After consideration, I have decided to split up the responsibilities of my system based on user roles in order to separate concerns, allow for a tailored application dependent on the user's role, allow for easier maintenance and updates and flexible scalability. I need to select an architectural style which fits my modular system design.

## Considered Options

* Service-Oriented Architecture (SOA)
* Microservices Architecture
* Monolithic Architecture
* Event-Driven Architecture

## Decision Outcome

Chosen option: "Service-Oriented Architecture", because SOA aligns with the goal of separating concerns based on user role and allows for the creation of independent services which can be tailored to each user role. Also, SOA allows for isolated changes which makes maintaining the system easier and SOA provides flexible scalability.
