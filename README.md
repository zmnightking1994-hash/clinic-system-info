# clinic-system-info  "Source code available for review upon request".

## 🏗️ System Architecture

This project is built using a modern decoupled architecture:

1. **Frontend (Next.js):** 
   - Built with React, TypeScript, and Tailwind CSS.
   - Handles patient dashboard views, real-time input validation, and responsive UI.
   - Communicates with the backend using secure, asynchronous API fetches.

2. **Backend (FastAPI):**
   - High-performance Python ASGI framework.
   - Handles clinical logic, user authentication, and endpoints for EHR management.
   - Automatic API documentation available via Swagger UI (`/docs`).

3. **Database (PostgreSQL):**
   - Robust relational database for managing patients, encounters, and prescriptions.
   - Structured schemas ensuring strict data integrity and compliance with medical data standards.
