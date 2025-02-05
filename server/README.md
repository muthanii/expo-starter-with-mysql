# MySQL Server Setup for Expo App

This README provides instructions for setting up the server-side of the Expo application, which connects to a MySQL database.

## Prerequisites

- Node.js (version 14 or higher)
- MySQL Server
- npm or yarn

## Getting Started

1. **Clone the Repository**

   ```bash
   git clone <repository-url>
   cd my-expo-app/server
   ```

2. **Install Dependencies**

   Navigate to the server directory and install the required packages:

   ```bash
   npm install
   ```

   or

   ```bash
   yarn install
   ```

3. **Configure Environment Variables**

   Create a `.env` file in the `server` directory and add your MySQL database credentials:

   ```
   DB_HOST=localhost
   DB_USER=your_username
   DB_PASSWORD=your_password
   DB_NAME=your_database_name
   ```

4. **Start the Server**

   To start the server, run:

   ```bash
   npm start
   ```

   or

   ```bash
   yarn start
   ```

   The server should now be running and connected to your MySQL database.

## API Endpoints

- List of available API endpoints will be documented here once the routes are set up.

## Troubleshooting

- Ensure that your MySQL server is running and accessible.
- Check the `.env` file for correct database credentials.

## License

This project is licensed under the MIT License.