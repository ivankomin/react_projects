# WorldWise

A React-based Single Page Application (SPA) that allows users to track their travels by logging the cities and countries they have visited on an interactive world map.

This project demonstrates the implementation of complex routing, global state management, and the integration of third-party interactive libraries within a modern React environment.

## Tech Stack

* **Core:** React
* **Routing:** React Router
* **State Management:** Context API
* **Map Integration:** Leaflet & React-Leaflet
* **Styling:** CSS Modules
* **Build Tool:** Vite

## Key Features

* **Interactive Map:** Users can click on the map to select locations and add new cities to their travel list using `react-leaflet`.
* **Geolocation Integration:** Automatically detect and navigate to the user's current physical location on the map via the browser's Geolocation API.
* **City & Country Tracking:** View a detailed list of visited cities and a dynamically derived list of countries based on the travel history.
* **URL State Management:** Stores map coordinates directly in the URL (using query parameters), ensuring the map position is preserved across reloads and can be easily bookmarked or shared.
* **Global Context:** Utilizes the Context API to seamlessly manage the core list of cities and
