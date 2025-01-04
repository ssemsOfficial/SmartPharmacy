# SmartPharmacy

# Smart Refrigeration Dashboard

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [System Requirements](#system-requirements)
- [Setup and Installation](#setup-and-installation)
- [Functionalities](#functionalities)
- [Project Architecture](#project-architecture)
- [Future Improvements](#future-improvements)
- [Acknowledgements](#acknowledgements)

---

## Overview

This project involves the development of a **Smart Refrigeration Dashboard**, an IoT-based application to manage and monitor medical refrigeration systems. Initially developed as part of an internship project at ISET Sousse, it addresses the shortcomings of an existing dashboard, focusing on improving user experience, real-time monitoring, and system control. 

### Problem Statement

The existing dashboard lacks advanced functionalities, such as:
- Real-time data visualization.
- Error notifications and history tracking.
- Professional UI/UX design.

The proposed solution is to develop a robust and user-friendly admin dashboard that transforms the project into a commercial-ready solution.

---

## Features

### Core Features

- **User Management**: Add, delete, and modify client information.
- **Fridge Management**: Add, delete, and modify refrigerator details.
- **Real-time Monitoring**: Track fridge parameters like temperature, battery status, and door status.
- **Data Visualization**: Display real-time and historical data using interactive charts.
- **Error Notifications**: Receive alerts about errors and view their history.
- **Admin Authentication**: Secure access to the dashboard.

### Design Focus

- **Performance**: Optimized for real-time operations.
- **Security**: Ensures safe handling of sensitive data.
- **UI/UX**: Professional and responsive interface.

---

## Technologies Used

### Frontend
- **HTML5**: Structuring web pages.
- **CSS3**: Styling the interface.
- **JavaScript**: Adding dynamic interactions.
- **Chart.js**: Real-time and historical data visualization.

### Backend
- **Feathers.js**: Lightweight framework for REST APIs.
- **Node.js**: Server-side JavaScript runtime.
- **Firebase**: Real-time NoSQL database.

### Tools
- **Webpack**: Module bundler for JavaScript files.
- **Git**: Version control.

---

## System Requirements

### Hardware
- **Processor**: Intel Core i5 (or equivalent) @ 2.5GHz.
- **Memory**: 8GB RAM.
- **Storage**: 1TB Hard Drive.

### Software
- **Operating System**: Windows/Linux/MacOS.
- **Node.js**: Version 16.x or later.

---

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/smart-refrigeration-dashboard.git
   ```

2. Navigate to the project directory:
   ```bash
   cd smart-refrigeration-dashboard
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Run the development server:
   ```bash
   npm start
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## Functionalities

### Admin Dashboard
- **Login Page**: Secure authentication for administrators.
- **Dashboard**: Real-time monitoring and control.
- **User Management**: CRUD operations for clients.
- **Fridge Management**: CRUD operations for refrigerators.

### Notifications
- Real-time error alerts.
- Historical error log access.

### Data Visualization
- Temperature, door status, and battery status monitoring.
- Interactive charts for historical and current data.

---

## Project Architecture

### UML Diagrams
- **Use Case Diagrams**: Define system functionalities and actor interactions.
- **Sequence Diagrams**: Detail workflows, including user authentication and data management.
- **Class Diagram**: Illustrates relationships between core classes like `Administrator`, `Client`, `Fridge`, and `Error`.

---

## Future Improvements

- **Payment Management**: Integration for handling client payments.
- **Enhanced Analytics**: Additional charts and insights for better data interpretation.
- **Mobile Application**: Extend functionality to mobile platforms.

---

## Acknowledgements

Special thanks to:
- **Mr. Mokhtar Harabi**: Supervisor at ISET Sousse.
- **Mr. Adnen Rouatbi**: Department Manager.
- **ISET Sousse**: Providing an opportunity for this project.

For references and tools used:
- [Chart.js](https://www.chartjs.org/)
- [Firebase Documentation](https://firebase.google.com/docs/web/setup)
- [Node.js](https://nodejs.org/en/)
- [Online Visual Paradigm](https://online.visual-paradigm.com/)

---

For any queries, please contact **your.email@example.com**.
