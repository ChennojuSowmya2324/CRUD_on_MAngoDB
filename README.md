This project is a RESTful API built using **Flask** that performs CRUD (Create, Read, Update, Delete) operations on a MongoDB database. The API includes user authentication with hashed passwords and supports operations such as user creation, retrieval, updating, and deletion. The endpoints can be tested using **Postman** or any REST client.

- Create, read, update, and delete user records.
- Password hashing for secure storage.
- Authentication endpoint for login validation.
- MongoDB integration for data storage.
Requirements:
- **Flask**: Backend framework.
- **MongoDB**: NoSQL database for storage.
- **PyMongo**: MongoDB Python driver.
- **Werkzeug**: For password hashing and validation.
- **Flask-CORS**: To handle Cross-Origin Resource Sharing (CORS).

 Prerequisites
- Python 3.8+
- MongoDB instance (local or cloud).

Procedure:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flask-mongodb-crud.git
   cd flask-mongodb-crud
