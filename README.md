# Weather App

A simple and interactive weather application built using **React + Vite** that fetches real-time weather data from an API.

## Features
- Get current weather information for any city
- Displays temperature and humidity
- Search functionality for different locations
- Fast performance with Vite

## Tech Stack
- **Frontend**: React, Vite
- **Styling**: Tailwind CSS (or any other CSS framework used)
- **API**: OpenWeatherMap API

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/sanju51/Weather-app.git
   cd weather-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **API Integration**
   - The app fetches real-time weather data using the **OpenWeatherMap API**.
   - Get your API key from [OpenWeatherMap](https://openweathermap.org/).
   - The API key is directly added to `SearchBox.jsx` instead of a `.env` file.

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

## Usage
- Enter a city name in the search bar and get real-time weather updates
- See temperature, humidity, wind speed, and weather conditions
- Enjoy a clean and user-friendly interface

## Folder Structure
```
weather-app/
├── public/            # Static public files
│   ├── vite.svg
├── src/
│   ├── assets/        # Static assets
│   ├── App.css        # Global styles
│   ├── App.jsx        # Root component
│   ├── InfoBox.css    # Styles for InfoBox
│   ├── InfoBox.jsx    # InfoBox component
│   ├── SearchBox.css  # Styles for SearchBox
│   ├── SearchBox.jsx  # SearchBox component (Contains API Key)
│   ├── WeatherApp.jsx # Main weather app component
│   ├── index.css      # Global CSS
│   ├── main.jsx       # Entry point
├── .gitignore         # Ignored files
├── README.md          # Project documentation
├── eslint.config.js   # ESLint configuration
├── index.html         # Main HTML file
├── package-lock.json  # Dependency lock file
├── package.json       # Dependencies and scripts
├── vite.config.js     # Vite configuration
```

```bash
npm run build
```
Then, follow the specific deployment instructions for your hosting provider.

## Contributing
Feel free to contribute! If you find any bugs or want to add new features, submit a pull request.

---
**Author**: Sanjana B U  
**GitHub**: https://github.com/sanju51


