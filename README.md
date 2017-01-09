<h1>Learn to build real world multi user SEO blog application in laravel and push to live server (shared hosting)</h1>
<h2>Learn the fundamentals of Laravel and build a real world application at the same time</h2>

<h3>Final Source Code</h3> for the course below:

https://www.udemy.com/learn-laravel-php-framework-building-multi-user-seo-blog-app/

<h4>Installation</h4>

<ul>
<li>extract the zip file</li>
<li>cd projectname</li>
<li>composer install</li>
<li>php artisan key:generate</li>
<li>Create a database and inform .env</li>
<li>php artisan migrate --seed to create and populate tables</li>
<li>Inform config/mail.php for email sends</li>
<li>php artisan vendor:publish to publish filemanager</li>
<li>php artisan serve to start the app on http://localhost:8000/</li>
</ul>

<h5>Make the necessary changes:</h5>
Add maigun domain and mailgun secret-key for mail function in .env
In App/Config/services.php supply facebook app id and secret to use login with facebook feature

Enjoy!
