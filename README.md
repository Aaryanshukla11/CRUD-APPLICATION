CRUD Application 

A full-stack CRUD (Create, Read, Update, Delete) application that allows users to manage and manipulate data through a clean and interactive user interface. This project demonstrates essential web development skills using Node.js, Express, MongoDB, and EJS (or your chosen templating engine).

 Project Description

The CRUD Application is a full-stack web project that enables users to perform all four fundamental database operations: creating, reading, updating, and deleting records. Built using Node.js and Express, the backend connects with MongoDB to persist data, while the frontend uses server-rendered views and modern UI interactions to display and manage content effectively.

This project showcases the core principles of RESTful API design, database integration, routing, and dynamic view rendering. It serves as an excellent foundation for understanding how web apps interact with databases in real time and is ideal for demonstrations, portfolio showcases, or as a starting point for more advanced applications.

 Features

> Create new records
> Read and list all records
> Update existing records
> Delete records
> Responsive and user-friendly UI
> Clean, structured codebase

 Project Structure
CRUD-APPLICATION/
├── models/                 # Database schemas
├── routes/                 # API / Web routes
├── views/                  # EJS templates or frontend pages
├── public/                 # CSS/JS assets
├── app.js                  # Main server file
├── package.json
└── README.md

 Tech Stack
Layer	Technology
Backend	Node.js, Express
Database	MongoDB
Frontend	HTML, CSS, EJS (or any templating)
ORM	Mongoose
 Live Demo

 Installation

Clone the repository

git clone https://github.com/Aaryanshukla11/CRUD-APPLICATION.git
cd CRUD-APPLICATION


Install dependencies

npm install


Set up environment variables

Create a .env file:

PORT=5000
MONGODB_URI=your_mongo_connection_string


Start the server

npm start


Visit

http://localhost:5000

 How It Works

🔹 Create — Users add new records through a form.
🔹 Read — Saved records are listed and displayed dynamically.
🔹 Update — Records can be edited and saved back to the database.
🔹 Delete — Records can be removed with one click.

 Routes
Method	Route	Description
GET	/	Home/list view
GET	/create	Show form
POST	/create	Save new item
GET	/edit/:id	Edit item
POST/PUT	/edit/:id	Update item
GET/DELETE	/delete/:id	Remove item
 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

 License

Distributed under the MIT License. See LICENSE for details.

 Credits

Built with ❤️ using Node.js, Express, and MongoDB.

🔹 One-Line Description (for GitHub)

A full-stack CRUD application built with Node.js, Express, and MongoDB for managing database records with create, read, update, and delete operations.
