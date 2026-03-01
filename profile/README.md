# 🏆 Danfoss Innovator Award 2026

Welcome to the official organization for our award-winning project: **Non-Invasive Condition Monitoring and Remaining Useful Life (RUL) Prediction of DC Link Capacitors using Hybrid Physics-ML Models.**

## The Project Ecosystem
To protect our core intellectual property, our raw ML and hardware code is kept in a private repository. However, you can explore our system architecture and live dashboard below:

* **[Live Web Dashboard](https://capacitorhealthdashboard.vercel.app/)**: Real-time condition monitoring UI.
* **[Dashboard Source Code](https://github.com/sathyajith04/capacitor_health_dashboard)**: The HTML/CSS/JS powering the frontend.
* **[System Architecture & Showcase](Link-to-capacitor-monitoring-showcase-repo)**: A deep dive into our methodology, combining ESP32 edge computing, MQTT, Simulink, and XGBoost.

## Core Methodology
We developed a system that bridges physical degradation models with data-driven Machine Learning. By extracting harmonic peaks (6th and 12th) from the DC link voltage using Fast Fourier Transform (FFT), our edge device (ESP32) calculates Equivalent Series Resistance (ESR) and Capacitance (C). These values are fed into an XGBoost model trained on a physics-informed dataset to predict the Health Index (HI) and Remaining Useful Life (RUL) with high accuracy.

## The Team
* **[Sathyajith]** - [LinkedIn](https://www.linkedin.com/in/sathyajith04) / [GitHub](https://github.com/sathyajith04)
* **[Sri Nawin Krishna]** - [LinkedIn](link) / [GitHub](https://github.com/nawin-cmd)
* **[Lakshmipriya]** - [LinkedIn](link) / [GitHub](https://github.com/lakshmipriyangel)
* **[Shwetha]** - [LinkedIn](link) / [GitHub](https://github.com/shwethasundaram05)
