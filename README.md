# Personal-Carbon-Footprint-Optimization

Personal Carbon Footprint Optimization is a Streamlit-based web application that helps users calculate, track, and reduce their CO₂ emissions.  
It provides personalized reduction plans, eco-friendly place recommendations, and daily sustainability challenges to promote greener living.

---

## Prerequisites

Before running the application, ensure you have the following:

- Python 3.8 or higher installed  
- Google Cloud account with billing enabled  
- Google API Key (for Maps and Places)  
- Optional: Vertex AI access for AI-driven eco insights  

**Note:**  
Create a `.env` file to store your API keys and credentials securely.  
Do **not** commit this file to version control.

---

## Features

- Calculate and track personal CO₂ emissions  
- Set yearly reduction targets and monitor progress  
- Discover eco-friendly locations nearby (parks, gardens, sanctuaries)  
- Receive actionable CO₂ reduction suggestions  
- View eco scores and virtual tree-planting stats  
- Generate downloadable CSV reports  
- Interactive chatbot for eco-awareness and guidance  
- Daily “Go Green” challenges for motivation  

---

## 🔑 API Keys Required

| Service               | Purpose                                    |
|------------------------|--------------------------------------------|
| Google Maps API        | Display maps and locations                 |
| Google Places API      | Fetch nearby eco-friendly places           |
| Geocoding API          | Get coordinates from city/state            |
| Vertex AI API (optional) | AI-powered environmental recommendations |
| Compute Engine API     | Cloud app deployment                       |
| GCP Services API       | Resource and access management             |

---

## Tech Stack

| Layer         | Technology                                                                 |
|---------------|----------------------------------------------------------------------------|
| Frontend      | ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white) |
| Backend       | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) |
| Visualization | ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=python&logoColor=white) |
| Mapping       | ![Folium](https://img.shields.io/badge/Folium-77B300?logo=leaflet&logoColor=white), ![streamlit-folium](https://img.shields.io/badge/Streamlit--Folium-4F46E5?logo=python&logoColor=white) |
| Geolocation   | ![Geopy](https://img.shields.io/badge/Geopy-60A5FA?logo=python&logoColor=white) |
| Data Handling | ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) |
| Environment   | ![dotenv](https://img.shields.io/badge/dotenv-214B8A?logo=python&logoColor=white) |
| Tunneling     | ![Pyngrok](https://img.shields.io/badge/Pyngrok-4F46E5?logo=python&logoColor=white) |
| Cloud AI (optional) | ![Vertex AI](https://img.shields.io/badge/Vertex%20AI-4285F4?logo=googlecloud&logoColor=white) |
| Deployment    | ![Google Cloud Platform](https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white) |

---
