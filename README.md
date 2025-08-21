Contact List App – MEAN Stack (RESTful API)

A simple **Contact List Application** built with the **MEAN stack (MongoDB, Express, AngularJS, Node.js)**.
This project demonstrates CRUD operations (Create, Read, Update, Delete) using a **RESTful API**.

Features

* Add new contacts with **Name, Email, Number**
* View all saved contacts
* Edit and update contact details
* Delete contacts from the list
* RESTful API integration with **MongoDB backend**
* Responsive UI with **Bootstrap**

Tech Stack

* **Frontend:** AngularJS, Bootstrap, HTML5, CSS3
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (using `mongojs`)
* **Middleware:** Body-Parser

📂 Project Structure

```
contact-list-app/
│
├── public/
│   ├── index.html       # Frontend UI
│   └── controllers/
│       └── controller.js # AngularJS Controller
│
├── server.js            # Express server & REST API
├── package.json         # Dependencies & scripts
└── README.md            # Documentation
```

---

⚙️ Installation & Setup

1. Clone the repository

```bash
git clone https://github.com/your-username/contact-list-app.git
cd contact-list-app
```
2. Install dependencies

```bash
npm install
```

3. Setup MongoDB

Make sure **MongoDB** is installed and running locally.
By default, this project uses a database named `contactlist`.

Start MongoDB service:

```bash
mongod
```

4. Run the server

```bash
npm start
```

Server will start at: **[http://localhost:3000](http://localhost:3000)**

---

API Endpoints

| Method | Endpoint           | Description          |
| ------ | ------------------ | -------------------- |
| GET    | `/contactlist`     | Fetch all contacts   |
| POST   | `/contactlist`     | Add a new contact    |
| GET    | `/contactlist/:id` | Fetch single contact |
| PUT    | `/contactlist/:id` | Update contact by ID |
| DELETE | `/contactlist/:id` | Delete contact by ID |

---

 Screenshots

<img width="1917" height="1020" alt="image" src="https://github.com/user-attachments/assets/0a73e462-86e1-4032-be8a-85f1bbb7d229" />


---


---

Do you want me to also **add MongoDB installation & setup guide** (Windows/Linux) inside the README so others can directly run your project?
