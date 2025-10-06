❤️ Dating App

Full-Stack | ASP.NET Core Web API + Angular + SQL Server + Cloudinary

🔍 Overview

The Dating App is a modern web application that allows users to create profiles, upload photos, match with others, and chat in real time.
It’s built using ASP.NET Core Web API and Angular, following clean architecture principles for scalability and performance.

✨ Key Features

👤 User Profiles – Register, edit profiles, and upload profile pictures.

❤️ Likes & Matches – Like profiles and view mutual matches.

💬 Real-Time Chat – Implemented with SignalR for instant messaging.

🔐 Authentication & Authorization – JWT-based authentication and role-based permissions.

📷 Image Management – Integrated with Cloudinary API for photo upload, validation, and transformation.

🔍 Filtering & Pagination – Browse users using filters such as gender, age, and location.

📊 Activity Tracking – See who viewed your profile or liked you.

🧠 AI & Automation Workflows

Used ChatGPT and Cursor during API design to generate boilerplate CRUD operations and DTO mappings.

Tested and debugged API endpoints using Replit before pushing to production.

Automated media upload, resizing, and storage through Cloudinary API, removing the need for manual moderation.

🛠️ Tech Stack

Backend: ASP.NET Core Web API, Entity Framework Core, AutoMapper, SignalR, JWT
Frontend: Angular, TypeScript, Bootstrap, RxJS
Database: SQL Server
Automation Tools: ChatGPT, Cursor, Replit, Cloudinary API
Deployment: IIS / Azure

⚙️ Setup Instructions

Backend

cd API
dotnet ef database update
dotnet run


API available at http://localhost:5000/swagger

Frontend

cd client
npm install
npm start


Frontend available at http://localhost:4200

📜 License

MIT License — open source and available for learning and professional use.
