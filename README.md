# airbnb-clone-project
The backend for the Airbnb Clone project is designed to provide a robust and scalable foundation for managing user interactions, property listings, bookings, and payments. This backend will support various functionalities required to mimic the core features of Airbnb, ensuring a smooth experience for users and hosts.

## Project goals
User Management: Implement a secure system for user registration, authentication, and profile management.
Property Management: Develop features for property listing creation, updates, and retrieval.
Booking System: Create a booking mechanism for users to reserve properties and manage booking details.
Payment Processing: Integrate a payment system to handle transactions and record payment details.
Review System: Allow users to leave reviews and ratings for properties.
Data Optimization: Ensure efficient data retrieval and storage through database optimizations.

## Tech Stack
Django
Django REST Framework
PostgreSQL
GraphQL
Celery
Redis
Docker
CI/CD Pipelines

## Team Roles
•	Backend Developer: Responsible for implementing API endpoints, database schemas, and business logic.
•	Database Administrator: Manages database design, indexing, and optimizations.
•	DevOps Engineer: Handles deployment, monitoring, and scaling of the backend services.
•	QA Engineer: Ensures the backend functionalities are thoroughly tested and meet quality standards.
• UI/UX Designers: Focus on the user interface (UI) and user experience (UX) of a product, designing layouts, interactions, and flows that are intuitive, accessible, and visually appealing.
• Software Architects: Design the high-level structure of software systems, making critical decisions about architecture, technologies, and patterns to ensure scalability, maintainability, and performance.
• Business Analysts (BAs): Bridge the gap between business needs and technical solutions by gathering requirements, analyzing processes, and helping define project scope and objectives.
• Product Managers (PMs): Oversee the product’s strategy, vision, and roadmap. They align product development with business goals and customer needs, working closely with multiple stakeholders.

## Tehnology Stack
•	Django: A high-level Python web framework used for building the RESTful API.
•	Django REST Framework: Provides tools for creating and managing RESTful APIs.
•	PostgreSQL: A powerful relational database used for data storage.
•	GraphQL: Allows for flexible and efficient querying of data.
•	Celery: For handling asynchronous tasks such as sending notifications or processing payments.
•	Redis: Used for caching and session management.
•	Docker: Containerization tool for consistent development and deployment environments.
•	CI/CD Pipelines: Automated pipelines for testing and deploying code changes.

## Database Design
Users, Properties, Bookings, Reviews, and Payments.
A user can have multiple properties, a booking belongs to a property. 
A user can write multiple reviews, a review belongs to one property.
A user can make multiple payments. A payment is linked to one booking.
A booking has one payment.
A property have multiple reviews.
A booking is for one user.
