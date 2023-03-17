# BillingTrack

**NOTE**
**Minimum PHP requirement for v5.3.X is PHP >= 7.3 or >= 8.0**

BillingTrack is a self hosted billing system for freelancers and small businesses.

Host on your own server.

Your clients can view and pay their invoices online using the built-in PayPal, Stripe and Mollie integrations.

Built with Laravel

after git clone :
composer install
php artisan migrate
php artisan key:generate
From the database add main user : 
whatever email, name (please note that the password is 'secret' )
In database ; users I have make user email : invoice@email.com ;
name: invoice ( the password is secret )

