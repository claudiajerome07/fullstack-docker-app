# Fullstack Docker App

This project is a simple **React + Express + PostgreSQL** full-stack application, containerized using **Docker Compose**. The frontend and backend are separated into services, and PostgreSQL is used as the database with volume persistence.

---

## Project Structure

fullstack-docker-app/
├── backend/
│ ├── app.js # Express server
│ └── package.json # Node.js dependencies
├── frontend/
│ ├── package.json # React app dependencies
│ └── src/
│ └── App.js # React component
├── db-data/ # Persistent database volume
├── docker-compose.yml # Compose file to run all services
├── .env # Environment variables (currently empty)
└── README.md # Project documentation
