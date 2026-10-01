# Best Bike Paths (BBP)

![BBP Project](https://img.shields.io/badge/Project-Software_Engineering-blue)
![LaTeX](https://img.shields.io/badge/Documented_in-LaTeX-green)
![Alloy](https://img.shields.io/badge/Formal_Analysis-Alloy-red)

> **Best Bike Paths (BBP)** is a software platform designed to simplify the life of cyclists who want to enjoy their trips without worrying about finding the best routes. It serves as a community where cyclists can track their trips, log road conditions and hazards, and share paths so everyone can benefit from the collective experience.

This repository contains the software engineering documentation for the BBP project. The documentation covers everything from requirements elicitation and formal analysis to the complete architectural design of a microservice-based system.

## 📂 Repository Structure

The repository is organized into three main sections:

### 1. [RASD (Requirements Analysis and Specification Document)](./RASD)
The RASD defines the problem domain and the system's requirements. It outlines what the system must do without diving into how it will be implemented.
- **Goals and Domain Assumptions:** Detailed analysis of user needs and world phenomena.
- **Use Cases:** Interaction scenarios between users (cyclists) and the system.
- **Formal Analysis:** An Alloy model that formally verifies the core functionalities of the system, such as trip recording, modification, and publication lifecycle.
- *Contains the LaTeX source code and PlantUML diagrams for the RASD.*

### 2. [DD (Design Document)](./DD)
The DD translates the requirements specified in the RASD into a concrete technical architecture.
- **Architectural Design:** A modular, microservice-based architecture designed for scalability and maintainability.
- **Component Interfaces:** Detailed definitions of how system components interact.
- **User Interface (UI) Design:** Mockups and UX flows for the smartphone application.
- *Contains the LaTeX source code and PlantUML diagrams for the DD.*

### 3. [DeliveryFolder](./DeliveryFolder)
Contains the final compiled PDF versions of both documents ready for review:
- `RASDv1.pdf`
- `DDv1.pdf`

## 🛠️ Technologies & Tools Used
- **LaTeX:** For typesetting and structuring the documentation.
- **PlantUML:** For generating UML diagrams (Use Case, Sequence, Class, Component, and Deployment diagrams).
- **Alloy Analyzer:** For formal verification and consistency checking of the system's critical domain models.

## 👥 Authors
- **Angelo Cantoli**
- **Simone Edmondo Bedini**

---
*Copyright © 2025 - Angelo Cantoli, Simone Edmondo Bedini - All rights reserved.*