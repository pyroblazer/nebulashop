# README

## NebulaShop E-Commerce Application

Ruby version: 3.3.4

### Setup Instructions:

#### Environment Variables:

To manage your app's secret configuration, use the `config/credentials.yml.enc` file. You can create or modify this file securely by running the command `bin/rails credentials:edit`.

#### Database:

For local development, a sqlite3 database is pre-configured.

In a production environment, make sure to set the `DATABASE_URL` environment variable to point to your PostgreSQL database.

#### Database Setup:

Execute `bin/rails db:migrate` to set up the required database tables.