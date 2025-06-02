# Software_Engineering
This is a project of Software Engineering CSE3132 Lab course
# Install composer dependency
composer install

# Install node modules 
npm install / yarn

# Copy environment file
cp .env.example .env

# Set the Application key
php artisan key:generate

# setup the database credentials and migrate database with seeders
php artisan migrate --seed

## Development Server

Start the development server on http://localhost:8000

php artisan serve
