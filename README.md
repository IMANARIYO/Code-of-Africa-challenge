Interactive Photo Gallery
Overview
This project is an interactive photo gallery built as part of the COA Taskforce take-home challenge. The gallery is designed to be responsive, accurately match the provided Figma designs, and include various interactive features. Additionally, two JavaScript coding challenges are solved and included in the repository.

Table of Contents

     1.Features
     2.Technologies Used
     4.Setup Instructions
     5.Project Structure
     6.Coding Challenges
         Array Manipulation
         String Transformation
     7.Contact
1.Features
Responsive Design:

 Adapts seamlessly to different screen sizes and devices.

Figma Design Accuracy:
 Matches the provided Figma designs pixel-perfectly.

Hover Interaction: 

Displays additional details when a user hovers over a photo.

Cross-browser Compatibility:

 Ensures consistent performance across modern web browsers (Chrome, Firefox, Safari, Edge).
Image Thumbnail Navigation:

 Allows users to navigate through images using thumbnails.
Full-size Image Viewing:

 Enables users to view images in full size.
2.Technologies Used
   .HTML5
   .CSS3
   .JavaScript
   .Git & GitHub
Setup Instructions
Follow these steps to set up and run the project on your local machine:

Clone the Repository:

git clone https://github.com/IMANARIYO/Code-of-Africa-challenge.
cd Code-of-Africa-challenge
Open the Project:
Open index.html in your preferred web browser to view the interactive photo gallery.

Development:
Use your preferred code editor or IDE to make any changes or improvements.

Project Structure

Code-of-Africa-challenge/
│
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── script.js
│   └── images/
│       └── (your image files)
│
├── challenges/
│   ├── arrayMap.js
│   └── stringTransform.js
│
├── index.html
├── README.md
└── .gitignore
assets/css/styles.css: Contains all the CSS styles for the project.

assets/js/script.js: Contains the JavaScript code for interactivity.

assets/images/: Folder for storing image files.
challenges/: Folder containing solutions to the coding challenges.
arrayMap.js: Solution to the array manipulation challenge.
stringTransform.js: Solution to the string transformation challenge.
index.html: The main HTML file for the interactive photo gallery.
README.md: This README file.
.gitignore: Specifies files to be ignored by Git.
Coding Challenges
Array Manipulation
Problem Statement:
Given an array of integers and a target sum, determine if there exists a contiguous subarray within the array that sums up to the target. Return true if such a subarray exists, otherwise return false.

Example:

javascript
Copy code
Input: arr = [4, 2, 7, 1, 9, 5], target = 14
Output: true
Explanation: The subarray [7, 1, 9] sums up to 14, which is equal to the target.
Solution:
The solution is implemented in challenges/arrayMap.js.

String Transformation
Problem Statement:
Given a string, transform it based on the following rules:

If the length of the string is divisible by 3, reverse the entire string.
If the length of the string is divisible by 5, replace each character with its ASCII code.
If the length of the string is divisible by both 3 and 5, perform both operations in the specified order.
Example:

javascript
Copy code
Input: "Hello World"
Output: "87 111 114 108 100 32 111 108 108 101 72"
Explanation: The length of the string is 11, which is divisible by both 3 and 5. First, the string is reversed, becoming "dlroW olleH". Then, each character is replaced by its ASCII code, resulting in "87 111 114 108 100 32 111 108 108 101 72".
Solution:
The solution is implemented in challenges/stringTransform.js.

Contact
For any questions or further clarification, please reach out to:

Email: clet@codeofafrica.com
Phone: +250 789 823 888
Best of luck with your project!

