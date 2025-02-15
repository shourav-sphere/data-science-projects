# Student Performance Analysis

This project focuses on performing data analysis on student performance data to explore trends and patterns related to test scores, attendance, and overall performance.

## Project Overview
The project involves data merging, feature engineering, clustering, and visualization to better understand student performance.

## Dataset
The project uses the following datasets:
- **term-test-1-result.csv**: Term Test 1 results.
- **term-test-2-result.csv**: Term Test 2 results.
- **attendance-term-final-result.csv**: Attendance and final term marks.

Each dataset contains:
- **Registration Number**: Unique student identifier.
- **Name**: Student's name.
- **Marks**: Test scores.
- **Attendance Marks**: Marks assigned based on attendance.

## Project Steps
1. **Data Loading**: Reading multiple datasets into Pandas dataframes.
2. **Data Merging**: Combining test result datasets and attendance/final result dataset.
3. **Feature Engineering**: Calculating best and average test marks.
4. **Final Marks Calculation**: Applying weighted formula to compute final marks.
5. **Clustering**: Using K-Means clustering to group students by performance.
6. **Visualization**: Plotting clustered student performance.

## Tools & Libraries
- Python (Pandas, Matplotlib, Scikit-Learn)
- Jupyter Notebook

## Key Insights
- **Performance Patterns**: Identified clusters of students based on performance.
- **Influential Factors**: Attendance, test scores, and term finals significantly impact final marks.

## Instructions to Run the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/shourav-sphere/data-science-projects.git
    ```
2. Navigate to the project directory:
    ```bash
    cd student-performance-analysis
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the analysis script or open the notebook:
    ```bash
    jupyter notebook student-performance-analysis.ipynb
    ```

## Contributing
Contributions are welcome! Please submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Data source: Internal academic records.
- Python community for providing amazing resources.
