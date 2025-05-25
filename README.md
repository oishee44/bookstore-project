# Bookstore Laravel Application

This is a simple Bookstore web application built with Laravel (PHP framework). It allows users to manage a collection of books, including creating, viewing, updating, and deleting book records.

---

## 📺 Demo Video

<div align="center">
  
[![Book Store Laravel Demo](https://github.com/noobdevsam/book-store-laravel-project/blob/master/resources/Screenshot2025-05-22.png)](https://youtu.be/q6frX2yFqKc)

</div>

> _Click the image above to watch the demo on YouTube!_


---

## Features
- List all books with pagination
- Search books by title or author
- Add new books
- Edit existing books
- Delete books
- View book details

## Tech Stack
- **Backend:** Laravel 12 (PHP 8.2)
- **Frontend:** Blade templates, Bootstrap 5
- **Database:** SQLite (default, can be changed)
- **Build Tools:** Vite, Tailwind CSS (optional)

## Getting Started

### Prerequisites
- PHP 8.2 or higher
- Composer
- Node.js & npm (for frontend assets)

### Installation
1. Clone the repository:
   ```powershell
   git clone <repo-url>
   cd bookstore
   ```
2. Install PHP dependencies:
   ```powershell
   composer install
   ```
3. Install Node dependencies:
   ```powershell
   npm install
   ```
4. Copy the example environment file and set your configuration:
   ```powershell
   copy .env.example .env
   ```
5. Generate the application key:
   ```powershell
   php artisan key:generate
   ```
6. Run database migrations and seeders:
   ```powershell
   php artisan migrate --seed
   ```
7. Start the development server:
   ```powershell
   php artisan serve
   ```
8. (Optional) Build frontend assets:
   ```powershell
   npm run dev
   ```

Visit [http://localhost:8000/books](http://localhost:8000/books) to use the app.

## Project Structure
- `app/Models/Book.php` - Book model
- `app/Http/Controllers/BookController.php` - Controller for book CRUD
- `resources/views/books/` - Blade views for books
- `routes/web.php` - Web routes
- `database/migrations/` - Database schema
- `database/seeders/BookSeeder.php` - Seeds sample books

## License
MIT
