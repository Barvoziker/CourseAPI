# API Using PHP Symfony and API Platform - README

## Prerequisites
- PHP 7.3 or higher
- Symfony 4.4 or higher
- API Platform 2.5 or higher

## Installation
1. Clone the repository to your local machine
2. Run `composer install` to install all dependencies
3. Set up your database connection in the `.env` file
4. Run `php bin/console doctrine:database:create` to create the database
5. Run `php bin/console doctrine:schema:create` to create the database schema
6. Run `php bin/console doctrine:fixtures:load` to load the test data

## Usage
1. Start the built-in web server by running `php bin/console server:run`
2. Use the API by making HTTP requests to the endpoint `http://localhost:8000/api`
3. Use the API documentation available at `http://localhost:8000/api/docs`

## Note
This API is intended for development and testing purposes only, it is not suitable for production use.