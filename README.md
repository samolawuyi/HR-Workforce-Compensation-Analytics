This project demonstrates the use of Tableau to perform complex data joining and visualization for human resources (HR) analytics. The goal was to transform disparate data tables, Demographics, Job Titles, and Salaries into a single, interactive dashboard that provides insights into organizational pay structures and employee distribution. 

Data Engineering & Architecture
​To create a unified view, I performed Data Joins within Tableau’s physical layer:
​Data Source: Three Microsoft Excel tables (Demographics, JobTitle, and Salary).

​Join Logic: Utilized Inner Joins with EmployeeID as the primary linking key across all three tables to ensure data integrity.

​Final Dataset: A consolidated 9-field, 7-row table ready for visualization.

​Key Visualizations & Insights
​Organizational Salary Distribution
​Visualization Type: Ranked Bar Chart.

​Objective: Identify top earners and salary variance across the organization.

​Logic: Aggregated SUM(Employee Salary) by Name of Employee.

​Visual Elements: Applied a continuous color gradient (ranging from \$35,000 to \$70,000) to provide an immediate visual cue for pay scale hierarchy.

​Employee Profiles
​The project successfully maps specific attributes including:

​Demographic Breakdown: Tracking age and gender (e.g., Identifying Jim Halpert, 35, Male).

​Hierarchy Mapping: Linking specific employees to their job titles and corresponding salary tiers.

​Technical Skills Demonstrated
​Tableau Physical Layer Joins: Connecting multiple Excel data sources.

​Data Aggregation: Using SUM and Dimensions to create meaningful metrics.

​Visual Storytelling: Implementing color marks and sorted axes to enhance readability and insight generation.

​Advanced Dashboarding: Bridging the gap between raw data and executive-level HR insights.  

Objective: To provide executive-level insights into departmental pay scales and identify compensation trends

Visualization Strategy: Developed a Sorted Bar Chart to rank employees by total salary.

Applied a Sequential Color Gradient (Deep Blue to Light Blue) to the SUM(Employee Salary) measure to visually distinguish pay brackets.

Key Insights: The dashboard successfully identifies top earners (e.g., Michael Scott, Dwight Schrute) and maps them against their respective job titles to audit pay equity.

Tools Used: Tableau Desktop, Data Joining, Calculated Fields.
