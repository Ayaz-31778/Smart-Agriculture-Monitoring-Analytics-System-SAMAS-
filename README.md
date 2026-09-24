# 🌱 Smart Agriculture Monitoring & Analytics System (SAMAS)

**SAMAS** is a Python-based smart agriculture project that collects field-condition data, analyzes agricultural conditions, stores records in CSV format, and visualizes important environmental parameters.

The project demonstrates how programming, data handling, analytics, file handling, and visualization can be combined to support data-driven agricultural monitoring.

## 📌 Project Overview

Agricultural conditions such as temperature, humidity, soil moisture, and rainfall directly affect crop growth and irrigation requirements. Monitoring these parameters manually can make it difficult to identify changing field conditions quickly.

The **Smart Agriculture Monitoring & Analytics System (SAMAS)** provides a simple software-based workflow to:

- Collect field sensor/observation data
- Store structured field records
- Analyze agricultural conditions
- Generate basic recommendations and warnings
- Calculate average environmental values
- Save records to CSV
- Visualize temperature, humidity, and soil-moisture trends

## 🎯 Problem Statement

Farmers need timely information about field conditions to make better decisions related to irrigation and crop care.

SAMAS addresses this academic problem by creating a monitoring and analytics workflow around four key parameters:

| Parameter | Purpose |
|---|---|
| 🌡️ Temperature | Identifies high/low temperature conditions |
| 💧 Humidity | Helps identify abnormal humidity levels |
| 🌱 Soil Moisture | Indicates whether irrigation may be required |
| 🌧️ Rainfall | Identifies rainfall conditions and heavy rainfall |

## ⚙️ How the System Works

~~~text
Field Data Input
      ↓
Record Creation
      ↓
Condition Analysis
      ↓
Analytics Calculation
      ↓
CSV Data Storage
      ↓
Data Visualization
      ↓
Agricultural Monitoring Report
~~~

## 🧩 Project Modules

### Module 1 — Input Handling

Collects field records from the user.

Inputs include:

- Temperature (°C)
- Humidity (%)
- Soil Moisture (%)
- Rainfall (mm)

The module also validates numeric input.

### Module 2 — Data Model

The \`FieldRecord\` class represents a field observation containing:

- Temperature
- Humidity
- Soil moisture
- Rainfall

The model converts records into a structured tuple for further processing.

### Module 3 — Analysis & Analytics

The system evaluates field conditions using predefined thresholds.

Examples include:

- High temperature → possible crop stress
- Low temperature → slower crop growth
- High humidity → possible fungal-disease risk
- Low soil moisture → irrigation may be required
- High soil moisture → avoid unnecessary watering
- Heavy rainfall → rainfall warning

The analytics component also calculates:

- Average temperature
- Average humidity
- Average soil moisture

### Module 4 — Visualization

The project uses **Matplotlib** to visualize agricultural data.

Current visualizations include:

- Temperature trend
- Humidity trend
- Soil moisture trend

## 🛠️ Technology Stack

| Technology | Usage |
|---|---|
| Python | Core application |
| CSV | Field-record storage |
| Matplotlib | Data visualization |
| Git | Version control |
| GitHub | Source-code repository |

## 📁 Repository Structure

The repository contains the following project components:

~~~text
Smart-Agriculture-Monitoring-Analytics-System-SAMAS-/
│
├── LICENSE
├── README.md
│
├── module 1 (SAMAS)
├── module 2 (SAMAS)
├── module 3 (SAMAS)
├── module 4 (SAMAS)
│
├── python project code
└── structure
~~~

The repository also documents the intended modular organization of the project:

~~~text
smart_agriculture/
│
├── main.py
├── requirements.txt
│
├── module1_foundations/
│   └── input_handler.py
│
├── module2_data_structures/
│   └── data_models.py
│
├── module3_scalable/
│   ├── analyzer.py
│   ├── analytics.py
│   └── file_handler.py
│
├── module4_ai_ml/
│   └── visualization.py
│
└── data/
    └── records.csv
~~~

## 🚀 Getting Started

### Prerequisites

Install:

- Python 3.x
- Matplotlib

### Install Matplotlib

~~~bash
pip install matplotlib
~~~

### Run the Project

The complete implementation is available in the repository under:

\`python project code\`

Run the Python program using:

~~~bash
python "python project code"
~~~

If the code is saved locally as \`main.py\`, run:

~~~bash
python main.py
~~~

### Input Example

The program asks for the number of field records and then collects values such as:

~~~text
Enter number of field records: 2

Enter details for record 1
Temperature (°C): 28
Humidity (%): 65
Soil Moisture (%): 45
Rainfall (mm): 10
~~~

The system then analyzes the conditions and generates an analytics summary.

## 📊 Example Analysis

For suitable temperature and soil-moisture values, the system can report:

~~~text
--- Field Analysis Report ---

Temperature is optimal for crops.
Humidity level is normal.
Soil moisture is adequate.
Rainfall is within safe limits.
~~~

The program also calculates average values and displays graphical trends.

## 💾 Data Storage

Field records can be saved as CSV data with the following columns:

~~~text
Temperature
Humidity
Soil Moisture
Rainfall
~~~

This provides a simple and portable format for storing agricultural observations.

## 🔮 Future Enhancements

The current project can be extended into a complete IoT-based smart agriculture platform by adding:

- Real-time sensor integration
- ESP32/Arduino connectivity
- Soil-moisture sensors
- Temperature and humidity sensors
- Automated irrigation control
- Weather API integration
- Cloud data storage
- Web dashboard
- Mobile application
- Machine-learning-based crop recommendations
- Predictive irrigation
- Alert notifications
- Historical analytics
- Multiple-field monitoring

## 🎓 Academic Learning Outcomes

This project demonstrates practical concepts involving:

- Python programming
- Functions
- Classes and objects
- Input validation
- Data structures
- Conditional analysis
- File handling
- CSV processing
- Data analytics
- Data visualization
- Modular programming

## 📌 Project Status

**Status:** Academic Project / Prototype

The current version focuses on software-based agricultural data collection, analysis, CSV storage, and visualization. Hardware/IoT integration can be added as a future development stage.

## 👨‍💻 Author

**Shaik Ayaz Dadavali**

B.Tech — Computer Science & Engineering  
KL University

GitHub: [Ayaz-31778](https://github.com/Ayaz-31778)

## 📄 License

This project is released under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

⭐ **Smart Agriculture Monitoring & Analytics System (SAMAS)**  
*A project exploring how data and technology can support smarter agricultural monitoring.*
