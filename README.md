## Default installation of Laravel Breeze / Vue3 / InertiaJS v2 / TailwindCSS v4.0.0-beta.2

Demonstrates the compiled spacing utility issue on TW4 beta.2

## Prerequisites

- PHP >= 8.1
- Composer
- NPM


## Installation Steps

1. Clone the repository: git clone https://github.com/dev-ctrl480/tw4-laravel11-inertiajs2.git
   
2. Navigate to the project directory: cd tw4-laravel11-inertiajs2
	
3. Install PHP dependencies: composer install

4. Install NPM dependencies: npm install

5. Create environment file: cp .env.example .env

6. Generate application key: php artisan key:generate

7. Build assets: npm run dev

8. Go to http://localhost/login and inspect the divs with "There should be spacing"

