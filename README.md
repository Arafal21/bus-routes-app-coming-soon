# Bus routes

App inspired by https://zbiorkom.live/krakow (A little bit)

Planned project start: 2025/09/01
Planned project completion: 2026/11/30

A powerful web application for designing and optimizing city bus networks with both manual controls and AI-powered suggestions. Perfect for urban planners, local governments, and community groups who need flexible tools to plan routes and stops even in areas without existing public transit.


## 🚍 Key Features

- **Manual Bus Addition**: Add buses to any city area, even where no lines currently exist. Customize the number of vehicles and their schedules to meet local needs.
- **AI-Powered Demand Insights**: Let our AI analyze population density and movement patterns to suggest where new bus routes and stops may be most needed.
- **Area & Route Mapping**: Draw or highlight the service area directly on the map. The app will automatically generate optimal route paths within the selected boundaries.
- **Stop Placement**: Based on your defined area, the system proposes strategic bus stop locations, or you can place stops manually to fine-tune passenger pickup points.
- **Traffic-Aware ETA**: View estimated arrival times for each bus taking into account real-time or historical traffic congestion (e.g., red zones on the map).
- **Interactive Map Interface**: Pan, zoom, and draw regions on a map overlay to sculpt routes and monitor bus operations.

## 🛠 Tech Stack

- **Frontend**: React
- **Backend**: Python with FastAPI
- **Database**: PostgreSQL
- **Real-Time & Mapping**: Socket.IO for live updates and Mapbox GL JS for an interactive map interface.  
- **AI & Data Processing**: Python

## 🤖 AI FEATURES

- **Demand Prediction**: AI models ingest mobile and pedestrian flow data to forecast high-traffic corridors and recommend new routes.
- **Stop Location Optimization**: Using clustering algorithms, the system clusters points of interest and high footfall zones to place stops where they maximize ridership.
- **Adaptive Route Balancer**: Continuously adjusts suggested routes and bus frequency based on time-of-day traffic patterns and observed passenger loads.

## 📊 Statistics & Reporting

- **Arrival Time Estimates**: For each route and stop, view near real-time ETAs considering traffic conditions from integrated map services.
- **Performance Dashboards**: Monitor average travel times, stop dwell times, and passenger wait times with automatically generated charts.
- **Exportable Reports**: Download route summaries and performance metrics as CSV or PDF for presentations and planning meetings.

## 🛠️ Tech Stack - fullstack by me:

- **Frontend **: React + Tailwind CSS  
- **Backend **: Node.js + Express + Python + AI API
- **Real-time**: Socket.io  
- **Database**: MongoD
