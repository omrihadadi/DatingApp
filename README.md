# Dating Web Application

This is a modern dating web application built using ASP.NET Core and Angular. It provides a platform for users to connect, interact, and find potential matches. The application utilizes a client-server architecture, with the frontend developed using Angular and the backend developed using ASP.NET Core.

## Features

- User Registration: Users can create new accounts by providing their basic information and preferences.
- User Profile: Users can create and manage their profiles, including uploading photos and providing detailed information about themselves.
- Matching Algorithm: The application incorporates a matching algorithm to suggest potential matches based on user preferences, interests, and compatibility factors.
- Real-Time Chat: Users can communicate with their matches through a real-time chat system, enabling seamless and instant messaging.
- Privacy and Security: The application ensures user privacy and security by implementing authentication and authorization mechanisms, as well as data encryption.

## Technologies Used

- ASP.NET Core: Backend development framework for building robust and scalable web applications.
- Angular: Frontend development framework for creating dynamic and interactive user interfaces.
- Entity Framework Core: Object-Relational Mapping (ORM) tool used for database interactions.
- SignalR: Library for implementing real-time functionality, such as real-time chat and notifications.
- JWT (JSON Web Tokens): Used for authentication and authorization of users.
- Cloud Storage: Integration with a cloud platform for storing and managing user-uploaded files.

## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/dating-web-app.git`
2. Set up the backend:
   - Install the required dependencies by running `dotnet restore` in the backend project directory.
   - Configure the database connection string in the `appsettings.json` file.
   - Run database migrations using `dotnet ef database update` to create the necessary tables.
   - Start the backend server by running `dotnet run`.
3. Set up the frontend:
   - Install the required dependencies by running `npm install` in the frontend project directory.
   - Configure the API endpoint URL in the environment files.
   - Start the development server by running `ng serve`.
4. Access the application in your browser at `http://localhost:4200`.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
