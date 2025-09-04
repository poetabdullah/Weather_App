# 🌦️ WeatherApp

![Kotlin](https://img.shields.io/badge/Kotlin-1.9-blueviolet?style=flat\&logo=kotlin)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-UI-green?style=flat\&logo=jetpackcompose)
![Architecture](https://img.shields.io/badge/Clean_Architecture-✓-brightgreen?style=flat)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat)

## 📌 Introduction

**WeatherApp** is a modern **Kotlin-based Android application** that delivers **real-time and hourly weather updates** in a clean, intuitive interface.

Built with **Jetpack Compose** and following **Clean Architecture**, the app ensures **scalability, maintainability, and testability**, making it not only useful for end-users but also a great learning resource for developers exploring modern Android practices.

---

## ✨ Features

✅ **Hourly Forecasts** – Track detailed hourly updates to plan your day.
✅ **Current Weather** – Get instant access to real-time conditions.
✅ **Location-Based Data** – Automatically fetches local forecasts via GPS.
✅ **Clean UI** – Built with Jetpack Compose + Material Design principles.
✅ **Scalable Architecture** – Powered by Clean Architecture & DI with Hilt.

---

## 🎯 Use Cases

* **Daily Planning:** Organize tasks with accurate forecasts.
* **Outdoor Activities:** Check conditions before sports, hikes, or events.
* **Travel Prep:** Instantly view weather at your current or destination city.

---

## 🌍 Data Source

The app integrates with the [**Meteo API**](https://open-meteo.com/) for reliable and accurate weather information.

* 🌡️ Temperature
* 🌬️ Wind Speed
* 💧 Humidity
* 📊 Pressure

---

## 🖼️ User Interface

* **Jetpack Compose** → Declarative, reactive, and modern UI framework.
* **WeatherCard Composable** → Displays temperature, condition, humidity, pressure, and wind speed.
* **Custom Theming** → Centralized in `colors.kt` for consistency.

  * 🎨 DarkBlue & DeepBlue for visual depth.
* **Material Design 3** → Ensures modern, polished user experience.

---

## ⚙️ Tech Stack & Dependencies

* **Language:** Kotlin
* **UI:** Jetpack Compose
* **Architecture:** Clean Architecture (Domain, Data, Presentation layers)
* **DI:** Dagger-Hilt
* **Networking:** Retrofit + OkHttp
* **Location:** Google Play Services Location API
* **Async:** Kotlin Coroutines + Flow

---

## 🛠️ Development Setup

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/WeatherApp.git
   cd WeatherApp
   ```
2. Open in **Android Studio (latest stable)**.
3. Sync Gradle & build the project.
4. Run on an emulator or physical device (API 24+ recommended).

---

## 📂 Project Structure

```
WeatherApp/
 ┣ data/             # Repositories, API, DTOs
 ┣ domain/           # Use cases, models
 ┣ presentation/     # UI, ViewModels, Compose screens
 ┣ di/               # Dependency injection setup (Hilt)
 ┣ ui/theme/         # Colors, typography, themes
 ┗ utils/            # Common helpers & extensions
```

---

## 🤝 Contribution

Contributions are welcome! 🎉

* Fork the repo
* Create a feature branch (`git checkout -b feature/amazing-feature`)
* Commit your changes (`git commit -m 'Add amazing feature'`)
* Push to the branch (`git push origin feature/amazing-feature`)
* Open a Pull Request 🚀

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use and modify.

---

## 💡 Future Improvements

* 🌍 Multi-city weather tracking
* 📱 Widgets for quick glance weather
* 🔔 Severe weather notifications
* 🗺️ Interactive maps with weather layers

---

👉 With **WeatherApp**, you’re always one step ahead of the weather! 🌤️
