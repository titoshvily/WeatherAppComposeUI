<img width="606" height="1280" alt="image" src="https://github.com/user-attachments/assets/b242384c-9757-4811-ba40-b25fa730b515" />



```markdown
# 🌤️ Weather App Compose

A modern Android weather application built with Jetpack Compose and WeatherAPI.

## 📱 Features

- **Current Weather** - Real-time temperature and conditions
- **3-Day Forecast** - Detailed weather predictions
- **City Search** - Find weather for any location
- **Auto-refresh** - Up-to-date information
- **Beautiful UI** - Modern Material Design 3 interface

## 🛠️ Built With

- Kotlin
- Jetpack Compose
- Volley (HTTP requests)
- WeatherAPI
- Material Design 3




## 🚀 Getting Started

### Prerequisites

- Android Studio
- Android SDK API 21+
- WeatherAPI key

### Installation

1. Clone the repo
```bash
git clone https://github.com/your-username/weatherapp-composeui.git
```

2. Get free API key from [WeatherAPI.com](https://www.weatherapi.com/)

3. Add your API key in `MainActivity.kt`:
```kotlin
const val API_KEY = "your_actual_api_key"
```

4. Build and run the app

## 🏗️ Architecture

- MVVM Pattern
- Jetpack Compose UI
- State management with mutableStateOf
- Volley for network requests

## 📁 Project Structure

```
app/
├── screen/          # Composable screens
├── data/            # Data models
├── ui/theme/        # App theme
└── MainActivity.kt  # Main activity
```

## 🔧 Configuration

Get your free API key from [WeatherAPI.com](https://www.weatherapi.com/) and replace the empty string in `API_KEY` constant.

## 📄 License

Note: This is a pet project to demonstrate Android development skills. It is not intended for commercial use

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- WeatherAPI for weather data
- JetBrains for Android Studio
- Google for Jetpack Compose


