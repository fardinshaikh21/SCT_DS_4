# 🚦 Traffic Accident Data Analysis – Task 4

This project focuses on analyzing traffic accident data to identify trends related to **road conditions**, **weather**, and **time of day**. Using data visualization, we uncover accident hotspots and the most significant contributing factors to road accidents.

---

## 🎯 Project Objectives

- Clean and preprocess traffic accident data.
- Analyze accident distribution across different times and days.
- Identify key weather and road surface conditions related to accidents.
- Visualize accident hotspots and patterns using Python libraries.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – data manipulation and cleaning
- **Matplotlib** – plotting graphs
- **Seaborn** – statistical data visualization
- **Jupyter Notebook**

---

## 📊 Data Analysis Performed

1. **Missing Value Handling**:
   - Checked for missing values.
   - Dropped rows with null values to ensure clean analysis.

2. **Time-Based Accident Analysis**:
   - **Accidents by Hour**: Countplot of accidents distributed from 0–23 hours.
   - **Accidents by Day of the Week**: Mapped numerical days to weekday names and visualized trends.

3. **Weather Conditions**:
   - Countplot of **Top 7 Weather Conditions** during which most accidents occurred.

4. **Road Surface Conditions**:
   - Countplot of **Top 6 Roadway Surface Conditions** related to accidents.

---

## 📈 Key Visual Insights

- Certain **hours of the day**, particularly during commuting hours, show spikes in accidents.
- **Weekends** tend to have a different accident distribution pattern compared to weekdays.
- Most accidents occurred during specific **weather conditions** like clear, rain, or fog.
- **Dry and wet pavement** were the most common road conditions during accidents.

---

## 🚀 How to Run the Project

1. Clone this repository or download the `.ipynb` notebook.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas
   pip install matplotlib
   pip install seaborn
