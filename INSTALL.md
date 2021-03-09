# Install instructions for Curio students

## Requirements

* PHP > 8.0
* A MySQL Database
* Composer
* NodeJS (for npm)

## Setup

* **Clone** the repo (DO NOT DOWNLOAD AS ZIP) - Symbolic links in the repo break when downloading as zip
* Prepare the development environment:
  1. Clone this repo
  2. Copy the `.env.example` to `.env` and configure your database details
  3. Run `composer install`
  4. Run `php artisan migrate`
  5. Run `php artisan key:generate`
  6. Run `npm install && npm run dev` to compile the resources files

* now visit the application in your webbrowser at:
  * http://localhost:8000/admin for administators to add church services (and configure settings)
  * http://localhost:8000/ for church visitors

When you start the application the database file is empty. In order for the application to run you need a default user.
Automatically a default user will be created with these credentials as default values **We recommend to change them!**

**user email: demo@example.org**

**user password: demo1234**
