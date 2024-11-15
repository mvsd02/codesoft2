Student Grade Calculator
Description
The Student Grade Calculator is a simple web application that allows users to enter marks for four subjects (Physics, Maths, Chemistry, and Biology) and calculate the total marks, percentage, and grade. The app uses JavaScript for the calculations and Bootstrap for styling. It also provides a clean, user-friendly interface.

The user inputs the marks for each subject, and when they click on the "Show Percentage" button, the total marks, percentage, and grade are displayed.

Features:
Input marks for Physics, Maths, Chemistry, and Biology.
Calculate total marks and percentage.
Display grade based on the percentage.
Simple, responsive design using Bootstrap.
Validations to ensure input marks are numeric.
Table of Contents
Technologies Used
Installation Instructions
Usage
How It Works
Contributing
License
Technologies Used
HTML5: For structuring the webpage.
CSS3: For styling the webpage (using Bootstrap framework for responsiveness).
JavaScript: For handling the logic of grade calculation and dynamic display of results.
Bootstrap: For styling and making the application responsive.
Google Fonts: Used for the Poppins font to enhance the look of the text.
Installation Instructions
Clone the Repository: First, clone the repository to your local machine using Git.

bash
Copy code
git clone https://github.com/your-username/student-grade-calculator.git
cd student-grade-calculator
Open the Project: Open the index.html file in a web browser to view and interact with the application.

Usage
Open the index.html file in your browser.
Input marks for the following subjects:
Physics
Maths
Chemistry
Biology
Click the "Show Percentage" button to calculate the total marks, percentage, and grade.
The results will be displayed on the page showing:
Total Marks
Percentage
Grade
How It Works
Frontend:
HTML Structure: The page includes input fields for each of the subjects (Physics, Maths, Chemistry, and Biology). It also includes a button to trigger the calculation and display results.

CSS and Styling: Bootstrap is used for creating a responsive and mobile-friendly layout. The page layout is designed using a simple screen-body layout with clean styling.

JavaScript Logic:

When the user enters marks for the subjects, the results() function is triggered by the button click.
The function:
Fetches the values from the input fields.
Validates if the inputs are valid numbers.
Calculates the total marks and percentage.
Assigns a grade based on the percentage.
Displays the results on the screen.
Grading System:
A+: 90% and above
A: 80% to 89%
B: 70% to 79%
C: 60% to 69%
D: 50% to 59%
F: Below 50%
Contributing
If you'd like to contribute to this project, follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit (git commit -am 'Add new feature').
Push to your branch (git push origin feature/your-feature).
Open a pull request.
License
This project is open-source and available under the MIT License.
