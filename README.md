# Chemical-process-anomaly-detection.
End-to-end data analysis &amp; anomaly detection in chemical processes.
## Project Overview
This project analyzes sensor data from a chemical process to identify normal behavior and detect anomalies using Python and machine learning techniques.  
The goal is to gain insights into process performance and highlight unusual events, demonstrating end-to-end data analysis skills.

---

## Dataset
The dataset (`sensor_data.csv`) contains sensor readings with the following columns:

| Column | Description |
|--------|-------------|
| timestamp | Timestamp of the sensor reading |
| temperature | Reactor temperature (°C) |
| pressure | Reactor pressure (bar) |
| flow_rate | Flow rate (L/min) |
| vibration_level | Equipment vibration levels |
| valve_position | Valve opening position (%) |
| motor_speed | Motor speed (RPM) |
| chemical_concentration | Chemical concentration (%) |
| anomaly_label | 0 = Normal, 1 = Anomaly |

---

## Key Insights
- Outliers and anomalies were detected using **statistical and ML-based methods**.  
- Certain sensors (e.g., flow_rate, vibration_level) show significant variation during anomalous events.  
- Regression models were attempted, but anomaly detection was more effective for identifying unusual behavior.  

All visualizations, including time-series plots, boxplots, and correlation analysis, are available in the notebook `chemical_process_anomallies_analysis.ipynb`.

---

## How to Run
1. Clone or download this repository.  
2. Open `chemical_process_anomallies_analysis.ipynb` in **Jupyter Notebook** or **Google Colab**.  
3. Run all cells sequentially to reproduce the analysis.

---

## Skills Demonstrated
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Data Analysis:** Data cleaning, EDA, visualization, anomaly detection  
- **Machine Learning:** Regression attempts, anomaly detection  
- **Portfolio-ready workflow:** Organized notebook, dataset, and README  

---

## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
