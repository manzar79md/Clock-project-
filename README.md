Clock - Using Pure JS
Overview
This project is a real-time analog clock built using pure HTML, CSS, and JavaScript. It displays the current time with rotating hour, minute, and second hands, and is visually designed to resemble a traditional analog clock. This clock updates every second, and the hands rotate smoothly to reflect the current time.

You can view the live version of the clock by clicking the link below:

Live Clock Project https://manzar79md.github.io/Clock-project-/

Features
Real-time clock: The time updates automatically every second using JavaScript.
Smooth Hand Movements: The hour, minute, and second hands rotate smoothly with CSS transformations.
Responsive Design: The clock is responsive and adjusts its size based on the viewport width (vw).
Personalized Text: The center of the clock displays the text "Md Manzar Nizam".
Technologies Used
HTML: Structure and layout of the clock and content.
CSS: Styling and positioning of the clock elements, including the use of transform for rotating the clock hands.
JavaScript: Logic for updating the clock every second, calculating the positions of the hands, and managing the rotation of the hands.
How It Works
The clock face is displayed using an image (clock.png) set as the background.
Three div elements represent the hour, minute, and second hands, each positioned and rotated based on the current time.
The JavaScript code uses setInterval to get the current time from the system every second and rotate the hands accordingly.
The clock updates every second and rotates the hands smoothly, providing an accurate real-time clock.
Files
index.html: The main HTML file that contains the structure of the clock and links to the CSS and JavaScript files.
index.css: The CSS file that defines the layout, positioning, and animations of the clock's hands.
index.js: The JavaScript file responsible for updating the clock's hands and managing the rotation based on the current time.
clock.png: The background image of the clock face.
Setup and Usage
Clone or download the repository to your local machine.
Open the index.html file in any modern web browser to view the clock.
Alternatively, you can view the live version of the clock here.
Future Improvements
Add themes for the clock to allow customization of its appearance.
Integrate an option to show different timezones or time formats.
Add a digital clock alongside the analog clock.
