
🌾 AgriSmart ---- Fertilizer Recommendation System
A smart, AI-powered application that recommends the most suitable fertilizers for farmers. It works in two modes:

Soil Report-Based Recommendation – Uses a Machine Learning model (Random Forest) trained with Scikit-learn.
Location-Based Recommendation – Uses Google's Gemini API based on location, crop, season, and soil type.
🚀 Features..
🧪 Accepts detailed soil reports and predicts optimal fertilizers using ML.
📍 Uses Gemini API for farmers who don't know soil data, by analyzing location + crop data.
🔐 Clerk-based user authentication.
📊 Data visualization with Recharts.
🌐 Seamless, fast frontend with React + Vite + TypeScript.
🛠 Tech Stack
Frontend
Feature	Tech
Framework	React + TypeScript
Build Tool	Vite
UI Libraries	shadcn-ui, Radix UI, Tailwind CSS
State Management	React Hooks
Authentication	Clerk
Routing	React Router DOM
Forms & Validation	React Hook Form + Zod
Data Visualization	Recharts
HTTP Client	Axios
API Integration	TanStack React Query..

Backend: This project does connects to external APIs like Gemini and optionally a hosted ML model.

🧠 How It Works
1. Soil-Based Recommendation (Machine Learning)
Input: N, P, K, pH, Moisture, Humidity, Temperature, Crop.
Output: A recommended fertilizer based on Random Forest classification.
2. Location-Based Recommendation (Gemini API)
Input: Location, Crop Type, Soil Type, Season.
Output: AI-generated fertilizer suggestions from Gemini API.
