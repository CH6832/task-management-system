# Task Management System

## About the project

The Task Manager Application is a simple yet powerful task management system built with Laravel. It provides users with the ability to manage tasks efficiently, allowing them to create, view, edit, and delete tasks seamlessly.

### Directory directory structure

    .
    ├── app/ - contains the core application code, including models, controllers, middleware, and service providers
    ├── bootstrap/ - holds files responsible for bootstrapping the Laravel framework, including the application initialization process
    ├── migrations/ - stores database migration files, which define the structure of database tables and allow for version control of the database schema
    ├── config/ - contains configuration files for various aspects of the application, such as database connections, caching, and services
    ├── database/ - contains database-related files such as seeders and factories, used for populating the database with test data
    ├── tests/ - holds test files for automated testing, including PHPUnit tests and feature tests for different parts of the application
    ├── lang/ - contains language files for internationalization and localization of the application
    ├── public/ - contains the publicly accessible files for the application, including the entry point (index.php) and assets such as images, JavaScript, and CSS files
    ├── resources/ - stores non-PHP resources such as views, JavaScript, CSS, and language files
    ├── routes/ - contains route definition files, which define the endpoints for handling HTTP requests and directing them to controllers or closures
    ├── storage/ - stores files generated by the framework, such as logs, cached files, session data, and uploaded files
    ├── tests/ - holds test files for automated testing, including PHPUnit tests and feature tests for different parts of the application.
    ├── vendor/ - contains Composer dependencies, including all third-party libraries and packages required by the application
    ├── .editorconfig - configuration file defining coding styles and formatting rules for different editors and IDEs
    ├── .env - environment configuration file containing environment-specific settings such as database credentials and application configuration
    ├── .env.example - example environment configuration file, serving as a template for creating the actual .env file
    ├── .gitattributes - configuration file for Git, specifying how certain files should be treated in version control
    ├── artisan - command-line interface for interacting with the Laravel application, allowing for tasks such as running migrations, generating code, and clearing caches
    ├── CODE_OF_CONDUCT.md - contains the code of conduct of the entire project
    ├── composer.json -  configuration file for Composer, defining the project's dependencies and other metadata
    ├── composer.lock - contains information about the exact versions of dependencies installed, ensuring consistent installations across different environments
    ├── COPYRIGHT - containing copyright information or license details for the project
    ├── LICENSE - contains project license
    ├── package.json - configuration file for npm, defining the project's JavaScript dependencies and scripts
    ├── phpunit.xml - configuration file for PHPUnit, specifying options and settings for running unit tests
    ├── README.md - project descriptions and instructions
    └── vite.config.js - configuration file for Vite.js, a build tool used for compiling and bundling JavaScript assets

## Features

* _Task Listing:_ View a list of tasks with their titles and descriptions.
* _Add New Task:_ Create a new task by providing a title and description.
* _Edit Task:_ Update the title and description of an existing task.
* _Delete Task:_ Remove a task from the system.
* _Markdown Documentation:_ Comprehensive documentation provided in Markdown format, allowing for easy understanding and customization.

## Getting started

### Prerequisites

0. Clone the repository:

```sh
git clone https://github.com/CH6832/task-management-system.git
```

1. Extract the repository:

```sh
tar -xf task-management-system.zip
```

2. Navigate into root directory:

```sh
cd task-management-system
```

### Run the application

0. Move the extracted `task-management-system` folder into `htdocs` folder in the `C:/xampp/htdocs` folder (Windows).

1. Start the server

```sh
php artisan serve
```

2. Go to `http://127.0.0.1:8000/` and start exploring the application.

### Read the docs

0. Getting started with `http://127.0.0.1:8000/docs/getting-started`

![Getting started](/storage/app/public/images/docs-getting-started.png)

1. Handle tasks with `http://127.0.0.1:8000/docs/manage-tasks`

![Getting started](/storage/app/public/images/docs-manage-tasks.png)

### Run tests:

```sh
php artisan test --testsuite=Unit
```

```sh
php artisan test --testsuite=Feature
```

## Resources used to create this project

* PHP
  * [Documentation](https://www.php.net/docs.php)
* HTML
  * [HTML: HyperText Markup Language](https://developer.mozilla.org/en-US/docs/Web/HTML)
* CSS
  * [CSS: Cascading Style Sheets - MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS?retiredLocale=de)
* Editor
  * [Visual Studio Code](https://code.visualstudio.com/)
* Frameworks
  * [XAMPP Documentation](https://www.apachefriends.org/docs/)
  * [Laravel](https://laravel.com/docs/11.x)
* Markdwon
  * [Basic syntax](https://www.markdownguide.org/basic-syntax/)
  * [Complete list of github markdown emofis](https://dev.to/nikolab/complete-list-of-github-markdown-emoji-markup-5aia)
  * [Awesome template](http://github.com/Human-Activity-Recognition/blob/main/README.md)
  * [.gitignore file](https://git-scm.com/docs/gitignore)

## License

This project is licensed under the terms of the [MIT License](LICENSE).

## COPYRIGHT

See the [COPYRIGHT](COPYRIGHT) file for copyright and licensing details.

## Code of Conduct

Please review our [Code of Conduct](CODE_OF_CONDUCT.md) before contributing to this project.