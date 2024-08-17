# HR_Analytics_Mini_Project

## Project Overview

This mini-project involves analyzing HR data to identify factors that influence employee attrition. The analysis is performed using Python, with a focus on data cleaning, exploration, and visualization. The dataset is sourced from Kaggle and includes various attributes related to employee demographics, job satisfaction, and other factors.

## Dataset

- **Source**: [Kaggle HR Analytics Dataset](https://www.kaggle.com/datasets)
- **Description**: The dataset contains information on employees, including attributes such as working hours, business travel, employee count, gender, department, age group, salary, and job satisfaction.

## Project Structure

- `HR_Analytics_Analysis.ipynb`: Jupyter Notebook with code for data analysis, cleaning, and visualization.
- `data/`: Directory containing the dataset file (`hr_analytics.csv`).

## Libraries Used

- **NumPy**: For numerical operations.
- **pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.

## Steps Performed

1. **Data Loading**:
   - The dataset is loaded into a Google Colab notebook.

2. **Data Cleaning**:
   - Removal of unnecessary columns.
   - Handling of object data types.
   - Addressing missing values.

3. **Data Analysis**:
   - Exploration of factors such as working hours, business travel, gender, department, age group, salary, and job satisfaction.
   - Analysis of their impact on employee attrition.

4. **Data Visualization**:
   - Generation of graphs and charts to visualize trends and relationships within the data.

5. **Conclusions**:
   - Drawing insights based on the data analysis and visualizations.

## Findings and Conclusions

- **Initial Data Inspection**:
  - The dataset contains 35 columns: 26 of type `int64` and 9 of type `object`. All columns have non-null values with a total of 1,470 entries per column.

- **Attrition Analysis**:
  - A graph plotted between attrition and count shows approximately 250 employees wanted to leave the company, while 1,100-1,200 employees did not want to leave.

- **Business Travel**:
  - Employees who travel rarely or frequently are more likely to leave their jobs. The lowest attrition was observed among those with minimal business travel, while the highest attrition was among those who traveled rarely.

- **Department**:
  - Analysis of departments (Sales, R&D, HR) revealed that R&D had the highest attrition, followed by Sales, with HR having the lowest attrition.

- **Education Field**:
  - Attrition was highest in the Life Sciences field, followed by Medical, Marketing, Technical Degree, and Other fields, with HR showing the lowest attrition.

- **Gender**:
  - Male employees exhibited higher attrition compared to female employees, indicating that men tend to leave the company more frequently than women.

- **Overtime**:
  - Overtime and increased working hours are associated with higher attrition. Employees working overtime show a higher rate of attrition, although fewer employees are working overtime.

- **Job Role**:
  - Analysis of various job roles (Sales Executive, Research Scientist, Lab Technician, MD, Healthcare Representative, Manager, Sales Representative, Research Director, HR) revealed that Sales Executives, Sales Representatives, and Lab Technicians have higher attrition rates, while Research Directors have the lowest.

- **Age Factor**:
  - Employees in the 25-35 age group have a higher likelihood of attrition.

- **Data Preprocessing**:
  - Object data types were converted to integer types. Categorical data handling was performed for parameters such as Business Travel, Education Field, Gender, and Department. Unnecessary columns were removed as part of data cleaning.

- **Visualization**:
  - Continuous data was visualized using effective methods, including combined visualizations rather than individual plots for each parameter with respect to attrition count.

## How to Run the Code

1. Clone this repository:
   ```git clone https://github.com/Shalmali-p/HR_Analytics_Mini_Project.git```
2. Navigate to the project directory:
  ```cd HR_Analytics_Mini_Project```
3. Open the Jupyter Notebook (HR_Analytics_Analysis.ipynb) in Google Colab or Jupyter Notebook environment.
4. Install necessary libraries if they are not already installed:
   ```pip install numpy pandas matplotlib```
5. Follow the steps in the notebook to execute the code and perform the analysis.

## License
This project is licensed under the Apache 2.0 License. See the LICENSE file for more details.
