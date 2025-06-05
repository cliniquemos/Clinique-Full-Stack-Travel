# Clinique Full-Stack Travel App
I’m very passionate about traveling—so why not mix that with another love: building great software? This is a sleek, full-stack travel planner app built with React, .NET Core, and SQL Server. Users can explore destinations, organize trips, and save personalized travel notes. I didn't finish it, but it's a work in progress.

This app showcases my full-stack engineering skills—from building responsive, modern UIs to secure, scalable APIs.

## App Features

- Explore curated destinations with photos and descriptions  
- Create and manage custom travel itineraries  
- Add personal notes or checklists for each trip  
- Register/login with secure JWT authentication  
- Responsive layout for desktop and mobile  
- Seamless front-end and back-end API integration

---

##  Tech Stack

### Frontend

- React  
- React Router DOM  
- Tailwind CSS or Material UI  
- Axios for HTTP requests  
- Context API or Redux for state management

### Backend

- .NET Core Web API  
- Entity Framework Core  
- SQL Server (or PostgreSQL)  
- AutoMapper + DTOs  
- JWT Authentication  
- CORS

---

## Local Setup Instructions

### Backend (.NET Core API)

```bash
cd backend
dotnet restore
dotnet run
```
## Frontend (React App)

# Navigate to project root
cd frontend

# If you haven't already created the app, use:
npx create-react-app frontend

# Then install dependencies
npm install

# Start the development server
npm start

##  Project Folder Structure 

```bash
roamradar-travel-app/
│
├── backend/                  # .NET Core Web API
│   ├── Controllers/
│   ├── Models/
│   ├── DTOs/
│   ├── Services/
│   ├── Data/
│   └── Program.cs
│
├── frontend/                 # React Frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── App.js
│   └── package.json
│
└── README.md                 # You're here
```
## Future Roadmap

- Deploy frontend and backend via Azure App Services + Azure SQL
- Add Google Maps route planning
- Integrate calendar view for trip timelines
- Export itineraries to PDF
- Enable shared trips & group planning features
- Screenshots (Coming Soon)

Preview of the trip planner, destination cards, and mobile views.

## Why I Built This

I love tech, and I love to travel—so I built something that reflects both. This travel app is more than a project; it’s a practical, stylish app that solves a real-world problem while giving me the chance to flex both my front-end and back-end skills. I focused on writing clean code, designing reusable components, and structuring APIs that are easy to scale.

![Frontend Code](./assets/screenshots/frontend-code.png)  
*React Trip Planner page with input, state management, and Tailwind styling.*

## App Preview

This is a working screenshot of the Plan Your Next Trip feature. It allows users to type a city, click “Add Destination,” and have their trip plans saved dynamically to a list.

![App Screenshot]()
