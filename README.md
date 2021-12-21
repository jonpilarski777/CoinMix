# README
CoinMix is a fullstack web application where a user can submit a risk profile and then be provided with recommended crypto allocations based on their specified risk tolerance, which can be viewed in a dashboard that pulls price/trading data (will be using CoinGecko api)

# How to start CoinMix on your own machine:
- Download ruby (version 2.7.4) on rails (v 6.1.4) back end dependencies/gems with **bundle install**
- Start backend server with **rails s**
- Populate database columns and rows/records with **rails db:migrate db:reset; verify by making sure schema reflects column names and that the table is not empty 
- Download React front end dependencies/packages with **npm install --prefix client** (frontend packages specific for React are in package.json in client folder)
- Start frontend with **npm start --prefix client**

# Configuration/Dependencies:

## Backend:
**Ruby version 2.7.4**
**Rails version 6.1.4**
**sqlite3 version 1.4**
**bcrypt 3.1.7**

## Frontend:
**React version 17.0.2**
**React-router-dom version 5.3**
**React chart.js version 3.6.0**
**React chartjs-2 version 3.3.0**


Entity Relationship Diagram:

![]("C:\Users\Jon\OneDrive\Desktop\CoinMix ERD.png")

