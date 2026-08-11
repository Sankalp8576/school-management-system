# school-management-system

A simple School Management System built with PHP (and some Hack). This repository provides the backend and minimal UI for managing students, teachers, classes, and attendance.

## Features
- Student, teacher, and class management
- Attendance recording
- Basic user authentication
- CSV import/export for student data
- Simple reporting

## Tech stack
- PHP (primary)
- Hack (small portions)
- (Optional) Composer for dependency management
- MySQL or MariaDB for the database

## Prerequisites
- PHP 7.4+ (or compatible)
- Composer
- MySQL / MariaDB
- Web server (Apache, Nginx) or PHP built-in server

## Installation
1. Clone the repo:
   git clone https://github.com/Sankalp8576/school-management-system.git
2. Change into project directory:
   cd school-management-system
3. Install PHP dependencies (if any):
   composer install
4. Copy environment/example file and update database credentials:
   cp .env.example .env
   # edit .env to set DB_HOST, DB_USER, DB_PASS, DB_NAME, etc.
5. Create the database and run migrations (if migration scripts provided):
   - Create a database in MySQL
   - Run any provided SQL or migration script (check the `database` or `migrations` folder)

## Running locally
- Using PHP built-in server:
  php -S localhost:8000 -t public
- Or configure your web server to point document root to `public/`.

## Tests
- If tests are included, run with:
  vendor/bin/phpunit

## Contributing
Contributions are welcome. Please open issues for bugs or feature requests and submit pull requests for fixes or enhancements.

## License
Specify a license here (e.g., MIT). If you want, I can add a LICENSE file.

## Contact
Maintainer: Sankalp8576
