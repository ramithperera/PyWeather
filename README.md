# 🌦️ PyWeather

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![PyQt5](https://img.shields.io/badge/UI-PyQt5-green.svg)
![API](https://img.shields.io/badge/API-OpenWeatherMap-orange.svg)
![Requests](https://img.shields.io/badge/Library-Requests-lightgrey.svg)
![dotenv](https://img.shields.io/badge/Config-dotenv-yellow.svg)

---

## 🧭 Overview

**PyWeather** is a modern, minimalistic weather application built with **Python** and **PyQt5** that lets users quickly check real-time weather conditions by simply entering a city name.  
It integrates with the **OpenWeatherMap API** to display temperature, weather descriptions, and even expressive **emojis** to visually represent the forecast.  

This project was built to deepen my understanding of **Python GUI development**, **API integration**, and **error handling** — while designing an intuitive interface that feels clean and enjoyable to use.

---

## ✨ Features

- 🌤 **Real-time weather data** using OpenWeatherMap API  
- 🎨 **Sleek and minimal PyQt5 GUI** with custom styling  
- 💬 **Dynamic weather emojis** for a fun visual experience  
- ⚙️ **Robust error handling** for all major HTTP issues  
- 🔐 **Environment variable support** using `.env` for API security  
- 🧊 **Temperature display in Celsius** (and internally supports Kelvin & Fahrenheit conversions)  

---

## 🧰 Tech Stack

| Category | Technologies Used |
|-----------|------------------|
| **Language** | Python |
| **GUI Framework** | PyQt5 |
| **API** | OpenWeatherMap |
| **Environment Config** | python-dotenv |
| **HTTP Requests** | requests |

---

## 🖥️ Demo

> 📸 *sample UI.*

<img width="412" height="546" alt="pyweatherApp" src="https://github.com/user-attachments/assets/75a00019-5ba6-49eb-94c3-6900b3625537" />



---

## 🚀 Getting Started

Follow these steps to run **PyWeather** locally.

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/PyWeather.git
cd PyWeather
```

### 2️⃣ Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Create a .env file in the project root
Then, add your API key inside it:

### 5️⃣ Run the application
```bash
python main.py
```

---

## ⚠️ Error Handling

PyWeather includes detailed exception handling for:

- 400: **Bad Request** (invalid input)

- 401: **Unauthorized** (invalid API key)

- 403: **Forbidden** (access denied)

- 404: **City not found**

- 500–504: **Server-side errors**

- Connection errors, timeouts, and too many redirects

Each case displays a **user-friendly** error message directly in the GUI.

---

## 💡 Motivation

“I built PyWeather to challenge myself to combine real-world **API integration** with a responsive desktop interface.
It was also a chance to explore how user experience and error resilience can make a small app feel professional.”

This project reflects my interest in clean UI design, Python software craftsmanship, and creating tools that make data simple and beautiful.

---

## 🚀 Future Improvements

- 📍 Integrate location-based weather detection

- 📅 Add 5-day forecast support

- 🌡 Switch between Celsius / Fahrenheit dynamically

- 💻 Build an installer or standalone executable

- 🌈 Improve theme customization (light/dark mode)

---


## 🧾 Requirements

Python 3.10 or higher

OpenWeatherMap API key (free registration available)

---

## 🙌 Acknowledgments

[OpenWeatherMap API](https://openweathermap.org/api)
 for providing accurate global weather data.

[PyQt5](https://pypi.org/project/PyQt5/)
 for enabling rich and elegant GUIs in Python.

 ---

 ## Getting Started

📔 Below is the requirement.txt 👇
```bash
# PyWeather - Requirements
# Install dependencies using: pip install -r requirements.txt

PyQt5==5.15.11
requests==2.32.3
python-dotenv==1.0.1
```
 
 💻 You can install everything by simply running:
 ```bash
pip install -r requirements.txt
```
