# Smart Tracking of Stolen Goods in Local Markets

## Overview
A multi-platform smart system for identifying and tracking stolen goods listed or spotted in local marketplaces. This MVP combines mobile reporting, AI-based image recognition, and marketplace surveillance tools to detect potentially stolen items and notify relevant users or authorities.

## Components

### Frontend (Web App)
A React-based web dashboard for users and administrators to view, manage, and flag marketplace items. It offers interfaces for logging stolen item reports, searching suspicious listings, and viewing AI-generated alerts in real-time.

### Backend (API Server)
A Node.js + Express API that handles all data processing and communication between the frontend, mobile app, and AI service. It manages user reports, marketplace listings, authentication, and links flagged data to verified police records when available.

### Mobile App
A lightweight React Native app that allows everyday users and market inspectors to snap photos of suspicious goods, scan item barcodes, and submit instant reports. It provides push notifications for nearby flagged items and live feedback from the backend.

### AI Service
A Python microservice that uses image recognition to compare uploaded photos with a database of reported stolen goods. It uses feature matching, visual similarity detection, and basic object classification to support field inspections and backend alerts.

## How to Use
- Launch the mobile or web app
- Upload or capture item images
- Receive alerts if the item matches any reported stolen items
- Authorities or admins can follow up through the dashboard

## License
MIT License
