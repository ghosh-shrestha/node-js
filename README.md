this repo is all about personal node js documentation.


# REST API – Subscriber Management System

A beginner-friendly REST API built using **Node.js, Express.js, MongoDB and Mongoose** to perform CRUD operations on subscriber data.

## 🚀 Tech Stack

- **Node.js** – JavaScript runtime environment
- **Express.js** – Backend web framework
- **MongoDB** – NoSQL database
- **Mongoose** – MongoDB object modeling
- **REST Client** – API testing through VS Code

## 📂 Project Structure

```text
restapi/
│
├── models/
│   └── subscriber.js
│
├── routes/
│   └── subscribers.js
│
├── .env
├── server.js
├── route.rest
├── package.json
└── README.md
```

## ⚙️ Features

- GET all subscribers
- GET a single subscriber by ID
- POST a new subscriber
- PATCH subscriber details
- DELETE a subscriber
- MongoDB database integration
- Express middleware and route handling

## 🛠️ Installation and Setup

**1. Clone the repository**

```bash
git clone <your-repository-url>
```

**2. Navigate to the project directory**

```bash
cd restapi
```

**3. Install dependencies**

```bash
npm install
```

**4. Configure environment variables**

Create a `.env` file:

```env
DATABASE_URL=mongodb://localhost/subscribers
```

**5. Start the server**

```bash
node server.js
```

Server runs at:

```text
http://localhost:3000
```

## 🔗 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/subscribers` | Fetch all subscribers |
| GET | `/subscribers/:id` | Fetch one subscriber |
| POST | `/subscribers` | Create a subscriber |
| PATCH | `/subscribers/:id` | Update subscriber |
| DELETE | `/subscribers/:id` | Delete subscriber |

## 🧪 API Testing

API requests are tested using the **REST Client extension in VS Code** through the `route.rest` file.

## 📚 Learning Outcomes

- Understanding REST API architecture
- Working with HTTP methods
- Building routes using Express.js
- Understanding middleware
- Creating Mongoose schemas and models
- Performing CRUD operations
- Connecting Node.js applications with MongoDB

## 👩‍💻 Author

**Shrestha Ghosh**

Learning Backend Development | Node.js | Express.js | MongoDB

---

*This project is part of my backend development learning journey.*
