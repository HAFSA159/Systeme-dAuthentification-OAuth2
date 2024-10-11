
# Centralized OAuth2 Authentication System

This project implements a **centralized OAuth2 authentication system** designed to securely manage authentication and authorization for third-party applications. The system includes a range of features to handle user management, authentication, and access control, making it an ideal solution for applications requiring robust security mechanisms.

## Features

- **Default Admin Seeder**: Automatically creates an administrator user via a seeder, allowing quick setup and initialization.
- **User Management**: The admin can manage users with full CRUD functionalities, including:
  - **Create**: Add new users to the system.
  - **Update**: Modify existing user information.
  - **Delete**: Remove users as necessary.
- **OAuth2 User Authentication**: Users can authenticate through OAuth2, receiving access tokens to interact with protected resources.
- **Token-Based Access**: Obtain secure access tokens for API data requests, ensuring secure data exchange.
- **Groups & Permissions**: Create user groups and assign specific permissions, allowing fine-grained access control over resources.
- **Unit Testing**: Comprehensive unit tests implemented using **PHPUnit** to ensure system reliability and integrity.
- **API Documentation**: Fully documented API using **Swagger**, providing clear and detailed instructions for third-party developers.

## Tech Stack

- **PHP** (Laravel)
- **OAuth2** for secure authentication
- **PHPUnit** for unit testing
- **Swagger** for API documentation

## How to Use

1. **Clone the repository** and run the following commands:
   ```bash
   composer install
   php artisan migrate --seed
   ```

2. **Run the server**:
   ```bash
   php artisan serve
   ```

3. **Access the Swagger documentation**:
   Visit `/api/documentation` to explore available API routes and test OAuth2 authentication flows.

