HiveMind

HiveMind is a full-stack web application built with Node.js, Express, MongoDB, and EJS for managing observations, tickets, and communication between two user roles: Observers and Support staff. The system was developed as part of the SWE5303: Applied Software Engineering module and demonstrates full-stack development, secure authentication, and API integration.

Features

Role-Based Access Control

Observers can register, log in, submit observations, and raise support tickets.

Support staff can manage submitted observations, respond to tickets, and message Observers.

Observation Tracking – Observers can submit and view their observations, while support staff can update statuses and manage workflow.

Ticketing System – Provides a structured way for Observers to request support, with Support staff able to view, respond, and close tickets.

Messaging – Direct communication between Observers and Support accounts, with messages stored in the database for clear history.

Authentication & Security – Implemented with Passport.js and bcrypt for secure login and password encryption. Sessions are handled via express-session.

API Integration – Includes What3Words API for precise observation location data, and Stripe integration for secure card handling with hashing.

MVC Architecture – Routes, controllers, models, and views are separated for maintainability. Middleware ensures authentication and role validation.

Responsive Design – EJS-based UI styled with a pastel theme (green backgrounds and purple form panels), following the provided wireframes for accessibility and clarity.

Tech Stack

Backend: Node.js, Express

Frontend: EJS templates with responsive CSS

Database: MongoDB with Mongoose

Authentication: Passport.js, bcrypt, express-session

APIs: What3Words, Stripe

Project Goals

HiveMind was created to apply software engineering principles to a real-world style web system. It demonstrates skills in full-stack development, secure user management, API integration, and modular architecture, while balancing usability, functionality, and security.
