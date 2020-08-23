## Integrate Stripe Payment Gateway Using Laravel

Stripe is a payment gateway that allows you to accept payments via credit card (in person or online) via moving money between your merchant account and a payment processor. This is achieved using either an online processor or a physical credit card terminal.

Laravel made the Stripe Payment Gateway integration process easier. In this project I have integrate Stripe using Laravel.

## Installation Process

1. At first cd to the project directory and run the following command :- 
<br>composer update 
2. Create a database on your database management system :- 'your_database'.
3. In .env file change the following line:- 
<br>DB_DATABASE=your_database
<br>DB_USERNAME=your_database_username
<br>DB_PASSWORD=your_database_password

<br>STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
<br>STRIPE_SECRET_KEY=your_stripe_secret_key
<br>STRIPE_CURRENCY=your_stripe_stripe_currency
4. Then cd to the project directory and run the following command:-
<br>php artisan migrate

This will complete the installation process.

## Stripe Payment Page

cd to the project directory and run the following command :-
<code>php artisan serve</code>
After that go to the following link to get the stripe payment page:-
<code>http://127.0.0.1:8000/payment</code>

## Demonstration
Demostration will be written soon.