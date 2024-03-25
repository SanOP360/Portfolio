This project is a full-stack portfolio website built using React and Express. It showcases my skills as a web developer and provides information about my projects, skills, and contact details.

Features:
Project Section: Displays a collection of projects I have worked on. Each project includes details such as title, image, description, and links to demo and code.
Add Project Form: Allows authorized users to add new projects to the portfolio. Users need to provide a title, image URL, video URL, code link, description, and owner's password.
About Section: Provides information about me, including my background, skills, and education.
Contact Section: Offers ways to get in touch with me via WhatsApp or LinkedIn.
Backend API
The backend API is built with Node.js and Express.js. It provides endpoints to create new projects and fetch existing projects from the database.

Endpoints
POST /api/projects: Adds a new project to the database. Requires authentication using an owner's password.
GET /api/projects: Retrieves all projects from the database.
Frontend
The frontend is developed using React.js. It provides a user-friendly interface for viewing projects and adding new projects to the portfolio.