# Smart Water Tank Monitoring System

## 📋 Project Overview
This project simulates a Smart Water Tank Monitoring System using Python to address challenges in water management. The system tracks water levels, issues alerts when levels drop below 30%, and refills the tank to 80% automatically. It analyzes trends in water usage, explores how temperature impacts consumption, and provides a KPI dashboard to monitor performance metrics, such as water usage, refill frequency, and alerts.

This project is particularly relevant for regions like Saudi Arabia, where efficient water management is critical due to the arid climate. The insights gained from this simulation can help users prevent water shortages, reduce waste, and manage water usage more effectively.

---

## 🛠️ Features Implemented
- **Simulated Alerts:**
  - Alerts when water levels drop below 30% (Low Level alert).
  - Visual comparison of original and refilled levels to prevent shortages.
- **Automated Refill Logic:** 
  - Automatically refills the tank to 80% when the water level is low.
- **Water Usage Analysis:** Tracks daily usage and shows trends over time.
- **Temperature Impact:** Simulates how temperature influences water consumption.
- **KPI Dashboard:** 
  - Key Performance Indicators (KPIs) for water usage, refill frequency, and alert occurrences.
  - Tracks performance metrics to ensure efficient water management.

---

## 🗂️ Project Structure
📦 **water-tank-monitoring**  
├── 📁 **data/** – Water tank level CSV data  
├── 📁 **notebooks/** – Jupyter Notebooks with Python code  
├── 📁 **visuals/** – KPI dashboards and generated plots  
└── 📄 **README.md** – Project documentation (this file)  

---
## 🔧 How to Use the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/your-Renad0x/water-tank-monitoring.git
   ```
2. Navigate to the folder:
   ```bash
   cd water-tank-monitoring
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/water_tank_monitoring.ipynb
   ```
4. Run the notebook cells to see the simulation and graphs.


## 📊 Visual Dashboards
This project includes visualizations in the form of **matplotlib graphs** and **KPI dashboards** that:

- Show daily water levels throughout October 2024.
- Compare original and refilled water levels to prevent shortages.
- Highlight days when water levels dropped below the threshold.
- Analyze the relationship between temperature and water consumption trends.
- Present **KPIs** such as:
  - Water consumption per day.
  - Total number of refills.
  - Number of alerts issued.


## 🛠️ Technologies Used
- **Python**: For data simulation and analysis.
- **Jupyter Notebook**: For code development and documentation.
- **pandas**: For data manipulation and processing.
- **matplotlib**: For visualizing water levels and trends.
- **GitHub**: For version control and project hosting.
