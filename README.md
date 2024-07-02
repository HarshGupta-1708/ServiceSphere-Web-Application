# ServiceSphere Web Application

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction
ServiceSphere is a web application designed to facilitate booking various services, akin to platforms like Urban Company. It provides interfaces for users, admins, and service providers, allowing for seamless interaction and efficient service management.

## Features
- **User Registration and Authentication**: Secure user registration and login via email or social media.
- **Service Provider Application**: Allows individuals to apply as service providers by submitting necessary documentation and qualifications.
- **Admin Module**:
  - **Verification**: Admins can review and verify service provider applications.
  - **Profile Management**: Admins can manage service provider profiles and handle suspensions or revocations.
- **Service Request**:
  - **Service Selection**: Users can browse and select from a variety of services.
  - **Scheduling**: Users can schedule appointments; service providers can set availability.
- **Real-time Tracking**: Users can track the status of their service requests in real time; service providers can update their status and location.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/servicesphere.git
    ```
2. Navigate to the project directory:
    ```bash
    cd servicesphere
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```
4. Set up the database:
    ```bash
    # Configure your database settings in config/database.js
    npx sequelize db:migrate
    ```

## Usage
1. Start the server:
    ```bash
    npm start
    ```
2. Open your browser and navigate to:
    ```plaintext
    http://localhost:3000
    ```
3. Register a new account or log in with your existing credentials.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript ,React
- **Backend**: Node.js, Express
- **Database**: MONGOdb
