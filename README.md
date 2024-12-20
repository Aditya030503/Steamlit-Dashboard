# Indian EV Market Analysis (2001 - 2024)

## Overview
This project provides a comprehensive analysis of the Electric Vehicle (EV) market in India, covering the period from 2001 to 2024. The analysis focuses on:
- Growth trends
- Government policies
- Infrastructure developments
- Key players in the EV industry
- Vehicle class-wise and manufacturer-specific sales data
- Consumer preferences and adoption patterns

The interactive web application built with **Streamlit** allows users to explore and visualize the data in an intuitive way.

---

## Key Features

### **1. Interactive Visualizations**
- **Total EV Sales Over the Years:** Track how EV sales have grown annually.
- **State-Wise EV Companies:** View the concentration of EV manufacturers by state using pie charts.
- **Top EV Manufacturers by Growth and Sales:** Identify key players and their performance trends.
- **Category-Wise Sales:** Analyze which types of EVs are the most popular.

### **2. Real-Time Filtering**
- Filter data by state, year, or specific manufacturers to customize insights.

### **3. Advanced Visualizations**
- 3D surface plots for time-series vehicle data.
- Interactive maps showcasing EV manufacturer locations.

### **4. Metrics Dashboard**
- Key Performance Indicators (KPIs) like total sales, top-performing states, and company counts.

---

## Technology Stack

### **Languages and Frameworks**
- **Python**: Core programming language for data analysis and app development.
- **Streamlit**: Framework for building the interactive web application.
- **Plotly & Altair**: Libraries for dynamic and visually appealing charts.
- **Folium**: Mapping library for geographical visualizations.

### **Data Management**
- **Pandas**: For data manipulation and preprocessing.
- **SQL**: For structured data storage and querying.

### **Additional Tools**
- **Geopandas**: To handle spatial data for maps.
- **Lottie Animations**: For engaging app visuals.
- **Video Embeds**: To showcase demo walkthroughs and insights.

---

## How to Run the Application

### **Prerequisites**
1. Install Python 3.8 or above.
2. Install dependencies using pip:
    ```bash
    pip install streamlit pandas numpy plotly folium geopandas
    ```

### **Steps to Run**
1. Clone the repository:
    ```bash
    git clone <repository_url>
    ```
2. Navigate to the project directory:
    ```bash
    cd indian-ev-market
    ```
3. Launch the Streamlit app:
    ```bash
    streamlit run main_demo.py
    ```
4. Open your web browser to the displayed local URL.

---

## Project Architecture

### **1. Data Collection Layer**
- Raw data is gathered from CSV files and preprocessed for analysis.

### **2. Data Processing Layer**
- Data cleaning and transformation are performed using Pandas.
- Aggregation and calculations for KPIs are carried out in Python.

### **3. Visualization and Front-End Layer**
- Built with Streamlit for dynamic user interaction.
- Visualized with Plotly and Folium for comprehensive insights.

---

## Collaboration and Version Control

- **GitHub**: Used for version control and collaborative development.
- **Branch Workflow**: Feature-specific branches merged after peer review.

---

## Authors
- Akash Vishwakarma
- Aditya
- Siva Maruthi

---

## Interactive Elements

### **1. Lottie Animations**
Engage with animations throughout the app for a better user experience. Example:
![Lottie Animation Example](https://assets10.lottiefiles.com/packages/lf20_x62chJ.json)

### **2. Video Walkthrough**
Watch this video walkthrough to understand how to use the application and explore key features:

[![Indian EV Market Walkthrough](https://img.youtube.com/vi/dQw4w9WgXcQ/0.jpg)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

### **3. Dashboard Overview**
Interactive charts and visuals:

![Dashboard](images/Dashboard_Screenshot.png)

---

## Feedback
We'd love to hear from you! Use the contact form in the app to share your thoughts or suggestions.

---

## Screenshots

### **Interactive Charts**
![Charts](charts_screenshot.png)

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

**Thank you for exploring the Indian EV Market with us! 🚗⚡**
