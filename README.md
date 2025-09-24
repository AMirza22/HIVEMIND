# HiveMind  

HiveMind is a **full-stack web application** built with **Node.js, Express, MongoDB, and EJS**. It enables structured communication and workflow management between two roles: **Observers** and **Support staff**.  

---

## Features  

- **User Authentication & Roles**  
  - Secure registration and login using **Passport.js**, **bcrypt**, and **express-session**.  
  - Role-based access control (Observer vs. Support).  

- **Observers**  
  - Submit and track **observations**.  
  - Create and manage **support tickets**.  
  - Access a personal dashboard with account details.  

- **Support Staff**  
  - View and manage submitted observations.  
  - Update observation/ticket statuses.  
  - Respond to support tickets.  

- **Messaging**  
  - Built-in system for communication between Observers and Support.  
  - Messages stored in the database for transparency.  

- **Validation & Security**  
  - Password hashing with bcrypt.  
  - Middleware for route protection and role enforcement.  

---

## Architecture  

- **MVC Pattern**  
  - **Models:** User, Observation, Ticket, Message.  
  - **Routes:** Authentication, account management, observations, support, messaging.  
  - **Middleware:** Authentication and role checks.  
  - **Views:** EJS templates with reusable partials for layout.  

- **Testing**  
  - **Jest** used for component and route testing.  

- **Configuration**  
  - Managed with **dotenv** for environment variables.  
  - **Axios** included for handling external API requests.  

---

## Design  

- **Frontend:** EJS templates with responsive design.  
- **Styling:** Pastel theme with **green backgrounds** and **purple form panels** (based on wireframes).  
- **Layout:** Consistent use of partials for headers, footers, and navigation.  

---

## Project Goals  

HiveMind was developed as part of the **SWE5303: Applied Software Engineering module** to showcase:  
- Full-stack web development with a modern Node.js stack.  
- Secure authentication and role-based access control.  
- Clear separation of concerns using MVC architecture.  
- Practical application of **software engineering principles** including validation, modularity, and testing.  
