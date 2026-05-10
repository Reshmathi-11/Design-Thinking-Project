# 🌍 Nearwise - Discover Smarter. Travel Better.

Nearwise is a professional, high-fidelity website prototype for a Smart Location Discovery Platform. It leverages real-world mapping APIs and intelligent recommendation logic to help users explore their surroundings with precision and ease.

## ✨ Key Features

- **📍 Intelligent Geolocation:** Real-time detection of user location for hyper-local search results.
- **🗺️ Advanced Mapping Integration:** Dynamic map rendering and interactive navigation powered by industry-leading geospatial services.
- **🧠 Smart Recommendation Engine:** A "For You" system that cross-references user history with multiple data points to suggest perfect destinations.
- **🎛️ Live Radius Filtering:** Dynamic distance slider (1km - 20km) to narrow down choices in real-time.
- **📅 Direct Reservations:** Integrated booking system for instant confirmation of dining, shopping, and visits.
- **🎨 Premium Web Interface:** A sleek, modern aesthetic inspired by high-end design standards, featuring a full desktop-responsive experience.

## 🛠️ Tech Stack & Data Sources

| Purpose | Tool / Source |
| :--- | :--- |
| **Maps & Nearby Places** | Google Places API ⭐ (Best Choice) |
| **Recommendation System** | OpenStreetMap (OSM) Data |
| **Recommendation Training** | Kaggle Datasets |
| **Reviews & Ratings** | Yelp Dataset |
| **Frontend Framework** | React + Vite |
| **Styling** | Tailwind CSS (Minimalist / Professional) |

## 🚀 Getting Started

Follow these steps to run the application locally:

### 1. Install Dependencies
```bash
npm install
```

### 2. Configure Environment Variables
Create a `.env` file in the root directory:
```env
VITE_GOOGLE_MAPS_API_KEY=your_api_key_here
```

### 3. Run the App
```bash
npm run dev
```
Visit `http://localhost:5173/` in your browser.

## 📱 Platform Screens
- **Modern Auth Portal:** Split-screen Sign In / Sign Up experience.
- **Global Discovery Home:** Interactive categories and featured trending spots.
- **Smart Explore:** Category-specific discovery with real-time distance filtering.
- **Personalized "For You":** Intelligent picks based on travel history and ratings.
- **Place Hub:** Comprehensive details, HD imagery, and booking portal.
- **Integrated Live Map:** Full-screen geospatial visualization.

---
*Developed as a premier Smart Location Discovery prototype for the Travel and Tourism domain.*
