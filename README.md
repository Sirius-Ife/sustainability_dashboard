# **Sustainability Dashboard for Pallet Trader**

This repository contains the code, data, and documentation for a **Sustainability Dashboard** designed to track and visualize sustainability metrics for Pallet Trader. The dashboard focuses on critical metrics such as CO₂ emissions, recycled materials percentage, and sustainability efforts over time, providing actionable insights.

---

## **Project Overview**
The goal of this project is to create an interactive Power BI dashboard that enables stakeholders to:
- Monitor key sustainability metrics.
- Track progress toward recycling and emission reduction goals.
- Identify trends in sustainability performance.

---

## **Features**
- **CO₂ Emissions Analysis**: Visualize total and average CO₂ emissions over time.
- **Recycled Materials Monitoring**: Track the percentage of recycled materials used.
- **Sustainability Metrics**: Gain insights into monthly and yearly trends.
- **Interactive Dashboard**: Filter by time, category, and other key parameters.

---

## **Technologies Used**
- **R**: For generating and preparing the dataset.
- **Power BI**: For creating the sustainability dashboard.
- **CSV**: Dataset format for compatibility and simplicity.

---

## **Data**
### **Dataset**
The dataset includes sustainability metrics for one year, generated using R. Key columns include:
- `Date`: Daily records spanning one year.
- `CO2_Emissions`: Amount of CO₂ emitted (kg).
- `Recycled_Materials_Percentage`: Percentage of materials recycled.
- `Energy_Usage`: Energy consumed (kWh).
- `Waste_Reduction`: Waste reduction efforts (kg).
- `Sustainability_Costs`: Costs associated with sustainability programs ($).

### **Data Dictionary**
| **Column Name**             | **Description**                          |
|-----------------------------|------------------------------------------|
| `Date`                      | Date of the record (YYYY-MM-DD).         |
| `CO2_Emissions`             | Total CO₂ emissions (kg).                |
| `Recycled_Materials_Percentage` | Percentage of recycled materials used. |
| `Energy_Usage`              | Energy consumed (kWh).                   |
| `Waste_Reduction`           | Amount of waste reduction (kg).          |
| `Sustainability_Costs`      | Costs for sustainability efforts ($).    |

---

## **Steps to Reproduce**
### **1. Dataset Generation**
- Use the `data_generation.R` script provided in the `/scripts` folder to generate the dataset. 
- The dataset will be saved as `sustainability_data.csv`.

### **2. Load Data in Power BI**
- Import `sustainability_data.csv` into Power BI.
- Use the step-by-step guide in the `/documentation` folder to set up visuals.

### **3. Dashboard Creation**
Follow the instructions for creating the following visuals:
- Line chart: *Recycled Materials Over Time*.
- Bar chart: *Monthly Sustainability Costs*.
- KPIs: *Year-to-Date CO₂ Emissions and Waste Reduction*.

---

## **Contact**
For questions or collaboration, feel free to reach out:
- **Author**: Ife Abe
- **Email**: abeifeoluwa21@gmail.com

---
