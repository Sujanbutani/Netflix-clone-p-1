# Netflix Clone

This project is a backend application built using **Node.js**, **Express**, and **MongoDB**. It supports basic Netflix clone functionalities with user authentication using **JWT**.

## Getting Started

### Prerequisites

- **Node.js** installed (v12 or higher)
- **MongoDB** installed or use a MongoDB Atlas cloud instance

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sujanbutani/Netflix-clone-p-1.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the project root and add the following environment variables:
   ```
   MONGODB_URL=<Your MongoDB connection string>
   PORT=5000
   SECRET_key=<Your JWT secret key>
   ```

4. Start the development server:
   ```bash
   npm start
   ```

   The server will start at `http://localhost:5000`.
