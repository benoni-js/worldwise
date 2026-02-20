# 🌍 WorldWise | Your Personal Travel Tracker

**WorldWise** is a feature-rich React application designed for travelers who want to document their journeys. It allows users to track visited cities and countries by interacting with a dynamic world map, keeping all travel memories in one organized place.

---

## 🚀 Features

* **Interactive Map:** Built with Leaflet, allowing users to select locations directly on the map.
* **Location Tracking:** Automatically detects city and country names via reverse geocoding.
* **Stateful URLs:** Uses the URL to store map coordinates and selected city data, making the app's state shareable and bookmarkable.
* **Travel Diary:** Add notes and dates for every city you visit.
* **Geolocation:** A "Use my position" feature to instantly find where you are on the map.
* **Authentication:** Simulated login flow to demonstrate protected routes and user-specific data.

## 🛠️ Tech Stack

* **Framework:** [React](https://react.dev/) (Vite)
* **Routing:** [React Router v6](https://reactrouter.com/)
* **State Management:** Context API & `useReducer`
* **Map Library:** [Leaflet](https://leafletjs.org/) & [React Leaflet](https://react-leaflet.js.org/)
* **Styling:** CSS Modules
* **Mock Backend:** [JSON Server](https://github.com/typicode/json-server)

## 📦 Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/benoni-js/worldwise.git](https://github.com/benoni-js/worldwise.git)
    cd worldwise
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Start the Mock API:**
    WorldWise uses `json-server` to persist data. Run this in a separate terminal:
    ```bash
    npm run server
    ```

4.  **Launch the App:**
    ```bash
    npm run dev
    ```

## 🗺️ How it Works

1.  **Login:** Enter the app (demo credentials usually predefined).
2.  **Explore:** Navigate the map and click on any city you've visited.
3.  **Log:** A form will appear with the city details; add your notes and save.
4.  **View:** Your list of cities and countries is automatically updated and persisted in your local `cities.json`.

---
