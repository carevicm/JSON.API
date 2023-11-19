# JSON.API

Project Description: Taco Town 🌮 - A Dynamic Recipe Web Application


Project Overview:

Taco Town is an interactive web application designed to provide users with delicious taco recipes. 
The application features a simple and engaging interface where users can select their preferred taco ingredient (chicken, beef, or fish) and instantly view a customized recipe. 
This project is an excellent example of how modern web technologies can be combined to create a user-friendly and dynamic web experience.


Technologies Used:

HTML & CSS: The frontend of the application is built using HTML5 and CSS3. HTML structures the content, while CSS is used for styling. The application features a responsive design with a focus on usability and aesthetics. The CSS includes custom styles for buttons, text, and layout, along with a unique background pattern created using SVG.

JavaScript (Client-Side): Although not explicitly shown in the provided code, JavaScript may be used for handling user interactions in the browser, such as responding to button clicks.

Node.js & Express.js: The backend of the application is powered by Node.js, with Express.js as the web application framework. Express.js simplifies the server-side logic, handling HTTP requests and responses with ease.

EJS (Embedded JavaScript Templating): EJS is used as a templating engine to dynamically generate HTML pages based on the server-side data. It allows the insertion of JavaScript code into HTML, enabling dynamic content rendering.

Body-Parser: This middleware is used in the Express.js application for parsing incoming request bodies. It's essential for handling POST requests, as it allows access to req.body.

JSON: The recipes are stored in a JSON format, which is a lightweight data interchange format. This makes it easy to store and retrieve recipe data, including details like ingredients, preparation methods, and prices.


Application Logic:

The server listens on port 3000 and serves the static files (HTML, CSS) and the EJS templates.

The main page (index.ejs) displays buttons for different taco types. When a user clicks a button, a POST request is sent to the server with the selected taco type.

The server handles the POST request in the /recipe route. It parses the user's choice, fetches the corresponding recipe from the JSON data, and stores it in a variable.

The user is then redirected to the homepage, where the EJS template renders the selected recipe dynamically, displaying ingredients and preparation details.

The CSS styles provide a visually appealing layout, with attention to typography, color scheme, and responsive design.
