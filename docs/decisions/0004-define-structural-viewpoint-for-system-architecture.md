# Define Structural Viewpoint for System Architecture

* Status: proposed
* Date: 12-11-2023

## Context and Problem Statement

According to the Open Group's ArchiMate documentation, "An architecture viewpoint frames one or more concerns. A concern can be framed by more than one viewpoint².", therefore, a dedicated viewpoint is defined to represent the structure, including the components and relationships of the system. A diagram type selection is required for the representation of the system's structure. A list of types of structural diagrams is avaiable from Science Direct, "Structure diagrams: Includes package, class, objects, composite structure, component, profile, and deployment diagrams. They are used to define what must be implemented in the system in terms of components. They are useful to specify the part of the system architecture that is time independent.".

## Considered Options

* Class Diagrams
* Deployment Diagrams
* Package Diagrams
* Object Diagrams

## Decision Outcome

Chosen option: "Class Diagrams", because Class diagrams provide a comprehensive representation of the structure and relationships within the system. Class diagrams are widely used and understood, making class diagrams an effective way to capture the static aspects of system architecture and an easily adoptable approach throughout the development team.
