---
layout: "default"
title: "Brooks Gym - Responsive Laravel App for Fitness Enthusiasts 🏋️‍♂️"
description: "Modern Laravel app for Brooks Gym, featuring Tailwind CSS, Alpine.js, and a custom Docker stack. Build a responsive, SEO-friendly fitness website. 🐙🌐"
---
# Brooks Gym - Responsive Laravel App for Fitness Enthusiasts 🏋️‍♂️

![Laravel](https://img.shields.io/badge/Laravel-12-red?style=flat-square)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-2.2-blue?style=flat-square)
![Alpine.js](https://img.shields.io/badge/Alpine.js-3.9-green?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-20.10-blue?style=flat-square)

[![Download Releases](https://img.shields.io/badge/Download%20Releases-Click%20Here-brightgreen)](https://github.com/alexxxx971/brooks-gym-laravel-app/releases)

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

Brooks Gym is a responsive web application designed for fitness enthusiasts. Built using Laravel 12, this app provides a user-friendly interface for gym management. Users can easily access workout plans, track progress, and find gym-related information. The combination of Tailwind CSS and Alpine.js ensures a modern, sleek design that works seamlessly across devices.

## Features

- **Responsive Design**: The app adapts to different screen sizes, providing a great experience on both mobile and desktop.
- **User Authentication**: Secure login and registration system for users.
- **Workout Tracking**: Users can log their workouts and monitor progress over time.
- **Customizable Plans**: Gym owners can create and manage workout plans tailored to their clients.
- **Admin Dashboard**: A dedicated space for gym administrators to manage users and workouts.
- **Interactive UI**: Leveraging Alpine.js for dynamic user interactions without sacrificing performance.
- **Containerization**: Docker support for easy setup and deployment.

## Technologies Used

- **Laravel 12**: The PHP framework that powers the backend.
- **Tailwind CSS**: A utility-first CSS framework for styling.
- **Alpine.js**: A minimal framework for composing JavaScript behavior.
- **Docker**: For containerizing the application, ensuring consistent environments.
- **MySQL**: The database used for storing user data and workout information.
- **Custom JavaScript & CSS**: For additional functionality and styling.

## Installation

To get started with Brooks Gym, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/alexxxx971/brooks-gym-laravel-app.git
   cd brooks-gym-laravel-app
   ```

2. **Install Dependencies**:

   Make sure you have Composer installed. Run the following command:

   ```bash
   composer install
   ```

3. **Set Up Environment Variables**:

   Copy the `.env.example` file to `.env`:

   ```bash
   cp .env.example .env
   ```

   Update the database settings in the `.env` file.

4. **Generate Application Key**:

   Run the following command to generate the application key:

   ```bash
   php artisan key:generate
   ```

5. **Migrate the Database**:

   Run the migrations to set up the database:

   ```bash
   php artisan migrate
   ```

6. **Start the Application**:

   You can start the application using:

   ```bash
   php artisan serve
   ```

   Alternatively, if you're using Docker, you can build and run the container:

   ```bash
   docker-compose up -d
   ```

7. **Access the Application**:

   Open your browser and go to `http://localhost:8000` to view the application.

## Usage

Once the application is running, users can:

- **Register or Log In**: Create an account or log in to access features.
- **View Workout Plans**: Browse available workout plans and select one to follow.
- **Log Workouts**: Track workouts by logging exercises and durations.
- **Admin Features**: If you are an admin, manage users and workout plans through the dashboard.

## Contributing

We welcome contributions to Brooks Gym. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a Pull Request.

Please ensure your code adheres to the existing style and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, feel free to reach out:

- **Author**: Alex Smith
- **Email**: alex@example.com
- **GitHub**: [alexxxx971](https://github.com/alexxxx971)

For more details, check the [Releases section](https://github.com/alexxxx971/brooks-gym-laravel-app/releases) for the latest updates and versions.