# Socket Backend

This is a simple Node.js backend project using Socket.io, Express, and MongoDB.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Scripts](#scripts)
- [Dependencies](#dependencies)
- [Dev Dependencies](#dev-dependencies)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/faisalamin001/socket-backend.git
   ```

2. Change to the project directory:

   ```sh
   cd socket-backend
   ```

3. Install the dependencies:

   ```sh
   npm install
   ```

4. Create a `.env` file in the root of your project and add your environment variables:

   ```sh
   touch .env
   ```

   Example `.env` file:

   ```env
   MONGODB_URI=your_mongo_uri
   DB_NAME=Your_db_name
   PORT=3000
   ```

## Usage

1. Start the server in development mode:

   ```sh
   npm run dev
   ```

2. Start the server in production mode:
   ```sh
   npm start
   ```

The server will start on the port specified in your `.env` file (default is `3000`).

## Scripts

- `start`: Starts the application using Node.js.
- `dev`: Starts the application using nodemon for development.
- `test`: Runs the tests using Jest.

## Dependencies

- **bcrypt**: ^5.1.0
- **body-parser**: ^1.20.2
- **cors**: ^2.8.5
- **dotenv**: ^16.0.3
- **express**: ^4.18.2
- **mongodb**: ^5.5.0
- **nodemailer**: ^6.9.4
- **nodemon**: ^2.0.22
- **randomstring**: ^1.3.0
- **socket.io**: ^4.6.1

## Dev Dependencies

- **jest**: ^29.6.1
- **supertest**: ^6.3.3

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.
