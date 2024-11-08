🌐 Simple Node.js HTTP Server

This project is a basic HTTP server built with Node.js, designed to serve HTML pages based on URL paths. It includes routing functionality for the Home, About, and Contact pages, as well as error handling for undefined routes. The project was created using the built-in http and fs modules in Node.js.

📌 Features

HTML Page Serving:

Serves different HTML files based on URL paths.

Routing:

Supports routes for:

Home (/)

About (/about)

Contact (/contact)

404 Error Handling:

Responds with a custom 404 error message for undefined routes.

Basic Logging:

Logs incoming requests to the console.

🛠 Technologies

Node.js - 

JavaScript runtime environment

HTTP Module -

Node.js module for creating HTTP servers

File System (FS) Module -

Node.js module for reading HTML files

📒 Usage

Available Routes

/ - Serves the home.html file with a 200 status code.

/about - Serves the about.html file with a 200 status code.

/contact - Serves the contact.html file with a 200 status code.

Undefined Routes - Any other route will return a 404 status code with a "404 - Page Not Found" message.

🌐 Accessing the Server

Home Page: Visit http://127.0.0.1:3000/

About Page: Visit http://127.0.0.1:3000/about

Contact Page: Visit http://127.0.0.1:3000/contact

🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

Built with ❤️ using Node.js. If you find this project helpful, don’t forget to give it a ⭐!
