# Vishnu Results Application

Welcome to the **Vishnu Results Application** repository! This application simplifies the process of managing and analyzing student results in a department. Using **Pandas**, the application extracts data from Excel files and calculates CGPA for students based on their grades. It also pivots the table to provide a more accessible format, making tracking individual and department-wide results easier.

## Features

- **Department-Wise Results**:
  - Extract and organize student results by department.
  - View individual student results and the department’s overall performance.

- **CGPA Calculation**:
  - Automatically calculate CGPA based on individual subject grades.
  - Supports multiple subjects and grades per student.

- **Data Pivoting**:
  - The application pivots the student records, allowing easy access to each student's subject-wise results.
  
- **Class-Wide Results**:
  - Given a starting and ending roll number, the app can display results for the entire class.

- **Preprocessing**:
  - To use this tool, first, convert the PDF results into an Excel file for easier data processing.

## Getting Started

### Prerequisites

Before running the application, ensure you have the following installed:
- Python 3.x
- Pandas
- Openpyxl (for reading Excel files)

### Steps to Run
> #### click on <mark> Open in colab </mark>
  > - click open in colab button in results.ipynb 
> #### Convert the PDF result file into Excel format (if the original data is in PDF).
 > - Preprocessing step: Use tools like Adobe Acrobat or any other PDF-to-Excel converter.
 > - Place the Excel file containing the results in the same directory as the application.


### Example Usage
- Once the Excel file is processed, you will be able to:
  - See each subject's marks for a given student.
  - View the results for the entire department.
  - Calculate the CGPA for each student.
## Collaborations
If you are interested in improving the project, we encourage collaborations! Specifically, we are open to integrating OCR (Optical Character Recognition) to directly convert PDF files into Excel format, removing the need for manual conversion. If you are experienced with OCR and want to contribute, please feel free to fork the repository and create a pull request!

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
Special thanks to Pandas for its powerful data manipulation tools.
A big shoutout to anyone contributing to enhancing the project through collaboration and improving its capabilities.

Feel free to add any specific instructions or modify sections as needed for your project!








