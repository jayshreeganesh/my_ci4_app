# CodeIgniter 4 Basic App

## Overview
This is a basic CodeIgniter 4 application setup with a simple controller, route, and view. It serves as a starting point for building a web application using CodeIgniter 4.

## Requirements
- PHP 8.0 or later
- Composer
- XAMPP (or any local server with MySQL and PHP support)

## Installation

### 1. Clone or Download the Project
```sh
cd C:\xampp\htdocs
mkdir ci && cd ci
git clone https://github.com/your-repo/my_ci4_app.git
cd my_ci4_app
```

### 2. Install Dependencies
Run the following command inside the project directory:
```sh
composer install
```

### 3. Configure Environment
Rename `.env.example` to `.env` and update the environment settings:
```ini
CI_ENVIRONMENT = development
```

### 4. Start the Development Server
Run the built-in server using:
```sh
php spark serve
```
Now, visit [http://localhost:8080](http://localhost:8080) in your browser.

## Project Structure
```
my_ci4_app/
├── app/              # Application logic (Controllers, Models, Views)
├── public/           # Public assets (index.php, CSS, JS)
├── system/           # Core CodeIgniter framework
├── writable/         # Cache, logs, and session files
├── .env              # Environment configuration
├── composer.json     # Composer dependencies
└── README.md         # Project documentation
```

## Features
- MVC architecture
- Basic routing
- Simple view rendering
- Local development server (`php spark serve`)

## Troubleshooting
### Missing `vendor` Folder Error
If you see an error related to `Boot.php` missing, run:
```sh
composer install
```

### Check PHP Version
Ensure you have PHP 8.0+ installed:
```sh
php -v
```

## License
This project is open-source and free to use under the MIT License.

---

Happy coding! 🚀

