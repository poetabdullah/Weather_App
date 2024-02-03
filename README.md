# WeatherApp

## Introduction

WeatherApp is a Kotlin-based mobile application designed to provide users with comprehensive and up-to-date weather information. The app utilizes Jetpack Compose for the user interface and adheres to the principles of Clean Architecture, ensuring a scalable and maintainable structure. Users can access both hourly forecasts and current weather conditions, making it a reliable tool for staying informed about the weather.

## Features

1. **Hourly Forecast:**
   - View detailed hourly weather forecasts.
   - Plan daily activities effectively based on upcoming weather changes.

2. **Current Weather:**
   - Real-time information about the current weather conditions.
   - Instant updates to keep users informed.

## Uses

- **Daily Planning:**
  - Users can plan their day based on the hourly forecast.
  - Stay prepared for changes in weather conditions.

- **Outdoor Activities:**
  - Ideal for users engaged in outdoor activities, providing weather insights for planning.

- **Travel Planning:**
  - Useful for travelers to check the weather conditions at their destination.

## External API

The app relies on the Meteo API to fetch accurate and reliable weather data. The Meteo API serves as the backend for the weather information displayed in the application.

## User Interface (UI)

1. **Design Principles:**
   - Utilizes Jetpack Compose for building the UI, offering a modern and reactive approach.
   - Follows a Clean Architecture pattern for a well-organized and maintainable codebase.

2. **UI Components:**

   - **WeatherCard Composable:**
     - Displays key weather information such as temperature, weather type, pressure, humidity, and wind speed.
     - Utilizes Material Design components for a consistent and aesthetically pleasing UI.

3. **Theming:**
   - Colors defined in a separate `colors.kt` file to maintain a consistent color scheme.
   - DarkBlue and DeepBlue colors are used to enhance the visual appeal.

## Dependencies

The app uses various libraries and tools to enhance functionality and development:

- **Dagger-Hilt:**
  - Incorporates Dagger-Hilt for dependency injection, promoting a modular and testable architecture.

- **Retrofit:**
  - Integrates Retrofit for handling network requests and communicating with the Meteo API.

- **Google Play Services Location API:**
  - Leverages the Location API for accurate location-based weather information.

- **Compose:**
  - Takes advantage of Jetpack Compose for building a declarative and reactive user interface.

## Development Environment

- **Android Studio:**
  - Developed using Android Studio as the primary IDE for Android app development.

Feel free to contribute, report issues, or provide feedback to help improve WeatherApp. Happy coding!
