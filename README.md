# 📋 Personal Task Manager API

A simple Node.js API for managing personal tasks, including CRUD operations, image uploads, and JSON-based data storage.

## 🌟 Features
- **CRUD Operations**: Create, Read, Update, and Delete tasks.
- **Image Upload**: Attach images to tasks with automatic file handling.
- **File-Based Storage**: Stores tasks in a JSON file to simulate persistent storage.
- **Modular Structure**: Organized code with separate controllers, routes, and utilities.

---

## 📂 Project Structure

```plaintext
personal-task-manager-api/
├── controllers/           # Task logic and image upload handling
│   └── taskController.js
├── data/                  # JSON file storage for tasks
│   └── tasks.json
├── uploads/               # Folder for uploaded task images
├── routes/                # API route definitions
│   └── taskRoutes.js
├── utils/                 # Helper utilities for file handling
│   └── fileHandler.js
├── views/                 # Basic HTML interface for testing
│   └── index.html
├── app.js                 # Main server setup and configuration
├── package.json           # Project metadata and dependencies
└── README.md              # Project documentation
```
# 🚀 Getting Started

## Prerequisites:

#### Node.js (v14+ recommended)

#### NPM (usually comes with Node.js)


# Installation

## 1. Clone the Repository
```
git clone https://github.com/MasterWithAhmad/task-manager-api.git
```
```
cd task-manager-api
```

## 2. Install Dependencies
```
npm install
```

## 3. Create Initial Data File

Ensure data/tasks.json exists with an empty array:
```
[]
```

## 4. Run the Application
```
node app.js
```
The server should start on 
```
http://localhost:3000.
```



---

# 🛠️ Usage

Access the HTML Interface: Open http://localhost:3000 in a browser to use the testing interface.

# API Endpoints:



---

## 📄 Example API Requests

### 1. Create a Task
```
curl -X POST -F "title=My Task" -F "description=Task details" -F "status=pending" -F "image=@path/to/image.jpg" http://localhost:3000/tasks
```
### 2. Get All Tasks
```
curl -X GET http://localhost:3000/tasks
```
### 3. Update a Task
```
curl -X PUT -F "title=Updated Task Title" -F "status=completed" -F "image=@path/to/new-image.jpg" http://localhost:3000/tasks/1
```
### 4. Delete a Task
```
curl -X DELETE http://localhost:3000/tasks/1
```

---

# 🤝 Contributing

Contributions are welcome! Follow these steps to contribute:

## 1. Fork the Repository:

Click on the "Fork" button at the top of this repository page to create your own copy.



## 2. Clone the Forked Repository:

Clone your forked repository to your local machine:
```
git clone https://github.com/MasterWithAhmad/task-manager-api.git
```
```
cd task-manager-api
```


## 3. Create a New Branch:

Make a new branch for your feature or bugfix:
```
git checkout -b feature-name
```


## 4. Make Changes and Commit:

Make your changes, then commit them:
```
git add .
```
```
git commit -m "Add a new feature"
```


## 5. Push to Your Fork:

Push the changes to your forked repository:
```
git push origin feature-name
```


## 6. Submit a Pull Request:

Open a pull request to merge your changes into the main repository.

Include a description of your changes and any relevant issue numbers.





---

# 📜 License

This project is open-source and available under the MIT License.


---

# 👤 Author

Ahmed Ibrahim Ahmed

Feel free to reach out if you have questions or suggestions! 😊
