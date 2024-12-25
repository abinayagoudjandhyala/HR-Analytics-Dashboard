# HR Analytics Dashboard 

## **Overview**
The HR Analytics Dashboard provides a comprehensive overview of workforce metrics, enabling HR teams to analyze key indicators such as employee demographics, attrition trends, performance, and job satisfaction. This dashboard empowers data-driven decision-making by offering insights into critical HR areas.

---

## **Features**

### **Key Metrics**
1. **Total Employees**: Displays the total number of employees across departments.
2. **Attrition Count**: Shows the number of employees who have left the organization.
3. **Attrition Rate**: Percentage of employees who have left relative to the total workforce.
4. **Active Employees**: Number of currently employed individuals.
5. **Average Age**: Displays the average age of the workforce.

### **Visualizations**
1. **Average Monthly Income by Job Role**
   - A line chart illustrating the average monthly salary for each job role.

2. **Active Employees by Education Field**
   - A pie chart representing the distribution of employees across various educational fields such as Life Sciences, Medical, and Marketing.

3. **Active Employees by Age Band and Gender**
   - A clustered bar chart showing active employees categorized by age bands and gender.

4. **Average Performance Rating by Department**
   - A donut chart comparing the average performance ratings across departments (R&D, HR, Sales).

5. **Sum of Attrition by Department and Job Role**
   - A stacked bar chart detailing the attrition count segmented by department and job role.

6. **Active Employees and Attrition Count by Department**
   - A bar chart that compares active employees against attrition count across different departments.

7. **Job Satisfaction Rating by Job Role**
   - A detailed table that includes job roles and their corresponding satisfaction ratings (scale of 1 to 5), with a total score for each role.

### **Interactive Filters (Slicers)**
- **Department**: HR, R&D, Sales.
- **Gender**: Male, Female.

---

## **File Structure**
The project folder is structured as follows:

```
├── Attrition rate icon       # Icon for attrition-related metrics
├── dashboard_preview         # Image preview of the dashboard
├── employe icon              # Icon representing employees
├── HR Analytics.pbix         # Power BI dashboard file
├── HR Data.xlsx              # Source dataset for the dashboard
├── README.md                 # Documentation for the project
```
---

## **Color Scheme**
- **Background**: Purple theme for consistency and branding.
- **Data Colors**:
  - Orange: Highlights key metrics.
  - Blue, Green, Yellow, and Red: Used for various categories and visualizations.
- **Text and Labels**: White for contrast and readability.

---

## **How to Use the Dashboard**
1. **Load Data**:
   - Ensure the dataset is updated with accurate employee details.
   - Refresh the data source in Power BI to reflect the latest metrics.

2. **Interactivity**:
   - Use the slicers to filter data by department, gender, or age band.
   - Hover over charts for detailed tooltips.
   - Drill down into specific categories, such as job roles within departments.

3. **Insights**:
   - Identify departments or roles with high attrition rates.
   - Analyze correlations between performance ratings and attrition.
   - Understand income distribution across job roles.

---

## **Future Enhancements**
1. **Recruitment Pipeline Metrics**:
   - Incorporate visuals for applications, interviews, and offers.
2. **Time-based Trends**:
   - Add line charts to show attrition or satisfaction trends over time.
3. **Engagement Metrics**:
   - Include tenure analysis and employee engagement survey results.

---

## **Prerequisites**
- Power BI Desktop (latest version).
- Dataset with columns including:
  - Employee ID, Department, Job Role, Monthly Income, Age, Gender, Education Field, Attrition, Performance Rating, Job Satisfaction.

---

Dataset Source: https://www.youtube.com/watch?v=vkUXAKqbEjY&t=2274s
