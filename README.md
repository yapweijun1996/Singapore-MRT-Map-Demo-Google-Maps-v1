# 🚇 Interactive Singapore Public Transport Map

This project provides a simple, interactive web map showcasing the Singapore MRT (Mass Rapid Transit) and LRT (Light Rail Transit) stations. It's built using the **Google Maps Platform** and features dynamic **marker clustering** for a cleaner view at different zoom levels, along with custom-styled markers and detailed information popups for each station.

## ✨ Features

*   **Interactive Map:** Explore all Singapore MRT and LRT stations visually.
*   **Dynamic Marker Clustering:** Stations automatically group into clusters when zoomed out, making the map less cluttered. Clicking a cluster zooms in to reveal individual stations.
*   **Custom-Styled Markers:** Individual stations are represented by a distinct blue dot, and clusters have custom circular designs that change size and color based on the number of stations they contain.
*   **Detailed Info Popups (InfoWindows):** Click on any station marker to view:
    *   Station Name
    *   Optional Image
    *   Description (if available)
    *   Associated Lines (e.g., North South Line, East West Line)
    *   Available Facilities
    *   A "View Details" button linking to more information (e.g., Wikipedia).
*   **Toast Notifications:** Simple messages appear to provide feedback on actions (e.g., opening a link).

## 🚀 Getting Started

To run this project, you'll need a **Google Maps API Key**.

### Prerequisites

*   **Google Maps API Key:** This is essential! Google Maps requires an API key to load the map and use its services.
    *   You can get one from the [Google Cloud Console](https://console.cloud.google.com/project/_/api/enable).
    *   Make sure you enable the **"Maps JavaScript API"** and **"Marker Library"** for your project.
    *   **Important:** Keep your API key secure and restrict its usage to your domain if deploying online. For local development, you can allow requests from `localhost`.


## 🗺️ How to Use the Map

Once the map loads:

*   **Pan and Zoom:** Click and drag to move the map, or use your mouse wheel/trackpad gestures to zoom in and out.
*   **Individual Markers:** When you zoom in close enough, individual blue circular markers will appear. Click on one to open a detailed information popup (InfoWindow).
*   **Marker Clusters:** When zoomed out, stations will group into larger colored circles with a number. This number indicates how many stations are in that cluster. Clicking a cluster will zoom the map to show its contained stations.
*   **InfoWindow Details:** Inside the popup, you'll find details about the station. If a "View Details" button is present, click it to open a new tab with more information (e.g., Wikipedia page).

## 📁 Project Structure

*   `index.html`: The main web page containing the map and all the JavaScript logic.
*   `README.md`: This file!

## 🛠️ Technologies Used

*   **HTML, CSS, JavaScript:** The core web technologies.
*   **Google Maps JavaScript API:** For creating and controlling the interactive map.
*   **@googlemaps/markerclusterer:** A library to handle the clustering of markers.

## 🤝 Contributing

This is a simple demo, but feel free to fork the repository, make improvements, and submit pull requests if you have ideas!
