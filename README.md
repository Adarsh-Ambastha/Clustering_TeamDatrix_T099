# Clustering_TeamDatrix_T099

# **Household Power Consumption Clustering**

### **Description**
This project explores and analyzes household power consumption data using clustering techniques. It applies various machine learning algorithms, including K-Means, K mini batch, and Gaussian Mixtures, to uncover meaningful patterns and insights. The project also includes comprehensive Exploratory Data Analysis (EDA) to understand data distribution, trends, and correlations.

---

### **Table of Contents**
- [Project Description](#description)
- [Dataset Information](#dataset-information)
- [Technologies Used](#technologies-used)
- [Key Features](#key-features)
- [Setup and Installation](#setup-and-installation)
- [Project Workflow](#project-workflow)
- [Results and Visualizations](#results-and-visualizations)
- [Contributors](#contributors)
- [License](#license)

---

### **Dataset Information**
The dataset contains electric power consumption measurements from a single household recorded at one-minute intervals over nearly four years. The key features include:
- `Date` and `Time`: Timestamp of the measurement.
- `Global_active_power`: Household global minute-averaged active power (kilowatts).
- `Global_reactive_power`: Household global minute-averaged reactive power (kilowatts).
- `Voltage`: Minute-averaged voltage (volts).
- `Global_intensity`: Household global minute-averaged current intensity (amperes).
- `Sub_metering_1`: Energy consumed in the kitchen (watt-hours).
- `Sub_metering_2`: Energy consumed in the laundry room (watt-hours).
- `Sub_metering_3`: Energy consumed by the water heater and air-conditioner (watt-hours).

---

### **Technologies Used**
- **Python**: Programming language.
- **Libraries**:
  - Data Processing: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
- **Version Control**: Git, GitHub

---

### **Key Features**
1. **Exploratory Data Analysis (EDA)**:
   - Time-series plots of power consumption.
   - Distribution analysis and correlation heatmaps.
   - Sub-metering trends over time.

2. **Clustering**:
   - **K-Means Clustering**
   - **Mini-Batch K-Means Clustering**
   - **Gaussian Mixture Models (GMM)**
   - **Hierarchical Clustering**

3. **Evaluation Metrics**:
   - Silhouette Score
   - Davies-Bouldin Index

4. **Interactive Visualizations**:
   - PCA-based scatter plots for cluster representation.

---

### **Setup and Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/household-power-clustering.git
   cd household-power-clustering
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the scripts:
   - **EDA**:
     ```bash
     python eda.py
     ```
   - **Clustering**:
     ```bash
     python clustering.py
     ```

---

### **Project Workflow**
1. **Data Preprocessing**:
   - Handle missing values.
   - Combine `Date` and `Time` into a single `Datetime` column.
   - Normalize numerical features for clustering.

2. **EDA**:
   - Visualize trends and correlations in the data.

3. **Clustering**:
   - Apply various clustering techniques.
   - Tune hyperparameters and evaluate performance.

4. **Insights**:
   - Analyze and interpret clusters to provide actionable insights.

---

### **Results and Visualizations**
#### **Key Findings**:
- Identified distinct consumption patterns based on voltage, intensity, and sub-metering values.
- Highlighted periods of high energy usage for specific devices.

#### **Visualizations**:
1. Time-series plots of power consumption.
2. Contour plots for Gaussian Mixtures.
3. PCA-based cluster representations.
4. Heatmaps showing feature correlations.

---

### **Contributors**
- Aman Rajput - 202418003
- Adarsh Ambastha - 202418004
- Yashraj Singh - 202418064
- Pragnya Dandavate - 202418065

---

### **Acknowledgments**
- **Dataset Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption)
- Tools and technologies used in the project.
