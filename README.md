## **📂 Project Overview**  
This project analyzes employee data from **ABC Company**, focusing on **salary expenditure, age distribution, team-wise analysis, and correlation between factors**. The goal is to extract valuable insights from the dataset using **Pandas, Seaborn, and Matplotlib**.  

---

## **📊 Dataset Information**  
The dataset consists of **458 rows and 9 columns**, covering employee details such as:  
- **name** – Employee Name  
- **team** – Department Name  
- **number** – Employee ID  
- **position** – Job Title  
- **age** – Employee Age  
- **height** – Employee Height (in cm)  
- **weight** – Employee Weight (in kg)  
- **college** – Educational Background  
- **salary** – Annual Salary (in currency units)  

---

## **🔧 Data Preprocessing Steps**  .  
✔ **Filled missing values in `salary`** column using the **median salary** to avoid data loss.  
✔ **Corrected invalid values in `height`** by assigning random values between **150 cm and 180 cm**.  
✔ **Checked for outliers in `salary`** using a **box plot** and analyzed their impact.  

---

## **📈 Key Analysis & Insights**  

### **1️⃣ Salary Expenditure by Team & Position**  
- **Identified the team with the highest salary expenditure**.  
- **Determined which job positions cost the most**.  
- **Visualized salary distribution using bar charts**.  

### **2️⃣ Employee Distribution Analysis**  
- **Counted employees per team** and calculated the percentage split.  
- **Identified the most common job positions**.  

### **3️⃣ Age-Based Analysis**  
- **Determined the predominant age group** among employees.  
- **Found the exact age that appears most frequently** in the dataset.  

### **4️⃣ Correlation Analysis**  
- **Checked correlation between age and salary** (`0.21` weak positive correlation).  
- **Visualized the relationship using a scatter plot with a regression line**.    

---

## **📊 Visualizations Used**  
📌 **Bar Charts** – Salary distribution by team & position.  
📌 **Box Plot** – Outliers in salary.  
📌 **Scatter Plot** – Correlation between age & salary.   

---

## **🚀 How to Run This Project**  
### **Prerequisites**  
Ensure you have **Python 3.x** installed along with the following libraries:  
```bash
pip install pandas numpy matplotlib seaborn
```

### **Steps to Run the Notebook**
1. **Clone this repository**:  
   ```bash
   git clone https://github.com/Jayxkrsh/Entri_MOD4_Project.git
   cd Entri_MOD4_Project
   ```
2. **Run the Python script or Jupyter Notebook**:  
   ```bash
   jupyter notebook analysis.ipynb
   ```
3. **Explore the dataset and visualizations**.  

---

## **📌 Future Enhancements**  
✅ Add **salary prediction models** using Machine Learning.  
✅ Perform **industry benchmarking** for salaries.  
✅ Integrate **interactive dashboards** using **Plotly or Power BI**.  

---

## **📜 License**  
This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it.  

---

### **🔗 Connect with Me**  
📧 Email: jayakrishnanmnair58@gmail.com  
🐙 GitHub: (https://github.com/Jayxkrsh)  
💼 LinkedIn: (www.linkedin.com/in/jayakrishnan-m-nair)  

---
