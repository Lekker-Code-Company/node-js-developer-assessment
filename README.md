# Node.js Backend Developer Assessment - Game Monitoring API

Your task is to build a simple RESTful API server in Node.js that allows authenticated users to monitor players and team details in a game. Follow the instructions below to complete the assessment

## Overview

- Implement a signup and signin functionality using JSON Web Tokens (JWT) to ensure secure user access to the application.
- Upon signup, users should be assigned a random score.
- Implement an authentication validation middleware to protect certain routes from unauthorized access.
- Create CRUD operations for teams.
  - Users can create a team with the following details:
    - Team name (required)
    - Maximum member number (should be greater than 10)
    - The user creating the team will become its owner.
  - Team owners can update team information and have the ability to reject team member requests.
  - Team owners can also delete the entire team.
  - Authenticated users can fetch team information, including the following details for each team member:
    - Rank (total rank by score in the game)
    - Name
    - Score
- Ensure appropriate error handling and validation throughout the backend.

## Acceptance Criteria

- Develop a Node.js backend using Express.js to handle HTTP requests and responses.
- APIs should be consuming and producing `application/json`.
- Utilize JSON Web Tokens (JWT) for user authentication during signup and signin processes.
- Generate a random score for users upon signup.
- Create middleware to validate user authentication and protect certain routes.
- Implement CRUD operations for teams, including creating, updating, and deleting teams.
- Allow users to join existing teams.
- Design an API endpoint to retrieve team information along with details for each team member (rank, score, name).
- Ensure appropriate error handling and validation throughout the backend.

## Assessment Evaluation

- Code Quality
- Functionality
- Security
- Error Handling
- Query Performance
- Unit tests.

## Bonus

- API documentation.
- Docker and Docker Compose.

## Submission Guidelines

- Share the GitHub repository link containing your complete Node.js backend code.
- Include clear instructions on how to set up and run the application locally.

_Try your best to implement as much as you can from the given requirements_
