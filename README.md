#### Adding Spree to an existing Rails application
`` 
  https://dev-docs.spreecommerce.org/advanced/existing_app_tutorial
``
#### Error outsite of module 
`` 
  https://github.com/hotwired/stimulus-rails
``
## Installation
    - Ruby version: 3.0.1
    - Rails version: 7.0.7
    - Node version: v16.19.0

## Generate Database
    bin/rails db:create
    bin/rails db:migrate

## Run rails sever
    rails s

## Dashboad 
  Go to http://localhost:3000/admin

## Use the install generators to set up Spree
    bin/rails g spree:install --user_class=Spree::User
