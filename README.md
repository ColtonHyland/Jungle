# Jungle

A mini e-commerce application built with Rails 6.1 for purposes of teaching Rails by example.

## Setup

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rails db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server

## Database

If Rails is complaining about authentication to the database, uncomment the user and password fields from `config/database.yml` in the development and test sections, and replace if necessary the user and password `development` to an existing database user.

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

- Rails 6.1 [Rails Guide](http://guides.rubyonrails.org/v6.1/)
- Bootstrap 5
- PostgreSQL 9.x
- Stripe

## Screenshots

Here are three screenshots that showcase the Jungle mini e-commerce application built with Ruby on Rails:

### Homepage

![jungle-1.png](https://github.com/ColtonHyland/Jungle/blob/201768bbe1d7e0be95d561785e1e2fc4b21818d9/jungle-1.png)
![jungle-2.png](https://github.com/ColtonHyland/Jungle/blob/201768bbe1d7e0be95d561785e1e2fc4b21818d9/jungle-2.png)

The application's homepage, where users can browse and view various products available for purchase.

### Product Details

(jungle-4.png)

The product details page, providing information about a specific item, including its description, price, and availability.

### Shopping Cart

(jungle-3.png)

You can see the user's shopping cart, where selected items are displayed, and users can review and manage their orders before proceeding to checkout.

These screenshots offer a visual glimpse of the key features and functionality of the Jungle application.
