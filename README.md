<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
Laravel Live Chat Application
</p>

## About Project

I built a live chat application using laravel 9 and php 8, javascript, jquery and pusher-js. Here, we will see a live example how two users chat each other in real time.

## There are some steps to follow -

### Step - 1
Create a fresh laravel project by using these following command -
laravel new laravel-chat-application
or
composer create-project laravel/laravel laravel-chat-application

### Steps - 2
Create  an account in pusher official website and create an app.

### Steps -3
Configure .env with pusher app credentials and also change BROADCAST DRIVER log to pusher.

### Steps - 4
Create an event and make changes in event file. By creating event you need to follow this command -
php artisan make:event Message
After then changes the event file 

### Steps - 5
Create a route in web.php file and  add Request Response and Event.

### Steps - 6
Create chat view page in home.blade.php

### Steps - 7
Add required css for chat page in app.css file.

### Steps - 8
Install npm, pusher js and pusher server by following these command -
npm install
npm run dev
npm install --save laravel-echo pusher-js
composer require pusher/pusher-php-server

### Steps - 9
Make changes in bootstrap.js

### Steps - 10
Write some code for Chat js code in app.js file.

### Steps - 11
Finaly uncomment BroadcastServiceProvider from config/app.php

### Steps - 12
Run the application by using these commands -
php artisan serve
npm run dev



