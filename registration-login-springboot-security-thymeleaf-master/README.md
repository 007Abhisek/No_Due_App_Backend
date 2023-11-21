registration-login-module using springboot, spring mvc, spring security and thymeleaf

Overview
Welcome to the No Due App backend repository! This project is designed to help users keep track of assignments, deadlines,
and other tasks without the stress of due dates. The backend is responsible for handling data storage, user authentication, 
and managing task-related functionalities.

The No Due App is a project designed to simplify and streamline the process of= managing and tracking assignments, deadlines, 
and tasks for students. This application provides a user-friendly interface for creating, organizing, and monitoring academic 
tasks, ensuring that students can stay on top of their responsibilities and never miss a deadline.


Features
Task Creation: Easily add new tasks, assignments, or deadlines with relevant details such as due date, priority, and course information.
Task Organization: Categorize tasks by courses or subjects, allowing for a structured and organized view of upcoming assignments.
Reminders: Receive timely reminders for approaching deadlines to help users stay proactive and avoid last-minute stress.
Task Completion Tracking: Mark tasks as completed, providing a sense of accomplishment and a clear overview of outstanding responsibilities.

Getting Started
Prerequisites
Before you begin, ensure you have met the following requirements:

Node.js installed

Installation
Clone the repository:
git clone https://github.com/your-username/no-due-app-backend.git
https://github.com/007Abhisek/No_Due_App_Backend

Install dependencies:
cd no-due-app-backend
npm install

Create a .env file in the root directory and configure the following variables:
PORT=3000
MONGODB_URI=mongodb://localhost:27017/no-due-app
SECRET_KEY=your_secret_key

Replace your_secret_key with a secure key for JWT token generation.

Start the server:
http://localhost:8080/