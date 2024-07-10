<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Inventaris Kampus Laravel

This is a Laravel-based web application for managing campus inventory.

## Prerequisites

Before you begin, ensure you have met the following requirements:

-   PHP >= 7.3
-   Composer
-   Node.js & NPM
-   MySQL or any other supported database

## Installation

Follow these steps to install and set up the project:

1. **Clone the Repository**

    ```bash
    git clone https://github.com/aqmal101/inventaris-kampus-laravel.git
    cd inventaris-kampus-laravel
    ```

2. **Install Dependencies**

    - Install PHP dependencies using Composer:

        ```bash
        composer install
        ```

    - Install JavaScript dependencies using NPM:

        ```bash
        npm install
        ```

3. **Setup Environment Variables**

    - Copy the `.env.example` file to `.env`:

        ```bash
        cp .env.example .env
        ```

    - Open the `.env` file and configure your database and other settings. Example configuration for MySQL:

        ```dotenv
        DB_CONNECTION=mysql
        DB_HOST=127.0.0.1
        DB_PORT=3306
        DB_DATABASE=your_database_name
        DB_USERNAME=your_database_user
        DB_PASSWORD=your_database_password
        ```

4. **Generate Application Key**

    ```bash
    php artisan key:generate
    ```

5. **Run Migrations**

    - Run the database migrations to create the necessary tables:

        ```bash
        php artisan migrate
        ```

6. **Seed the Database (Optional)**

    - If there are seeders available, you can populate the database with initial data:

        ```bash
        php artisan db:seed
        ```

7. **Build Frontend Assets**

    - Compile the frontend assets using Laravel Mix:

        ```bash
        npm run dev
        ```

    - For production, use:

        ```bash
        npm run prod
        ```

8. **Serve the Application**

    - Start the local development server:

        ```bash
        php artisan serve
        ```

    - The application should be accessible at `http://localhost:8000`.

## Usage

-   Visit `http://localhost:8000` in your web browser to access the application.
-   Follow the instructions on the interface to manage your campus inventory.

## Contributing

To contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgements

-   [Laravel](https://laravel.com/)
-   [Composer](https://getcomposer.org/)
-   [Node.js](https://nodejs.org/)

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

-   [Simple, fast routing engine](https://laravel.com/docs/routing).
-   [Powerful dependency injection container](https://laravel.com/docs/container).
-   Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
-   Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
-   Database agnostic [schema migrations](https://laravel.com/docs/migrations).
-   [Robust background job processing](https://laravel.com/docs/queues).
-   [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

# Inventaris Kampus Laravel

This is a Laravel-based web application for managing campus inventory.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- PHP >= 7.3
- Composer
- Node.js & NPM
- MySQL or any other supported database

## Installation

Follow these steps to install and set up the project:

1. **Clone the Repository**

    ```bash
    git clone https://github.com/aqmal101/inventaris-kampus-laravel.git
    cd inventaris-kampus-laravel
    ```

2. **Install Dependencies**

    - Install PHP dependencies using Composer:

        ```bash
        composer install
        ```

    - Install JavaScript dependencies using NPM:

        ```bash
        npm install
        ```

3. **Setup Environment Variables**

    - Copy the `.env.example` file to `.env`:

        ```bash
        cp .env.example .env
        ```

    - Open the `.env` file and configure your database and other settings. Example configuration for MySQL:

        ```dotenv
        DB_CONNECTION=mysql
        DB_HOST=127.0.0.1
        DB_PORT=3306
        DB_DATABASE=your_database_name
        DB_USERNAME=your_database_user
        DB_PASSWORD=your_database_password
        ```

4. **Generate Application Key**

    ```bash
    php artisan key:generate
    ```

5. **Run Migrations**

    - Run the database migrations to create the necessary tables:

        ```bash
        php artisan migrate
        ```

6. **Seed the Database (Optional)**

    - If there are seeders available, you can populate the database with initial data:

        ```bash
        php artisan db:seed
        ```

7. **Build Frontend Assets**

    - Compile the frontend assets using Laravel Mix:

        ```bash
        npm run dev
        ```

    - For production, use:

        ```bash
        npm run prod
        ```

8. **Serve the Application**

    - Start the local development server:

        ```bash
        php artisan serve
        ```

    - The application should be accessible at `http://localhost:8000`.

## Usage

- Visit `http://localhost:8000` in your web browser to access the application.
- Follow the instructions on the interface to manage your campus inventory.

## Contributing

To contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgements

- [Laravel](https://laravel.com/)
- [Composer](https://getcomposer.org/)
- [Node.js](https://nodejs.org/)



Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

-   **[Vehikl](https://vehikl.com/)**
-   **[Tighten Co.](https://tighten.co)**
-   **[WebReinvent](https://webreinvent.com/)**
-   **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
-   **[64 Robots](https://64robots.com)**
-   **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
-   **[Cyber-Duck](https://cyber-duck.co.uk)**
-   **[DevSquad](https://devsquad.com/hire-laravel-developers)**
-   **[Jump24](https://jump24.co.uk)**
-   **[Redberry](https://redberry.international/laravel/)**
-   **[Active Logic](https://activelogic.com)**
-   **[byte5](https://byte5.de)**
-   **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
