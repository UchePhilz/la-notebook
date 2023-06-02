# La Notebook (the notebook)
This is a simple backend application written in Kotlin that provides an API for managing a collection of notes or a notebook.
It allows users to create, read, update, and delete notes through HTTP requests,
providing basic CRUD (Create, Read, Update, Delete) functionality.

### Features

**RESTful API:**<br>
The backend app follows REST architectural principles, providing a set of endpoints to interact with the notebook.
It supports HTTP methods such as GET, POST, PUT, and DELETE for retrieving, creating, updating, and deleting notes respectively.

**Persistent storage:**<br>
The app utilizes a persistent storage mechanism, such as a database or a file system, to store the notes.
This ensures that the data is preserved even when the application is restarted.

**Authentication and authorization (optional):**<br>
Depending on the requirements, the app can include authentication and authorization mechanisms to secure the API endpoints, ensuring that only authorized users can access and modify the notes.

**Validation and error handling:<br**>
The app performs input validation to ensure that the data sent to the API is in the correct format.
It also includes proper error handling to provide informative error messages in case of any issues during the API calls.
