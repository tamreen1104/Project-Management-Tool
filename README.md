# Project-Management-Tool
*COMPANY - CODEALPHA
*NAME - TAMREEN KHANAM
*STUDENT ID - CA/JU1/26706
*DOMAIN - FULL STACK DEVELOPMENT
*DURATION - 1st JULY 2025-30th JULY 2025
# Description
The "Collaborative Project Management Tool" is a web application designed to facilitate team-based project organization and task management, drawing inspiration from platforms like Trello or Asana. Built with a modern frontend stack and leveraging Firebase Firestore for its backend capabilities, this tool offers a real-time collaborative environment for users to manage their work.

Core Functionality:

User Authentication and Profiles:
The application begins with a user authentication system. Users can "register" by providing a username, which then creates or retrieves their unique profile within the system. Firebase Authentication handles the underlying user sessions, initially signing users in anonymously and then associating them with their chosen usernames. This ensures that each user has a distinct identity within the collaborative space.

Project Management:

Projects Dashboard: Upon successful login, users are directed to a personalized dashboard that displays all projects they are associated with, either as an owner or a member. This provides a centralized view of their current commitments.

Project Creation: Users have the capability to initiate new group projects. When creating a project, they provide a name and a brief description. The user who creates the project is automatically designated as its owner and becomes an initial member, laying the groundwork for team collaboration.

Project Details View: Clicking on any project from the dashboard navigates the user to a dedicated detail page for that project. This view presents the project's title, description, the username of its owner, and a list of all current project members, offering a comprehensive overview before diving into tasks.

Task Management within Projects:

Task Creation: Within any active project, users can create new tasks. Each task requires a title, a detailed description, and a crucial assignment to one of the project's existing members. This ensures clear responsibility for each piece of work.

Kanban-style Task Boards: Tasks are visually organized into three distinct columns: "To Do," "In Progress," and "Done." This Kanban-inspired layout provides an intuitive way to track the progress of tasks through different stages of completion.

Status Updates: By clicking on a task, users can open a detailed modal. This modal not only displays the task's full information but also allows authorized users to easily change the task's status (e.g., moving it from "To Do" to "In Progress" or "Done") via a dropdown selector.

Communication within Tasks (Comments):
Each task is equipped with its own dedicated comment section. This feature enables real-time communication and collaboration directly related to specific tasks. Users can add comments, ask questions, or provide updates, and all comments are displayed chronologically, ensuring a clear history of discussions.

Technology Stack:

The application is built using standard web technologies:

Frontend: HTML provides the structural foundation, CSS (specifically Tailwind CSS for utility-first styling) ensures a responsive and aesthetically pleasing user interface, and JavaScript handles all dynamic interactions, data manipulation, and communication with the backend.

Backend & Database: Firebase Firestore serves as the primary backend and database solution. Its NoSQL, cloud-hosted nature simplifies data storage for users, projects, tasks, and comments. Crucially, Firestore's real-time data synchronization capabilities inherently provide the "real-time updates" bonus feature, eliminating the need for separate WebSockets implementation.

This project offers hands-on experience in building a complete, collaborative web application. 

Implementing user authentication and managing user-specific data.

Designing and interacting with a database for complex, interconnected entities (projects, tasks, comments, users).

Creating dynamic and responsive user interfaces.

Understanding and leveraging real-time data synchronization for collaborative features.

Structuring a full-stack application from frontend to backend logic.







