# Personal Notes Manager

A full-stack MERN application for managing personal notes, built with a focus on CRUD functionality, filtering, and a polished user experience. This project demonstrates practical skills in frontend and backend development, database management, and responsive design.

## Project Overview

The Personal Notes Manager application allows users to:
- **Create, Read, Update, and Delete** notes
- **Filter** notes by category or search by title
- **Mark notes as completed** (optional feature)

### Key Features
- **Backend:** Node.js with Express.js for RESTful APIs, SQLite database for persistent data storage.
- **Frontend:** React for dynamic, responsive UI with animations and professional design.
- **Validation:** Ensures each note has a title and description, with predefined categories.
- **Sorting and Filtering:** Notes are sorted by creation date, with options to filter by title or category.

## Project Structure

- **Backend:** APIs for CRUD operations, using SQLite to store notes with validation, sorting, and filtering capabilities.
- **Frontend:** Interactive components including Note List, Note Form, and Search Bar for efficient note management.

## Technologies Used

- **Frontend:** React, Axios, CSS3, responsive design with animations
- **Backend:** Node.js, Express.js, SQLite
- **Deployment:** Render (backend) and Netlify (frontend)

## Setup Instructions

1. **Backend Setup**
   - Navigate to the `backend` directory and install dependencies:
     ```bash
     cd backend_notes_manager
     npm install
     ```
   - Start the backend server:
     ```bash
     node server.js
     ```

2. **Frontend Setup**
   - Navigate to the `frontend_notes_manager` directory and install dependencies:
     ```bash
     cd frontend_notes_manager
     npm install
     ```
   - Start the frontend server:
     ```bash
     npm start
     ```

## API Endpoints

- `GET /notes`: Retrieve all notes (optional filters for category and title)
- `POST /notes`: Create a new note
- `PUT /notes/:id`: Update a specific note by ID
- `DELETE /notes/:id`: Delete a specific note by ID

## Queries & Improvements

The project was a valuable hands-on experience, reinforcing fundamental skills and expanding practical knowledge of CRUD operations, validations, and UI design. One potential area for further exploration would be best practices for optimizing similar real-world applications.

---

### Thank You!
