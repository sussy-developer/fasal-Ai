# 🌾 Smart Farming Advisor App
AI-powered mobile application designed to help farmers make smarter decisions about **crops, soil, fertilizers, diseases, weather**, and marketplace connectivity — all in one platform.

# UI screenshots:
![opening](fasal-Ai/opening.png)
![log_in](fasal-Ai/log_in.png)
![location selection](fasal-Ai/location_entering.png)
![Home dash](landing.png)

## 📂 Project Structure:

/lib
/screens
/widgets
/models
/assets
/screenshots
/icons
#technologies : 

| Component | Technology Used |
|----------|-----------------|
| Frontend App | Flutter (Dart) |
| Backend | Node.js / Express |
| Database | MongoDB |
| AI Models | CNN / Transfer Learning / RBM |
| APIs | OpenWeather, OSM Geo API |
| Authentication | Firebase/Auth |


## ✅ Features

### 🔍 1. Soil & Crop Advisory
- Upload soil photo
- CNN / Transfer Learning model analyzes:
  ✅ Moisture  
  ✅ Color  
  ✅ Texture  
- Suggests best crop for that soil

### 🧪 2. Fertilizer Recommendation
- Farmer answers simple questions:
  ✅ Previously grown crops  
  ✅ Fertilizers used  
  ✅ Current soil condition  
- AI model + RBM suggests best fertilizer


### 🌱 3. Disease Detection
- Upload leaf / plant photo
- Trained using PlantVillage & Kaggle datasets
- Detects disease + gives treatment suggestions


### 🌦 4. Realtime Weather Forecast
- Live weather using **OpenWeather API**
- Hourly & weekly forecast

- ### 🛒 5. Farmer Community & Marketplace
- Finds nearby marketplaces using **Open Street Map**
- Community chat & AI-powered support
- Language support for native languages

