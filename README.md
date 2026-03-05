# Finanztracker
Fullstack web application for tracking personal finances.

## Repositories
**Frontend:**
https://github.com/llng03/ftracker  
**Backend:**
https://github.com/llng03/ftracker-frontend

## Features
- monthly Overview with Cateogories and Totals
- add single income or expense to any month
- add fixedCosts, that happen at a certain frequency (monthly, quarterly, half-annual, annual)
- pots for various saving goals
- fixed expenses that are not monthly are distributed on monthly expenses that get saved in a pot
- correction Mode for editing and deleting entries
- statistics dashboard with charts showing the distribution of expenses
- authentication via Google
- demo-Mode

## Tech Stack
**Frontend:** React(Vite), Axois  
**Backend:** Spring Web, Gradle, Spring Security (OAuth2), JWT (for demo-version)  
**Database:** PostgreSQL

## Architektur

## Setup
**0) Prerequisites**  
Make sure the following tools are installed:  
- Java 21  
- Node.js 18+  
- Docker & Docker Compose  
- Git  
  
**1) Clone repositories**  
Clone both repositories:  
  
`git clone https://github.com/llng03/ftracker`  
`git clone https://github.com/llng03/ftracker-frontend`  
  
**2) Start database**  
Start the PostgreSQL database using Docker:  
  
`docker compose up -d`  
  
**3) Start backend**  
Navigate to the backend project:  
`cd ftracker`  
  
Start the Spring Boot application:  
`./gradlew bootRun`  
  
The backend then runs at http://localhost:8081.  
  
**4) Start frontend**  
Navigate to the frontend project:  
`cd financetracker-frontend`  
  
Install dependencies:  
`npm install`  
  
Start development server:  
`npm run dev`  
  
The frontend then runs at http://localhost:5173.  
  
**5) Open Application**  
Now you can open the application in your browser:  
http://localhost:5173  
