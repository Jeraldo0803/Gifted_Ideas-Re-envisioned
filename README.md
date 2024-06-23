# Gifted Ideas Re-envisioned

## Requirements
- Apache Web Server (XAMPP installs this for you)
- Composer
- Node & npm (For bootstrap)
- MySQL

## How to clone and run dev to your local repository
1. Clone anywhere in your local machine.
2. Under root repository `C:/Gifted_Ideas-Re-envisioned/` assuming you have Composer installed in your local machine, type in the terminal `composer install` to install all necessary dependencies.
3. Type in the terminal `cp .env.example .env` to make a .env file.
4. Type in the terminal `php artisan key:generate` to successfully fill the `APP_KEY= ` found in .env.
5. We don't have a database set up yet, visit the `.env` file and change the `DB_CONNECTION=sqlite` to `DB_CONNECTION=mysql` and remove the # comments below it.
6. Type `php artisan migrate` in the terminal to migrate the defined database toward your local MySQL database.
7. We also need to load in bootstrap, type `npm install` to install the node_modules dependencies.
8. We should have all of our dependencies, run `php artisan serve` and in a new terminal, run `npm run serve`.
