# OpportuNest - Job Listings Platform

OpportuNest is a Laravel-based platform designed for job seekers and employers to interact seamlessly. This project aims to provide a modern job listing and application system, offering an intuitive interface to connect talent with opportunities. The platform is built using **Laravel 11** and follows best practices learned from the **[30 Days to Learn Laravel](https://laracasts.com/series/30-days-to-learn-laravel-11)** series on Laracasts.

## Features
- **Job Listings**: Browse and search for jobs from various industries and locations.
- **Job Posting**: Employers can easily post new jobs with detailed descriptions.
- **Job Applications**: Registered users can apply for jobs with a single click.
- **User Roles**: Two distinct user roles (Job Seekers and Employers) with appropriate functionalities for each.
- **Responsive Design**: Mobile-first design to ensure compatibility across all devices.
- **Authentication**: Secure login and registration system for both job seekers and employers.
- **Admin Dashboard**: Admin access to manage job postings, user roles, and overall platform performance.
  
## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/mostafaamahmoudd/opportu-nest
    cd opportunest
    ```

2. Install Composer dependencies:
    ```bash
    composer install
    ```

3. Create a `.env` file by copying `.env.example`:
    ```bash
    cp .env.example .env
    ```

4. Generate an application key:
    ```bash
    php artisan key:generate
    ```

5. Set up your database in the `.env` file:
    ```env
    DB_CONNECTION=sqlite
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=your_database
    DB_USERNAME=your_username
    DB_PASSWORD=your_password
    ```

6. Run the migrations:
    ```bash
    php artisan migrate
    ```

7. Seed the database (optional):
    ```bash
    php artisan db:seed
    ```

8. Run the application:
    ```bash
    php artisan serve
    ```

## Learning Laravel through the Laracasts Series

This project was built as a part of learning from the **[30 Days to Learn Laravel 11](https://laracasts.com/series/30-days-to-learn-laravel-11)** series on Laracasts. The series covers Laravel's essential features, including routing, models, controllers, middleware, and much more. Each lesson contributed to building a fully functional job listing platform.

### Key Lessons Applied:
1. **Routing and Controllers**: Created routes for various pages and linked them to controllers that manage logic.
2. **Blade Templating**: Leveraged Blade templates for consistent layout across pages.
3. **Database and Eloquent**: Used Eloquent ORM to interact with the database for managing job posts, applications, and users.
4. **Middleware and Authentication**: Implemented secure login and role-based access controls.
5. **Validation**: Applied server-side validation for job listings and user data.
6. **Queues and Notifications**: Implemented email notifications when users apply for jobs (optional).
   
## Contributing
Feel free to submit a pull request to suggest improvements or contribute to the project.

## License
This project is open-source and available under the [MIT License](LICENSE).
