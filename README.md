# currency-converter-web
A modern, responsive web application for real-time currency conversion using live exchange rates and dynamic country flag previews.


# 💱 Currency Converter

A lightweight, responsive web application built with HTML, CSS, and JavaScript that provides real-time currency exchange rate conversion using live API data and visual country flags.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=stylelint&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

## ✨ Features

- 🌍 **Real-Time Exchange Rates**: Fetches live rates via the `@fawazahmed0/currency-api`.
- 🚩 **Dynamic Country Flags**: Displays corresponding national flags dynamically via `FlagsAPI`.
- 🔄 **One-Click Currency Swap**: Instantly switch "From" and "To" currencies with a single click.
- 📱 **Fully Responsive UI**: Clean, modern card interface designed with CSS grid/flexbox and a gradient theme.
- ⚡ **Auto-Load on Startup**: Automatically calculates conversion for default values on page load.

---

## 🛠️ Project Structure

.
├── index.html   # Application structure & markup
├── style.css    # Modern UI styles & layout
├── code.js     # Currency code to ISO country code mapping
└── script.js   # Main application logic & API fetch operations
