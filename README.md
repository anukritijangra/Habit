# HABIT (Task Management Application)

A full-featured Task Management Application built with the **MERN stack**. The frontend is developed using **React with Vite**, while the backend is powered by **Express.js** with **MongoDB** as the database.

## Features

- **User Authentication**  
  - Register and login with secure JWT authentication  
  - Secure password handling with **bcrypt.js**  
  - Only authenticated users can access and manage tasks

- **Task Management**  
  - Create, update, and delete tasks with priorities, due dates, and categories  
  - Share tasks via public links (read-only access)  
  - Change task statuses: Backlog, To-Do, In-Progress, Done  
  - Automatic highlighting:  
    - Red: Overdue tasks  
    - Green: Completed tasks  

- **User Management**  
  - Update name, email, and password in settings  
  - Re-authentication required after sensitive changes

- **Analytics & Filtering**  
  - View analytics in a dedicated dashboard  
  - Filter tasks by Today, This Week, or This Month

- **User Interface & Feedback**  
  - Responsive design  
  - Task tooltips for full titles  
  - Toast notifications for actions  
  - Mandatory fields marked clearly

- **Collaboration**  
  - Add members to boards  
  - Assign members to tasks

- **Bonus Features**  
  - Pre-filled settings info for easier edits  
  - Visual task status indicators based on due date

## Tech Stack

### Frontend
- React  
- Vite  
- Redux Toolkit  
- React Router DOM  
- React Icons  
- React Toastify  
- ESLint  

### Backend
- Express.js  
- Mongoose  
- JWT (JSON Web Tokens)  
- bcrypt.js  
- dotenv  
- cors
