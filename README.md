# GameQuestListingWebApp

## Description

**Game Quest Database Full-Stack Web Application.**
Game Quest is a comprehensive web application that allows users to explore, add, and review various games. Anyone can view the game lists and their reviews, but logging in is required to contribute new games or reviews. 'Users' can add games and write reviews, while 'managers' have the additional authority to edit or delete reviews. 



## Features

Full-Stack Application with a user-friendly interface created using Thymeleaf and styled with Twitter Bootstrap.
Secure authentication and authorization with Spring Security.
Users authenticate using a username and password.
Different roles (non-members, users, and managers) have varying permissions.
Role-based access control:
Non-members can view game lists and reviews.
Users can add new games and write reviews.
Managers can edit and delete reviews in addition to the capabilities of users.
Deployment on AWS EC2 for scalable and reliable hosting.
Comprehensive unit testing with JUnit to ensure code quality.
Adherence to Spring MVC best practices for a clean separation of concerns in the application architecture.
Efficient database interactions using JDBC and in-memory H2 Database Engine.
CRUD operations for managing game data and reviews.
Customizable schema and initial data setup using Schema.sql.
Reusable Thymeleaf Fragments to maintain consistent and maintainable HTML elements (head, footer, navigation).

