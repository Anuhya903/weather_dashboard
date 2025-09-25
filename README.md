🌤️ Dynamic Weather Dashboard

A modern, responsive, and accessible **Weather Dashboard** built with **HTML, TailwindCSS, and Vanilla JavaScript**.
This app fetches real-time weather data from **OpenWeatherMap** and provides a beautiful user experience with dynamic backgrounds, animated effects, and forecast details.

---

## 🚀 Features

* **Real-time weather data** powered by [OpenWeatherMap](https://openweathermap.org/).
* **Search by city or ZIP** (geocoding API).
* **Geolocation support** to detect your current location.
* **Dynamic backgrounds & icons** that change with weather conditions (sunny, cloudy, rainy, snowy, stormy, night).
* **Unit toggle** between Celsius (°C) and Fahrenheit (°F).
* **5-day forecast** with quick daily summaries.
* **Weather highlights** including sunrise, sunset, humidity, pressure, UV index, wind speed, clouds, and visibility.
* **Accessibility ready**: keyboard navigation, ARIA labels, focus styles.
* **Responsive UI**: mobile-first, smooth transitions, fluid card design.

---

## 📸 Preview

*(Add a screenshot or GIF of your dashboard here if possible)*

---

## 🛠️ Tech Stack

* **Frontend**: HTML5, CSS3, TailwindCSS, Vanilla JavaScript
* **Weather API**: [OpenWeather One Call API](https://openweathermap.org/api/one-call-3) + Geocoding API
* **Icons & Animations**: Custom SVGs, CSS animations

---

## ⚙️ Setup & Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/weather-dashboard.git
   cd weather-dashboard
   ```

2. **Get an API key from OpenWeatherMap**

   * Sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up)
   * Go to your [API keys](https://home.openweathermap.org/api_keys) page
   * Copy your key

3. **Insert your API key**

   * Open `index.html`
   * Find this line in the script section:

     ```js
     const OPENWEATHER_API_KEY = 'YOUR_API_KEY_HERE';
     ```
   * Replace `'YOUR_API_KEY_HERE'` with your API key.

4. **Open the project**

   * Simply open `index.html` in your browser.
   * Or use a local server (recommended for geolocation features):

     ```bash
     npx serve
     ```

     Then open the given localhost URL.

---

## 🌍 Usage

* Click **Detect** to fetch weather for your current location.
* Enter a **city name or ZIP code** and click **Search**.
* Toggle between **°C and °F** using the unit switch.
* Scroll through the **5-day forecast** and click on any card for details.

---

## 📖 Notes

* By default, if geolocation is blocked or denied, the app loads weather data for **New Delhi, IN**.
* This is a **single-page prototype** — for production:

  * Move CSS into a proper Tailwind build pipeline.
  * Hide API keys securely on a backend server.
  * Improve caching & error handling.

---

## 📌 Future Enhancements

* Hourly weather charts for each forecast day.
* Search suggestions with autocomplete.
* Save favorite locations.
* Dark mode toggle.

---

## 👩‍💻 Developer Notes

* Accessible design with **keyboard support** and ARIA labels.
* Uses **localStorage** to remember user’s temperature unit preference.
* Optimized for **mobile-first** browsing.

---

## 📜 License

This project is open source under the **MIT License**.
Feel free to use, modify, and share!

---

✨ Made with ☀️ by *[Vemu Lakshmi Anuhya]*
