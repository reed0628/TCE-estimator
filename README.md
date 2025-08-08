# Advanced TCE Calculator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A comprehensive, web-based tool for calculating the Time Charter Equivalent (TCE) for voyage charters, designed with realistic and detailed shipping operations in mind. This calculator allows for precise estimations by incorporating vessel performance, detailed voyage legs, and complex cost structures.

![Calculator Screenshot](https://i.imgur.com/8YvLhRk.png) 
*(建議您自行截一張計算機的圖片並替換此處連結)*

---

## ✨ Features

- **Detailed Vessel Performance**: Input specific speed and consumption data for ballast, laden, port working, and idle conditions.
- **Dynamic Voyage Calculation**: Automatically calculates sea days based on voyage distances (ballast & laden legs) and vessel speed.
- **Sea Margin**: Applies a configurable sea margin percentage to sea days for more realistic voyage time estimation.
- **Automated Port Day Calculation**: Determines port stay duration based on cargo quantity, loading/discharging rates, and specified turn times.
- **Dynamic Bunker Cost Calculation**: Computes total bunker costs automatically from voyage duration, consumption rates, and a specified bunker price.
- **Granular Cost Inputs**: Separate cost entries for loading port, discharging port, and other miscellaneous costs (e.g., ILOHC).
- **Clear & Comprehensive Summary**: The output provides a full breakdown of the calculation, including total days, total costs, net revenue, and the final TCE per day.

## 🚀 How to Use

As this is a self-contained HTML file, usage is very simple:

1.  **Download the File**: Clone this repository or download the `tce_calculator_en.html` file.
2.  **Open in Browser**: Open the `tce_calculator_en.html` file in any modern web browser (like Chrome, Firefox, Edge, or Safari).
3.  **Input Data**: Fill in the fields with your voyage and vessel data.
4.  **Calculate**: Click the "Calculate TCE" button to see the results instantly.

## 🛠️ Technology Stack

- **HTML5**: For the structure and content of the web page.
- **CSS3**: For styling and layout.
- **JavaScript (ES6)**: For all the calculation logic and DOM manipulation, with no external libraries or frameworks.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.