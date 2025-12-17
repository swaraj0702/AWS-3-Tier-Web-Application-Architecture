This repository is forked from the “10 Weeks of CloudOps” initiative by Piyush Sachdeva.
The project was practiced and explored as part of hands-on CloudOps learning, focusing on understanding AWS three-tier application architecture, scalability, and security best practices.

🧩 Overview

This project demonstrates the design and understanding of a Three-Tier Web Application Architecture deployed on Amazon Web Services (AWS).
The architecture separates the application into three independent layers to improve scalability, maintainability, and security.

Architecture Design
🔹 1. Presentation Layer

Handles user interaction and UI

Typically hosted on:

Amazon EC2

Amazon S3 (for static content)

Responsible for receiving HTTP/HTTPS requests

🔹 2. Application Layer

Contains business logic and backend processing

Hosted on:

Amazon EC2

Communicates securely with presentation and database layers

🔹 3. Database Layer

Stores application data

Implemented using:

Amazon RDS

Isolated from public access for enhanced security
