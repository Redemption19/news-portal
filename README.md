<div align="center">
    <br />
    <a href="" target="_blank">
        <img src="./public/screenshots/screen1.png" alt="Project Banner">
         <img src="./public/screenshots/screen2.png" alt="Project Banner">
          <img src="./public/screenshots/screen3.png" alt="Project Banner">
           <img src="./public/screenshots/screen4.png" alt="Project Banner">
            <img src="./public/screenshots/screen5.png" alt="Project Banner">
    </a>
    <br />
    <div>
        <img src="https://img.shields.io/badge/-PHP-black?style=for-the-badge&logoColor=white&logo=php&color=777BB4" alt="php" />
        <img src="https://img.shields.io/badge/-Laravel-black?style=for-the-badge&logoColor=white&logo=laravel&color=FF2D20" alt="laravel" />
        <img src="https://img.shields.io/badge/-MySQL-black?style=for-the-badge&logoColor=white&logo=mysql&color=4479A1" alt="mysql" />
    </div>
    <h3 align="center">News Portal and Magazine</h3>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Assets & Code](#snippets)
6. 🚀 [More](#more)

## <a name="introduction">🤖 Introduction</a>

This News Portal and Magazine project is a comprehensive web application built with Laravel 10. It offers a multi-language system, robust user authentication, role-based access control, and a professional-looking interface for both frontend and backend. The project is designed to manage and display news articles, handle advertisements, and provide a seamless user experience for both readers and administrators.

## <a name="tech-stack">⚙️ Tech Stack</a>

- Laravel 10
- PHP
- MySQL
- HTML/CSS
- JavaScript
- Bootstrap (for responsive design)

## <a name="features">🔋 Features</a>

👉 Multi-language System: Support for multiple languages to cater to a diverse audience.

👉 Laravel 10 Authentication: Secure user authentication system.

👉 User Roles and Permissions: Manage different user access levels and permissions.

👉 Professional Themes: Sleek and responsive designs for both frontend and backend.

👉 Image Upload: Easy image management for news articles and user profiles.

👉 CRUD Functionality: Comprehensive Create, Read, Update, and Delete operations.

👉 Website Settings: Customizable site-wide settings for easy management.

👉 News Advertisements: Manage and display advertisements within the news portal.

👉 Toaster Notifications: User-friendly notifications for various actions.

👉 Change Password: Secure option for users to update their passwords.

👉 Email Verification: Ensure user email authenticity through verification.

👉 Forgot Password and Reset: Seamless process for password recovery.

👉 User Profile Management: Allow users to update their profile information.

👉 SEO Optimization: Improve search engine visibility with optimized content and metadata.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally.

## Prerequisites

Make sure you have the following installed:

- Git
- PHP
- Composer
- MySQL

## Cloning the Repository

- `git clone https://github.com/yourusername/job-portal.git`
- `cd job-portal`

## Installation

Install project dependencies:

composer install
Set up Environment Variables

Create a `.env` file by copying the example:

cp `.env.example` `.env`
Update the `.env` file with your database, email, and payment gateway credentials.

## Running Migrations

### Run the database migrations to set up the schema:

php artisan migrate
Running the Project

php artisan serve

Visit http://localhost:8000 to view the project.

## <a name="more">🚀 More</a>

## <a name="deployment">🚀 Deployment</a>

To deploy this application to a production environment:

- Ensure all environment variables are properly set.
- Run `composer install` --optimize-autoloader --no-dev to install dependencies.
- Set APP_ENV=production and APP_DEBUG=false in your `.env` file.
- Run `php artisan config:cache` and `php artisan route:cache` to optimize performance.
- Set up a web server (e.g., Nginx or Apache) to serve your application.

For further customization, documentation, or support, please refer to the Laravel Official Documentation.
