# DATA VISUALIZATION

### **Objective**
- The objective of this project is to analyze and visualize the distribution of a categorical or continuous variable.

---

### **Technologies Used**
- **Programming Language:** Python  
- **Libraries:** `pandas`, `matplotlib`  
- **Platform:** Jupyter Notebook

---

### **Methodology**

#### **Data Import & Cleaning**
- Read the dataset using `pandas.read_csv()` with `skiprows=4` to skip metadata rows.
- Dropped irrelevant columns: `Indicator Name`, `Indicator Code`.

#### **User Interaction**
- **For country-specific population trend:**  
  - User inputs a country name.
- **For growth distribution:**  
  - User inputs a starting year and an ending year.

#### **Visualization**

- **Bar Chart:**
  - **X-axis:** Years (1960 to most recent year)
  - **Y-axis:** Population (in millions)
  - Shows a country's population trend over time.

- **Histogram:**
  - **X-axis:** Population Growth Rate (%) across countries
  - **Y-axis:** Number of countries
  - Shows how countries differ in population growth between two selected years.

---

### **Insights**
- Countries exhibit wide variation in population growth rates.
- **Bar charts** provide an in-depth view of a **single country’s** demographic change.
- **Histograms** highlight **global patterns**:
  - High-growth developing nations
  - Countries with stagnant or declining populations

---

### **Conclusion**
- This project offers a powerful yet simple way to visualize both long-term population trends for individual countries and the global distribution of growth.
