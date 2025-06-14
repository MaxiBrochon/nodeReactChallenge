# nodeReactChallenge
📁 Project Structure This repository contains the following three main folders:

backend:
A Node.js project built with Express, using TypeORM and routing-controllers libraries. The development follows key architectural patterns and best practices, including: -Controller-Service-Repository pattern -Data Transfer Object (DTO) pattern -Centralized error handling with routing-controllers -Dependency injection (DI)

frontend:
A React project written in TypeScript, utilizing Material UI for the UI components, along with Redux for state management and Axios for API communication. Basic JWT-based authentication is implemented.

database: Includes the Entity-Relationship (ER) diagram and a SQL script for creating the database schema.
⚙️ Installation Steps 
1-Clone the repository. 
2-Ensure Docker is running on your machine. 
3-From the root directory, run: "npm run dev" This command will: Spin up three Docker containers: -MySQL service -Node.js Express backend -React frontend

Automatically initialize the database schema, including tables, relationships, and seed data for departments.

🧪 API Testing You can test the available API endpoints using the shared Postman collection:
https://lacbro.postman.co/workspace/My-Workspace~c007e1f9-a8fb-4a87-8b47-499e1e5c1bf4/collection/2255275-9a8ad195-f819-45e8-9355-0ed255252960?action=share&creator=2255275


🧪 Unit testing for the backend has been added using Supertest, along with Code Coverage. To run the full test suite, use the console command: "npm run test" inside the Backend folder. To check the code coverage, run: "npm run coverage"
