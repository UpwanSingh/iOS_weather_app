# 🌤️ WeatherApp

A modern and responsive weather app built using **SwiftUI** and **MVVM architecture**, powered by the **OpenWeatherMap API**.

## 🚀 Features

- 🔍 Search weather by city
- 🌡️ Current weather: temperature, description, condition icon
- 📅 5-day forecast (daily at 12:00 PM)
- 📱 Clean and minimal SwiftUI interface
- 🧠 MVVM architecture
- 🔁 Async/Await networking
- ⚠️ Loading and error handling
  

WeatherApp
          
     ├── WeatherAppApp.swift           # App entry point  
     ├── Assets.xcassets               # App assets (icons, backgrounds)  
     ├── Views/  
     │   ├── ContentView.swift         # Main UI with weather overview  
     │   ├── WeatherDetailView.swift   # Detailed forecast view  
     │   ├── SearchView.swift          # Search bar for city input  
     │   └── Components/  
     │       └── WeatherCard.swift     # Reusable UI component for forecast cards  
     ├── ViewModels/  
     │   └── WeatherViewModel.swift    # Handles data fetching & state management  
     ├── Services/  
     │   └── WeatherService.swift      # API layer: fetches current weather & forecast  
     ├── Models/  
     │   ├── WeatherResponse.swift     # Data model for current weather  
     │   └── ForecastResponse.swift    # Data model for 5-day forecast  
     ├── Utilities/  
     │   ├── Constants.swift           # API keys & constants  
     │   └── Extensions.swift          # Helpful extensions (if needed)  
     └── WeatherAppTests/             # Unit tests  
<img width="1206" height="2622" alt="Simulator Screenshot - iPhone 16 Pro - 2025-08-02 at 23 57 29" src="https://github.com/user-attachments/assets/eebb1dbc-1399-451d-8e01-10d1728d618e" />
<img width="1206" height="2622" alt="Simulator Screenshot - iPhone 16 Pro - 2025-08-02 at 23 56 54" src="https://github.com/user-attachments/assets/9d991110-3793-4edb-84a7-b5dc98147b22" />

