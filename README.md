# SQLClass - User Management App

A simple backend-based user management application built using Node.js, Express.js, MySQL, and EJS.

This project was created to practice backend fundamentals like routing, CRUD operations, database connectivity, middleware usage, and server-side rendering.

---

#  Features

* View all users
* Edit usernames
* MySQL database integration
* Dynamic routing
* Server-side rendering with EJS
* Express middleware usage
* Method Override for PATCH requests

---

#  Tech Stack

* Node.js
* Express.js
* MySQL
* EJS
* Faker.js
* Method-Override

---

#  Project Structure

```bash
Sqlclass/
│
├── views/
├── node_modules/
├── app.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

---

#  Installation

Clone the repository:

```bash
git clone https://github.com/Ankitbisht818/Sqlclass.git
```

Move into the project folder:

```bash
cd Sqlclass
```

Install dependencies:

```bash
npm install
```

---

# Run the Project

Start the server:

```bash
node app.js
```

Server will run on:

```bash
http://localhost:8080
```

---

# Database Setup

Create a MySQL database named:

```sql
CREATE DATABASE delta_app;
```

Create a table named `user` with required fields.

Update your MySQL credentials inside `app.js` before running the project.

---

#  What I Learned

While building this project, I learned:

* How Express routing works
* CRUD operations with MySQL
* Using middleware in Express
* Handling forms with EJS
* Connecting backend with databases
* Dynamic route handling
* Basic backend project structure

---

#  Future Improvements

Planned improvements for this project:

* Add authentication
* Use bcrypt for password hashing
* Convert project into MVC structure
* Add form validation
* Improve UI styling
* Deploy the application online

---

#  Contribution

This is a learning project, but suggestions and improvements are always welcome.

---

#  Author

Ankit Bisht
