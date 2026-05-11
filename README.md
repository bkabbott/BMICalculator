# JavaFX BMI Calculator

A lightweight, desktop-based Body Mass Index (BMI) calculator built using **JavaFX**. This application provides a clean graphical user interface (GUI) to help users determine their BMI and weight category based on their height and weight.

---

## Preview

<img width="245" height="146" alt="image" src="https://github.com/user-attachments/assets/2ebb5fac-4cfc-4db3-a609-e677734e5ffa" />

---
## 🚀 Features

* **Real-time Calculation:** Instantly calculates BMI based on metric input (kg and meters).
* **Health Categorization:** Automatically identifies the BMI category:
* **Underweight:** < 18.5
* **Normal:** 18.5 – 24.9
* **Overweight:** 25.0 – 29.9
* **Obese:** 30.0+


* **Input Validation:** Simple check to ensure both fields are populated before calculating.
* **Reset Functionality:** Easily clear all fields with a single click.
* **User-Friendly Layout:** Uses a structured `GridPane` and `BorderPane` for a consistent UI experience.

---

## 🛠️ Built With

* **Java 21** (or higher)
* **JavaFX 17+**
* **CSS/Layout:** JavaFX Scene Graph

---

## 📖 How to Use

1. **Enter Weight:** Input your weight in kilograms (kg) in the first field.
2. **Enter Height:** Input your height in meters (m) in the second field.
3. **Calculate:** Click the **Calculate** button to see your numerical BMI and health status.
4. **Reset:** Click the **Reset** button to clear the inputs and start over.

---

## ⚙️ Setup and Installation

### Prerequisites

* [Java Development Kit (JDK)]() installed.
* JavaFX SDK downloaded and configured in your environment or IDE.

### Running the Application

If you are using a terminal and have JavaFX configured, navigate to the source folder and run:

```bash
javac --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls BMICalculator.java
java --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls bmi.BMICalculator

```

---

## 🏗️ Future Development

Future updates will focus on global accessibility by implementing a dual-unit system that allows users to toggle between metric and imperial measurements. This enhancement will introduce a selection interface—such as a toggle switch or dropdown menu—to switch between kilograms/meters and pounds/feet-inches, supported by backend logic incorporating the imperial conversion factor ($703 \times \frac{lb}{in^2}$). To ensure a seamless user experience, the UI will be refined to include dedicated input fields for feet and inches, alongside robust error handling to manage non-numeric inputs and unit-specific edge cases.
---

## 📝 Author

**Tyrone Darby**

*Created: May 11, 2026*

---

## ⚖️ License

This project is open-source and available for educational purposes.
