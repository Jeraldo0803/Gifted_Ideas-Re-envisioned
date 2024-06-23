# Gifted Ideas Re-envisioned

## How to clone and run dev to your local repository
1. Clone anywhere in your local machine.
2. Under root repository `C:/Gifted_Ideas-Re-envisioned/` assuming you have Composer installed in your local machine, type in the terminal `composer install` to install all necessary dependencies.
3. Type in the terminal `cp .env.example .env` to make a .env file.
4. Type in the terminal `php artisan key:generate` to successfully fill the `APP_KEY= ` found in .env.
5. We also need to load in bootstrap, type `npm install` to install the node_modules dependencies.
6. We should have all of our dependencies, run `php artisan serve` and in a new terminal, run `npm run serve`.
