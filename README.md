# My Vanilla Weather App

A clean, responsive weather application that displays current conditions and a 5-day forecast for any city worldwide, with a dark theme toggle for comfortable viewing.
## 🌟 Project Overview

This application was created as part of the SheCodes Plus course to learn advanced front-end development and build my first interactive application, with a focus on integrating a live API to fetch real-time data and using Git and GitHub to manage my code. 

🌤️ **Live Site:** https://legendary-puppy-d04392.netlify.app/

---

## 📚 Learning Objectives

- ✅ Fetch and display data from a third-party weather API using Axios
- ✅ Handle API errors gracefully with user-friendly messages
- ✅ Manipulate the DOM dynamically with vanilla JavaScript
- ✅ Format dates and timestamps using JavaScript's `Date` object
- ✅ Implement a dark/light theme toggle with CSS class switching
- ✅ Build a clean, responsive UI with CSS Flexbox
- ✅ Validate user input before making API calls

---

## 🛠 Technologies Used

- **HTML5** — Semantic structure and accessible form elements
- **CSS3** — Flexbox layouts, smooth transitions, and dark theme styles
- **Vanilla JavaScript** — DOM manipulation, event handling, and logic
- **Axios** — Promise-based HTTP requests to the weather API
- **SheCodes Weather API** — Current weather and 5-day forecast data
- **Google Fonts** — Roboto variable font for modern typography
- **VS Code** — Code editor
- **GitHub Desktop** — Version control and source management
- **Netlify** — Deployment and hosting

---

## ✨ Key Features

### 🌍 Live Weather Search
- Search current weather conditions for any city worldwide
- Displays city name, day, time, weather description, humidity, and wind speed
- Shows a weather condition icon alongside the temperature

### 📅 5-Day Forecast
- Automatically loads a 5-day forecast after every successful search
- Shows daily high/low temperatures and condition icons for each day

### 🌙 Dark Theme Toggle
- One-click toggle between light and dark themes
- Smooth CSS transitions for a polished feel
- Dark mode uses a deep purple gradient background

### ⚠️ Error Handling
- Validates city input (minimum 2 characters required)
- Displays friendly, styled error messages for invalid cities or failed API requests
- Errors are hidden automatically on a successful new search

### 🔍 Input Validation
- Trims and normalises user input before submitting
- Prevents empty or single-character searches from hitting the API

---

## 📁 Project Structure

```
vanilla-weather-app/
├── index.html          # Main HTML structure
└── src/
    ├── style.css       # All styling, including dark theme
    └── index.js        # All JavaScript logic
```

---

## 🚀 How to View

**Option 1: View Live Deployment**
Visit: https://legendary-puppy-d04392.netlify.app/

**Option 2: Run Locally**
1. Clone or download this repository
2. Open `index.html` directly in your web browser
3. Note: Internet access is required to load the Google Font, Axios CDN, and weather API data

**Option 3: Live Server (Recommended for Development)**
1. Install [VS Code](https://code.visualstudio.com/)
2. Install the **Live Server** extension by Ritwick Dey
3. Right-click on `index.html` and select **"Open with Live Server"**
4. The site opens at `http://localhost:5500`

---

## 💡 Key Learning Takeaways

**1. Working with APIs is Powerful**
Connecting to a real-world API and rendering live data made the project feel genuinely useful. Learning to read API response structures and map them to the DOM was a big step forward.

**2. Error Handling Matters**
Anticipating what can go wrong — a mistyped city, a network failure — and handling it gracefully makes a big difference to the user experience. It also taught me to always use `.catch()` alongside `.then()`.

**3. DOM Manipulation is Satisfying**
Updating the page dynamically without a page reload, and watching the forecast cards render from a loop, made the connection between JavaScript and the browser feel real and immediate.

**4. CSS Transitions Add Polish**
Adding `transition` to background colours and borders transformed the dark mode toggle from a basic switch into something that feels smooth and intentional.

**5. Input Validation Protects the API**
Validating before sending a request avoids unnecessary API calls and gives the user clear feedback — a habit worth building early.

---

## 🔧 Browser Compatibility

Tested and working on:
- ✅ Chrome 120+ (Desktop & Mobile)
- ✅ Firefox 121+ (Desktop & Mobile)
- ✅ Safari 17+ (Desktop & Mobile)
- ✅ Edge 120+ (Desktop)

---

## 📈 Future Enhancements

**Phase 1: UX Improvements**
- [ ] Add a "Use my location" button with the Geolocation API
- [ ] Remember the last searched city using `localStorage`
- [ ] Add a loading spinner while the API request is in progress

**Phase 2: Features**
- [ ] Toggle between °C and °F
- [ ] Add hourly forecast display
- [ ] Show sunrise and sunset times

**Phase 3: Design**
- [ ] Make the app fully responsive for mobile screens
- [ ] Animate weather icons
- [ ] Add background images that change based on weather conditions

---

## 👤 Author

**Caroline Hargreaves**
Aspiring Web Developer | SheCodes Student

- 💻 [GitHub Profile](https://github.com/carolinehargreaves41-sketch)
- 🌐 [Weather App Repository](https://github.com/carolinehargreaves41-sketch/Plus_Week8_Vanilla-Weather-Forecast)

---

## 📜 License

This project is open source and available under the MIT License.

### Usage Terms
- ✅ Use for learning and education
- ✅ Fork and modify for your own projects
- ✅ Use as a portfolio piece (with credit)
- ❌ Do not claim as your own work
- ❌ Do not use commercially without permission

---

## 🙏 Acknowledgments

- **SheCodes** — For the JavaScript and API integration course
- **Matt Delac** — Founder of SheCodes and excellent instructor
- **SheCodes Weather API** — For providing the weather data
- **Axios** — For making HTTP requests simple and readable
- **Google Fonts** — For the Roboto variable font
- **Netlify** — For seamless deployment and hosting

---

*Project Status: ✅ Completed October 2025.*
*Built with 💜 and lots of 🫖 in England*
