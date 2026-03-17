# Lag-Mover
Navigation App
# LAGMOVER - Your City, Your Pace 🇳🇬

**LAGMOVER** is a comprehensive, mobile-responsive navigation application specifically tailored for the unique transit ecosystem of Lagos, Nigeria. It provides commuters with a robust platform to plan trips, estimate costs, and receive smart transit advice across multiple local transportation modes.

## 🎯 Project Objective
The primary goal of LAGMOVER is to provide a high-utility transit solution that remains cost-effective for the developer while offering professional-grade data to the user. It addresses the "last mile" challenge by integrating localised transport modes that mainstream apps often overlook.

## ✨ Key Features
* **Multi-Modal Routing**: Supports specialized Lagos transport options including **BRT**, **Danfo (Bus)**, **Keke Marwa**, and **Okada**.
* **Real-Time Fare Estimation**: Dynamically calculates estimated trip costs in Nigerian Naira (₦) based on distance and selected transport mode.
* **AI-Driven Suggestions**: Provides smart advice on the most efficient way to travel based on trip length (e.g., suggesting a walk or Keke for short distances).
* **Hybrid Map Infrastructure**: Utilises a cost-saving architecture that pairs the free **Leaflet.js** visual engine with the high-accuracy **Google Maps API** for routing.
* **GPS & Proximity Alerts**: Includes "My Location" tracking and automatic alerts to notify users before they reach their destination.

## 🛠️ Technical Stack
* **Frontend**: HTML5, CSS3 (Modern UI with Lagos-inspired branding).
* **Map Engine**: Leaflet.js (OpenStreetMap Tiles) for unlimited free map loads.
* **Routing Engine**: Google Maps Directions API & Places Autocomplete.
* **Data Processing**: Custom Polyline Decoder to render Google's encrypted path data onto the Leaflet map.

---
*Developed for the Lagos commute — helping you navigate the city at your own pace.*
