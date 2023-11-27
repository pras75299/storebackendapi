# StoreAPI Backend

This repository contains the backend code for a StoreAPI. It's built using the MEN stack (MongoDB, Express.js, Node.js).

## Features

- RESTful API endpoints to manage tasks.
- Integration with MongoDB for data persistence.
- Robust error handling and data validation.

## Getting Started

### Prerequisites

- Node.js
- MongoDB
- ExpressJS

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/pras75299/storebackendapi.git
   ```
2. Install dependencies:
   ```
   cd storebackendapi
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```
     DB_URI=<your_mongodb_uri>
     ```

### Running the Application

1. Start the server:
   ```
   npm start
   ```
   The server will run on `http://localhost:3000`.

## API Documentation

- **/api/tasks**: GET (list all tasks), POST (create a new task)
- **/api/tasks/:id**: GET (retrieve a task), PUT (update a task), DELETE (delete a task)

## Contributing

Contributions are welcome. Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
