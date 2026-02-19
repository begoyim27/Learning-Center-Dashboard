# Learning-Center-Dashboard
A comprehensive Power BI solution for tracking course performance, student demographics, and financial metrics. Built using Power Query for ETL and advanced DAX for insights.

Project Overview
This Power BI dashboard provides a detailed analysis of a Learning Center's operations. It transforms raw student and course data into actionable insights regarding revenue, student enrollment trends, and course efficiency.

Tools & Technologies Used
* **Power BI Desktop**: For data visualization and dashboard design.
* **Power Query (M Language)**: For Data Cleaning, Transformation, and ETL processes.
* **DAX (Data Analysis Expressions)**: For calculating average fees, time-remaining metrics, and complex aggregations.

Key Features & Visuals
1.  **Average Course Fee Analysis**: A matrix showing fee trends across years (2023-2025) and by course type.
2.  **Course Fee by Gender**: A clustered column chart comparing financial contributions between male and female students.
3.  **Registration Trends**: An area chart visualizing student sign-ups month-by-month to identify peak seasons.
4.  **Course Progress Tracking**: 
    * Pie chart for percentage-based "Days Left" distribution.
    * Bar chart for precise countdown to course completion.
5.  **Demographic Insights**: Breakdown by City, Branch, and Age (based on the underlying dataset).

Dataset Description
The source data includes:
* `Student_ID`, `Student_Name`, `Gender`, `Age`
* `Branch` & `City` information
* `Course` details with `Registration_Date` and `Course_End_Date`
* `Course_Fee` and `Kurs_davomiyligi` (Course Duration)

How to view the report
1. Download the `.pbix` file from this repository.
2. Open it using **Power BI Desktop**.
3. (Optional) If the data source path is broken, point it to the included CSV/Excel file in the `data/` folder.
