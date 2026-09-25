Personal Task Manager — Laravel
Project Code: WST21-PM-2026-Student Name: (Argy G. Danngcalan) Course & Year: (BSIT-2 SEC-11) Database Used: MySQL (XAMPP)

Features
Add Task
View Tasks
Edit Task
Delete Task
Update Status (Pending / Completed)

How to Run
Install XAMPP + Composer
composer install
Copy .env.example to .env, set DB_DATABASE=task_manager
php artisan key:generate
Create task_manager database in phpMyAdmin
php artisan migrate
php artisan serve
Open http://127.0.0.1:8000
