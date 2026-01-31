🔢 Decimal to Binary Converter (Call Stack Visualizer)

A visual Decimal to Binary Converter built with HTML, CSS, and JavaScript that not only converts numbers to binary, but also animates how recursion and the JavaScript call stack work internally.

This project turns a normally invisible process into an interactive learning experience.

🚀 Live Demo

👉 [live page](https://rustom-yadav.github.io/decimal-to-binary-converter/)

📂 GitHub Repository

👉 [github repository](https://github.com/Rustom-yadav/decimal-to-binary-converter)

✨ Features

🔢 Convert any decimal number to binary

🧠 Recursive conversion using JavaScript

📊 Animated call stack for the number 5

⏱ Step-by-step function execution display

🧩 Real-time UI updates

📱 Responsive layout

🛠 Technologies Used

HTML5

CSS3

JavaScript (ES6)

No libraries. No frameworks. Pure logic + visuals.

🧠 How It Works

The conversion uses a recursive function:

decimalToBinary(n) = decimalToBinary(Math.floor(n / 2)) + (n % 2)


When the input is 5, the app displays a live call stack animation showing:

Function calls being pushed

Base case being reached

Values returning back up the stack

This allows users to see exactly how recursion builds the final binary result.

📦 How to Run Locally

Clone the repository

git clone https://github.com/Rustom-yadav/decimal-to-binary-converter.git


Open the project

cd decimal-to-binary-visualizer


Open index.html in your browser

🎯 What This Project Demonstrates

Recursive algorithms

Call stack behavior

DOM manipulation

Asynchronous timing using setTimeout

Data-driven UI animation

Input validation

🚀 Future Enhancements

Support animation for any number

Speed control slider

Step-by-step manual mode

History of conversions

Dark / light mode

👨‍💻 Author

Rustom
JavaScript Developer
Building tools that make invisible code visible.
