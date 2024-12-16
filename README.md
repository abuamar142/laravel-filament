# E-commerce Project with Laravel Filament

This project is a learning resource for building an e-commerce application using Laravel Filament.

## Requirements

- PHP 8.1+
- Laravel v10.0+
- Livewire v3.0+
- Composer
- Node.js & npm
- MySQL or any other supported database

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/e-commerce-laravel-filament.git
    cd e-commerce-laravel-filament
    ```

2. **Install dependencies:**
    ```bash
    composer install
    npm install
    ```

3. **Copy the `.env.example` file to `.env` and configure your environment variables:**
    ```bash
    cp .env.example .env
    ```

4. **Generate an application key:**
    ```bash
    php artisan key:generate
    ```

5. **Run the migrations:**
    ```bash
    php artisan migrate
    ```

6. **Seed the database (optional):**
    ```bash
    php artisan db:seed
    ```

7. **Build the front-end assets:**
    ```bash
    npm run dev
    ```

## Running the Project

Start the development server:
```bash
php artisan serve
```

You can now access the application at `http://localhost:8000`.

## Learning Resources

- [Laravel Documentation](https://laravel.com/docs)
- [Filament Documentation](https://filamentphp.com/docs)

Happy coding!
