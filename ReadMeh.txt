Full Stack Development Lab Report

1. Full Stack Development

Full Stack Development refers to the development of both the frontend and backend parts of a web application.

- The frontend handles the user interface that runs in the browser.
- The backend handles server-side logic and processes requests.
- Both parts communicate through APIs to form a complete web application.

This project demonstrates Full Stack Development because it includes both a frontend application and a backend server that communicate with each other.

2. Frontend and Backend Responsibilities

Frontend Responsibilities
The frontend is responsible for:
- Displaying the user interface in the browser
- Handling user interactions (button clicks, input, etc.)
- Sending requests to the backend API
- Displaying data received from the backend

Backend Responsibilities
The backend is responsible for:
- Running a server using Node.js and Express
- Creating API endpoints (e.g., /api/message)
- Processing incoming requests from the frontend
- Sending responses back in JSON format

3. Web Application Architecture

This project follows a client-server architecture.

Architecture Flow:
1. The user opens the frontend in the browser (Client)
2. The frontend sends an HTTP request to the backend
3. The backend server receives the request
4. The backend processes the request and prepares a response
5. The backend sends JSON data back to the frontend
6. The frontend displays the response to the user

Flow Diagram:
Client (Browser)
→ Frontend (HTML/JS)
→ Backend (Node.js + Express)
→ Response (JSON Data)
→ Frontend Display

4. Project Structure

fullstack-intro/
├── frontend/
├── backend/

This structure separates the user interface from the server logic, following full stack development principles.
