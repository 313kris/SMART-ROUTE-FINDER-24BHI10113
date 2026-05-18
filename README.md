Name - Kristi Roy 
24BHI10113

# SMART-ROUTE-FINDER " Master GPS " 
Intelligent Java-based route safety predictor that analyzes traffic, weather, and accident data to recommend the safest path.
 Master GPS – Intelligent Route Safety Predictor

Overview

**Master GPS** is a Java-based desktop application that helps users choose the safest and most efficient travel route.
It analyzes multiple factors like traffic, weather conditions, accident data, and road quality to generate a **risk score** for different routes and recommends the best one.

This project demonstrates how real-world problems like road safety and navigation can be solved using core Java concepts.

---

 Problem Statement

Many navigation systems focus only on distance or time but ignore **safety factors** such as accidents, weather, and road conditions.
This project aims to provide a **safer navigation alternative** by incorporating these critical parameters.

---

 Features

 Input source and destination
Generates multiple possible routes
Calculates **risk score** based on:

  * Traffic level
  * Weather conditions
  * Accident data
  * Road quality
 Displays **route comparison graph**
 Shows **weather details** for routes
 Intelligent recommendation:

  * Safe route
  * Fast route
  * Balanced route
* 🌐 Opens routes in **Google Maps**
* 🔊 Text-to-speech output (device dependent)

---

 Technologies Used

* **Language:** Java
* **GUI:** Swing
* **Concepts Used:**

  * Object-Oriented Programming (OOP)
  * Classes & Objects
  * Collections (ArrayList, HashMap)
  * Exception Handling
  * Event Handling
  * Graphics (for plotting graph)

---

 How It Works

1. User enters **source and destination**
2. System generates **3 possible routes**
3. Each route is analyzed using:

   * Traffic data
   * Weather conditions
   * Accident probability
4. A **risk score** is calculated
5. System recommends the best route based on user preference
6. Graph and detailed analysis are displayed

---

Risk Calculation Formula

```
Risk = 0.4 × (Accidents/100)
     + 0.3 × (Traffic/10)
     + 0.2 × (Weather/10)
     + 0.1 × (Road/10)
```

---

 Project Structure

```
MasterGPS/
│── MasterGPS.java
│── README.md
```

---

How to Run

### Step 1: Compile

```
javac MasterGPS.java
```

### Step 2: Run

```
java MasterGPS
```

---

 Sample Output

* Route A → Risk: 0.45 (Safe)
* Route B → Risk: 0.72 (High Risk ⚠)
* Route C → Risk: 0.60 (Moderate)

Recommended Route: **Route A (Safest)**

---

 Limitations

* Uses **simulated/random data** (not real-time APIs)
* Map is opened in browser (not embedded fully)
* Speech feature depends on system compatibility

---

 Future Enhancements

* Integration with real-time APIs (Google Maps, Weather API)
* AI/ML-based risk prediction
* Mobile application (Android/Flutter)
* Voice-based navigation assistant
* Real-time accident alerts

---

 Learning Outcomes

This project helped in understanding:

* Real-world problem solving using Java
* GUI development using Swing
* Data handling and logic building
* Application design and user interaction

---

## 👨‍💻 Author

Kristi Roy
24BHI10113
B.Tech CSE (Health Informatics)
VIT Bhopal University

---

 License

This project is developed for academic purposes as part of the **Programming in Java BYOP Course Project**.

---
