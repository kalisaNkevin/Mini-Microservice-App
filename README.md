# Mini Microservice App

## Description
This project implements a microservice architecture using Node.js and Express. The architecture is designed to provide a scalable and modular solution for a mini application.

## Features
- **User Service:** Manages user registration, authentication, and profile management.
- **Product Service:** Handles product catalog management and related functionalities.
- **Order Service:** Handles order processing and management.
- **Notification Service:** Sends notifications to users regarding their orders and other updates.

## Prerequisites
- Node.js (v14 or above)
- MongoDB (v4.4 or above)
- Redis (v6 or above)

## Installation
1. Clone the repository: `git clone https://github.com/kalisaNkevin/Mini-Microservice-App.git`
2. Change to the project directory: `cd Mini-Microservice-App`
3. Install dependencies: `npm install`

## Configuration
1. In the root directory, create a `.env` file.
2. Update the `.env` file with the following configuration parameters:

## User Service
USER_SERVICE_PORT=3000
USER_SERVICE_DB_URL=mongodb://localhost:27017/user_service_db

# Product Service
PRODUCT_SERVICE_PORT=3001
PRODUCT_SERVICE_DB_URL=mongodb://localhost:27017/product_service_db

## Order Service
ORDER_SERVICE_PORT=3002
ORDER_SERVICE_DB_URL=mongodb://localhost:27017/order_service_db
ORDER_SERVICE_REDIS_URL=redis://localhost:6379

## Notification Service
NOTIFICATION_SERVICE_PORT=3003
NOTIFICATION_SERVICE_REDIS_URL=redis://localhost:6379

## Usage

1. Start the microservices: `npm start`
2. Access the microservices using their respective endpoints and ports.

The microservices can be accessed as follows:

- User Service: `http://localhost:3000`
- Product Service: `http://localhost:3001`
- Order Service: `http://localhost:3002`
- Notification Service: `http://localhost:3003`

To interact with the microservices, you can use tools like cURL or Postman. Refer to the API documentation for detailed information on the available endpoints and request formats.

## API Documentation

The API documentation for each microservice can be accessed using the following links:

- User Service: [http://localhost:3000/api-docs](http://localhost:3000/api-docs)
- Product Service: [http://localhost:3001/api-docs](http://localhost:3001/api-docs)
- Order Service: [http://localhost:3002/api-docs](http://localhost:3002/api-docs)
- Notification Service: [http://localhost:3003/api-docs](http://localhost:3003/api-docs)

The API documentation provides details about the available endpoints, request/response formats, and authentication requirements.

## Testing

To run tests for all microservices, use the following command:

npm test

## Contributing

Contributions are welcome! If you would like to contribute to the Mini Microservice App, please follow the guidelines below:

1. Fork the repository by clicking the "Fork" button on GitHub.
2. Clone the forked repository to your local machine using `git clone`.
3. Create a new branch for your feature or bug fix: `git checkout -b my-feature`.
4. Make your changes and commit them with descriptive commit messages: `git commit -m "Add feature"`
5. Push your changes to your forked repository: `git push origin my-feature`.
6. Open a pull request on the main repository, providing a detailed description of your changes.

Please ensure that your code follows the project's coding style and conventions. Include tests to cover your changes and update any relevant documentation.

## Troubleshooting

If you encounter any issues or have questions about the Mini Microservice App, please check the project's [issue tracker](https://github.com/kalisaNkevin/Mini-Microservice-App/issues) to see if a similar problem has been reported. If not, feel free to open a new issue with detailed information about the problem you are experiencing.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Authors

- [kalisaNkevin](https://github.com/kalisaNkevin)

## Acknowledgements

- [Express](https://expressjs.com)
- [Mongoose](https://mongoosejs.com)
- [Redis](https://redis.io)
- [Swagger](https://swagger.io)

## Conclusion

Thank you for your interest in the Mini Microservice App! We hope this project provides you with a solid foundation for building microservice-based applications using Node.js and Express. We encourage you to explore the code, make improvements, and customize it to suit your specific needs.

If you have any questions or feedback, please don't hesitate to reach out. Happy coding!