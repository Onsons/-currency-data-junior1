# 1. Setup
## Ruby & Bundler
To be able to do this challange make sure you have installed a recent version of ruby and bunlder.
https://www.ruby-lang.org/en/
https://bundler.io
## Clone the project
For this challenge, you re going to use this repo as a starter project, for that you need to clone it.
`git clone https://github.com/2wunder/currency-data-junior.git`
## Install dependencies 
To install required dependencies you just need to run `bundle install`
## Database server
We assumed that you will be using *PostgreSQL* as a database server, that is why we included by default PostgreSQL datamapper adapter.
In case you want to use another database server please check the [documentation of datamapper](https://rom-rb.org/learn/) and add the right adapter.

Make sure to update database connection path in the file `config/environment.rb`.

# 2. Run the project
To run this starter project, simply execute `rackup` in your console
