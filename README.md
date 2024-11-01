# ecommerce back end

## Description
The E-commerce Backend is a back-end application built for e-commerce platforms to manage product-related data. It provides an API for managing products, categories, and tags, leveraging Express.js for the server, Sequelize as the ORM, and PostgreSQL as the database. This backend solution efficiently handles CRUD operations for managing a product catalog, showcasing object-relational mapping (ORM) capabilities and data relationships.

## Key Features
- RESTful API for managing product data, categories, and tags.
- Object-relational mapping (ORM) with Sequelize for simplified database interactions.
- Secure and robust data management with PostgreSQL.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Technologies](#technologies)
- [Credits](#credits)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/ecommerce-demo.git
   cd ecommerce-demo

2. Install Dependencies
npm install

3. Environment Variables Setup

Create a .env file in the root directory and configure the following variables:
DB_NAME=your_database_name
DB_USER=your_database_user
DB_PASSWORD=your_database_password
DB_HOST=localhost

4. Database Setup

Create the database using Sequelize CLI: 
npx sequelize-cli db:create
npx sequelize-cli db:migrate
npx sequelize-cli db:seed:all

5. Run the Application
npm start

## Usage
Once the server is running, you can test the API with a tool like Postman or Insomnia. The backend API provides endpoints to perform CRUD operations on products, categories, and tags.

## Technologies
Express.js - Server framework for Node.js
Sequelize - ORM for SQL-based databases
PostgreSQL - SQL database for data storage

## Credits
Developer: Emily Myhand (emangelic)
Inspiration: This project was inspired by the need for a scalable backend solution for e-commerce platforms.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Open a Pull Request.
6. Don't forget to update the Credits in the README.md with your Github!

## Tests
To run tests, ensure all dependencies are installed and run:
npm test

## Contact

Please contact ema.angelic@outlook.com for business inquiries.