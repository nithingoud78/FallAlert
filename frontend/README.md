# Frontend Dashboard

The Frontend Dashboard provides a real-time monitoring interface for the Fall Detection System. It enables users to view fall alerts, monitor device status, access location information, and analyze recorded events through a web-based dashboard.

---

## Features

* Real-time fall alert monitoring
* Device status visualization
* Event history tracking
* GPS location display
* Responsive user interface
* Backend API integration
* Live data updates

---

## Technology Stack

* React
* JavaScript
* Axios
* Socket.IO Client
* HTML5
* CSS3

---

## Project Structure

```text
frontend/
│
├── public/
├── src/
├── package.json
├── package-lock.json
└── README.md
```

---

## Prerequisites

Before running the frontend application, ensure the following are installed:

* Node.js
* npm (Node Package Manager)

Verify installation:

```bash
node -v
npm -v
```

---

## Installation

Install project dependencies:

```bash
npm install
```

---

## Available Scripts

### Start Development Server

```bash
npm start
```

Runs the application in development mode.

Open:

```text
http://localhost:3000
```

The page automatically reloads when changes are made.

---

### Run Tests

```bash
npm test
```

Launches the test runner in interactive watch mode.

---

### Build for Production

```bash
npm run build
```

Creates an optimized production build in the `build` directory.

Features:

* Optimized bundle size
* Minified assets
* Production-ready deployment files

---

### Eject Configuration

```bash
npm run eject
```

**Warning:** This operation is irreversible.

Ejecting copies all build configurations and dependencies into the project, allowing complete customization of the build process.

---

## Backend Integration

The frontend communicates with the backend services to:

* Receive fall detection alerts
* Display device information
* Retrieve event history
* Display GPS location data
* Visualize monitoring information

---

## Deployment

To create a production-ready build:

```bash
npm run build
```

Deploy the generated contents of the `build` folder to your preferred hosting platform.

---

## Future Enhancements

* Dark Mode Support
* Advanced Analytics Dashboard
* Multi-Device Monitoring
* Real-Time Notifications
* Mobile Responsive Improvements
* User Authentication

---

## License

This project is part of the Fall Detection System repository and follows the repository license.
